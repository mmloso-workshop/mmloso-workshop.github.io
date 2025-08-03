### Why this Shared Task?

India is home to unmatched linguistic diversity. Many languages with sizable speech communities—especially **tribal/Indigenous languages**—remain **poorly documented**, lacking the large annotated corpora that power today’s NLP breakthroughs. **Bhili** is one such language. Its limited digital presence creates barriers to healthcare messaging, disaster alerts, e-governance, and educational resources—domains that increasingly rely on text mining and machine translation.

This competition channels data-science skills toward tangible social impact by building **open-source systems** for:

- **Bhili ⇆ Hindi translation** (HRL → LRL and/or LRL → HRL)
- **Bhili sentiment analysis** (three-way emotion classification)

By tackling both tasks together, participants help **advance multilingual NLP** and develop **end-to-end pipelines** that work in **data-sparse settings**.

---

### Tasks

1. **Machine Translation (MT)**  
   Translate between **Hindi (HRL)** and **Bhili (LRL)**. Primary direction: **Hindi → Bhili**.

2. **Sentiment Analysis (SA)**  
   Classify the sentiment of Bhili texts into **three categories** *(e.g., 0/1/2 — confirm label mapping in the data card)*.

> **Evaluation metrics**: to be finalized; suggested defaults are **chrF / BLEU** for MT and **macro-F1** for SA.

---

### Dataset at a Glance

| File                   | Purpose                              | Key Columns                 |
|------------------------|--------------------------------------|-----------------------------|
| `mt_train.csv`         | Parallel data for MT training        | `id`, `source`, `target`    |
| `mt_test_features.csv` | Unlabelled source sentences (MT)     | `id`, `source`              |
| `sa_train.csv`         | Labeled texts for sentiment (SA)     | `id`, `text`, `label` *(0/1/2)* |
| `sa_test_features.csv` | Unlabelled texts for sentiment (SA)  | `id`, `text`                |
| `sample_submission.zip`| Shows correct folder & file layout   | —                           |

All texts are drawn from a **private, permissively licensed source**, cleaned and curated for research.  
**Courtesy:** *Ministry of Tribal Affairs, Government of India.*

---

### Submissions

- Follow the structure in **`sample_submission.zip`** for folder and file names.
- Upload a single archive containing:
  - MT predictions for the test split
  - SA predictions for the test split
- Include a short **system description** (1–2 pages) outlining model choices and data handling for low-resource constraints.

---

### Rules & Timeline

- **Standard Kaggle Code Competition rules apply.**  
- **External data** allowed if it is publicly available **before 07 Aug 2025** and you **link** it in your write-up.  
- **Team merger deadline:** TBD  
- **Final submission deadline:** TBD  
- **Private leaderboard reveal:** TBD  
- See the **Rules** tab on the competition page for full details.

---

### Impact & Openness

All baselines, scripts, and winning approaches will be **open-sourced** to improve **access to vital information** in Bhili and to **amplify native speakers’ voices** online.

---
layout: default                      # use the global layout
title: Shared Task & Competition     # text that shows in <title> and banner
permalink: /task/                    # URL will be …/task/
---


# Shared Task & Competition
[← Back to main page]({{ '/' | relative_url }})

Welcome to **“MMLoSo Language Challenge 2025”**! India is land of unmatched diversity, especially in terms of spoken languages. Many of these languages are tribal languages, which have a sizable number of speakers. But often, these languages are poorly documented and thus lack the massive annotated corpora that power today’s NLP breakthroughs. Limited digital presence means the native speakers face barriers in healthcare messaging, disaster alerts, e-governance, and educational resources—all of which increasingly rely on text mining and machine translation.

By building open-source systems for **LRL ⇆ HRL translation**, this competition channels deep‐learning skills toward tangible social impact: making vital information accessible in underserved languages and amplifying the voices of native speakers online. In this competition you will translate between high‐resource languages (HRL) and our focused low‐resource languages (LRL), i.e.:

- **Hindi ⇆ Bhili**  
- **Hindi ⇆ Mundari**  
- **Hindi ⇆ Gondi**  
- **English ⇆ Santali**

By tackling all tracks together, you will help push the frontier of multilingual NLP while building end‐to‐end pipelines that work in data‐sparse settings.

---

### Dataset at a Glance

| File                 | Purpose                                            | Key Columns                                  |
|----------------------|----------------------------------------------------|----------------------------------------------|
| `bhili-train.csv`    | Data for Bhili – Hindi translation training        | `row_id`, `hindi`, `bhili`                   |
| `gondari-train.csv`  | Data for Gondi – Hindi translation training        | `row_id`, `hindi`, `gondi`                   |
| `mundari-train.csv`  | Data for Mundari – Hindi translation training      | `row_id`, `hindi`, `mundari`                 |
| `santali-train.csv`  | Data for Santali – English translation training    | `row_id`, `english`, `santali`               |
| `test.csv`           | Unlabeled source sentences to translate (released later) | `row_id`, `source_sentence`, `source_lang`, `target_lang` |

_All texts are drawn from a private, permissively licensed source, cleaned and curated for research._  
**Courtesy:** *Ministry of Tribal Affairs, Government of India.*

---

## Tasks & Expected Outputs

| Task                   | What you submit                                                                                      | Where     | Metric                                 |
|------------------------|------------------------------------------------------------------------------------------------------|-----------|----------------------------------------|
| **Machine Translation**| `submission.csv` with columns:<br>`row_id`, `source_lang`, `source_sentence`, `target_lang`, `target_sentence` | On Kaggle | BLEU & chrF (tokenized, case-insensitive) |

---

### Evaluation Metric

Leaderboard ranks teams by a weighted composite score:

```text
Final Score = 0.6 × BLEU + 0.4 × chrF

> *Why 0.6 / 0.4?* Translation quality is harder to push in low-resource settings; the higher weight reflects its research importance.

---

## Rules & Timeline

- **Standard Kaggle Code Competition rules apply.**  
- **External data** allowed if publicly available **before 07 Aug 2025** and linked in your write-up.  
- **Team merger deadline:** TBD  
- **Final submission deadline:** TBD  
- **Private leaderboard reveal:** TBD  

See the **Rules** tab on the competition page for full details.  
Happy modeling – and thank you for advancing NLP for underrepresented languages!

---

## 📂 Data

#### 1. `bhili-train.csv`  
Sentences for supervised Bhili – Hindi translation.

| Column    | Type | Description                                        |
|-----------|------|----------------------------------------------------|
| `row_id`  | int  | Unique row identifier                              |
| `hindi`   | str  | Sentence in the high-resource language (Hindi)     |
| `bhili`   | str  | Gold translation in the low-resource language       |

#### 2. `mundari-train.csv`  
Sentences for supervised Mundari – Hindi translation.

| Column    | Type | Description                                        |
|-----------|------|----------------------------------------------------|
| `row_id`  | int  | Unique row identifier                              |
| `hindi`   | str  | Sentence in the high-resource language (Hindi)     |
| `mundari` | str  | Gold translation in the low-resource language       |

#### 3. `gondari-train.csv`  
Sentences for supervised Gondi – Hindi translation.

| Column    | Type | Description                                        |
|-----------|------|----------------------------------------------------|
| `row_id`  | int  | Unique row identifier                              |
| `hindi`   | str  | Sentence in the high-resource language (Hindi)     |
| `gondi`   | str  | Gold translation in the low-resource language       |

#### 4. `santali-train.csv`  
Sentences for supervised Santali – English translation.

| Column    | Type | Description                                       |
|-----------|------|---------------------------------------------------|
| `row_id`  | int  | Unique row identifier                             |
| `english` | str  | Sentence in the high-resource language (English)  |
| `santali` | str  | Gold translation in the low-resource language      |

#### 5. `test.csv`  
Unlabeled source sentences. Participants must predict the **`target_sentence`** column.

---

## Data Provenance, Licensing, & Copyrights

Machine Translation parallel corpora distilled from publicly released web-crawls and Wikipedia dumps, post-processed using the NGO-Aligned filtering toolkit.  
All text is redistributed under **Creative Commons BY-SA 4.0**. Use outside this competition must cite the original sources.

---

## Citation

If you publish work using this dataset, please cite:

```bibtex
@misc{lrlchallenge2025,
  title         = {Multimodal Models for Low-Resource Contexts and Social Impact 2025},
  year          = {2025},
  howpublished  = {Kaggle Competition},
  url           = {https://www.kaggle.com/competitions/mm-lo-so-2025}
}


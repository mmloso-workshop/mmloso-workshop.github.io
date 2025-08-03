## 🏆 Overview

### Introduction

Welcome to **“MMLoSo Language Challenge 2025”**! India is land of unmatched diversity, especially in terms of spoken languages. Many of these languages are tribal languages, which have a sizable number of speakers. But often, these languages are poorly documented and thus lack the massive annotated corpora that power today’s NLP breakthroughs. Limited digital presence means the native speakers face barriers in healthcare messaging, disaster alerts, e-governance, and educational resources—all of which increasingly rely on text mining and machine translation.

By building open-source systems for **LRL ⇆ HRL translation**, this competition channels deep-learning skills toward tangible social impact: making vital information accessible in underserved languages and amplifying the voices of native speakers online. In this competition you will translate between high-resource languages (HRL) and our focused low-resource languages (LRL):

- **Hindi ⇆ Bhili**  
- **Hindi ⇆ Mundari**  
- **Hindi ⇆ Gondi**  
- **English ⇆ Santali**

By tackling all tracks together, you will help push the frontier of multilingual NLP while building end-to-end pipelines that work in data-sparse settings.

---

### Dataset at a Glance

| File                 | Purpose                                            | Key Columns                                                |
|----------------------|----------------------------------------------------|------------------------------------------------------------|
| `bhili-train.csv`    | Data for Bhili – Hindi translation training        | `row_id`, `hindi`, `bhili`                                 |
| `gondari-train.csv`  | Data for Gondi – Hindi translation training        | `row_id`, `hindi`, `gondi`                                 |
| `mundari-train.csv`  | Data for Mundari – Hindi translation training      | `row_id`, `hindi`, `mundari`                               |
| `santali-train.csv`  | Data for Santali – English translation training    | `row_id`, `english`, `santali`                             |
| `test.csv`           | Unlabeled source sentences to translate (later)    | `row_id`, `source_sentence`, `source_lang`, `target_lang`  |

_All texts are drawn from a private, permissively licensed source, cleaned and curated for research._  
**Courtesy:** *Ministry of Tribal Affairs, Government of India.*

---

## Tasks & Expected Outputs

| Task                   | Submission Format                                                                                     | Location   | Metric                                        |
|------------------------|--------------------------------------------------------------------------------------------------------|------------|-----------------------------------------------|
| **Machine Translation**| `submission.csv` with columns:<br>`row_id`, `source_lang`, `source_sentence`, `target_lang`, `target_sentence` | Kaggle     | BLEU & chrF (tokenized, case-insensitive)     |

---

### Evaluation Metric

Leaderboard ranks teams by a weighted composite score:

```text
Final Score = 0.6 × BLEU + 0.4 × chrF

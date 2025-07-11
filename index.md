---
layout: default  
title: Welcome to MMLoSo 2025  
---
<style>
/* widen the site’s default container */
.wrapper{
  max-width: 1200px;   /* pick any width you like, e.g. 1400px or 90vw */
}
</style>

<!-- ▶️  Banner goes right after the front-matter block ◀️ -->
<img src="/assets/img/banner.png"
     alt="MMLoSo 2025 Workshop Banner"
     style="
        width:100vw;          /* fill entire viewport */
        max-width:1000;       /* <- override the theme rule */
        max-height:220px;
        object-fit:cover;
        display:block;
        position:relative;    /* pull it out of the wrapper’s center */
        margin:0 0 20px 0;"> 



<!-- Sticky Left Nav -->
<div style="
  position: fixed;
  top: 20%;
  left: 20px;
  width: 220px;
  display: flex;
  flex-direction: column;
  gap: 12px;
  z-index: 1000;
">
  <h3 style="margin: 0;">MMLoSo Workshop @ IJCNLP-AACL 2025</h3>
  <p style="font-size: 13px; margin: 0;">
    First International Workshop on<br>
    Multimodal Models for Low-Resource Contexts and Social Impact
  </p>
  <a href="https://openreview.net/group?id=aclweb.org/AACL-IJCNLP/2025/Workshop/MMLoSo&referrer=%5BHomepage%5D(%2F)#tab-recent-activity" 
     target="_blank"
     style="background-color: #2e7dd8; color: white; padding: 8px 14px;
            border-radius: 6px; text-decoration: none;
            font-weight: bold; font-size: 14px;">
    🔗 View on OpenReview
  </a>

  <hr style="width: 100%; border: 0; border-top: 1px solid #ccc; margin: 8px 0;">
  
  <a href="#about" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">About</a>
  <a href="#cfp" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Call for Papers</a>
  <a href="#task" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Shared Task and Competition</a>
  <a href="#keynotes" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Keynote Speakers</a>
  <a href="#dates" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Important Dates</a>
  <a href="#organizers" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Organizers</a>
  <a href="#pc" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Program Committee</a>
  <a href="#volunteers" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Student Volunteers</a>
  <a href="#contact" style="padding: 8px 12px; background-color: #005a9c; color: white; border-radius: 6px; text-decoration: none;">Contact</a>
</div>

<style>
body {
  max-width: 80%;
  margin-left: 2%;
  margin-right: 2%;
}

.wrapper {
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
}
</style>

<div class="wrapper">

<h1 id="mm">MMLoSo 2025</h1>
<p style="margin: 0 0 6px 0;"><strong>Multimodal Models for Low-Resource Contexts and Social Impact</strong></p>
<p style="margin: 0 0 6px 0;">📍 Co-located with IJCNLP-AACL 2025</p>
<p style="margin: 0;">📅 23rd December 2025, Mumbai, India</p>

</div>

---

## 📖 <a id="about"></a> About

This workshop brings together researchers at the intersection of multimodal learning, NLP, and AI for social good, with a focus on low-resource and underserved settings...
We invite papers on developing robust and inclusive multimodal systems that can operate effectively under data constraints. Topics include learning with multiple modalities, cross-lingual, cross-modal adaptation, and interpretable models for domains like healthcare, ecological monitoring, education, and cultural heritage preservation. Alongside papers and keynotes, a community-driven shared task will evaluate multimodal robustness and generalization in low-resource contexts.

---

## 📢 <a id="cfp"></a> Call for Papers

We focus on bridging the gap between the growing capabilities of multimodal machine learning models and the urgent needs of real-world applications in under-resourced, marginalized, or data-constrained settings. This includes scenarios where data is scarce, modalities are incomplete or imbalanced, and computational or human infrastructure may be limited.

The topics of interest for the workshop include, but are not limited to:

- **Learning with Missing or Incomplete Modalities**  
  Techniques for modality dropout, hallucination, and imputation when input signals are sparse or missing at training or inference time.

- **Few-Shot, Zero-Shot, and Transfer Learning in Multimodal Contexts**  
  Approaches that allow models pre-trained on high-resource datasets to adapt effectively to novel, low-resource domains and languages.

- **Multilingual and Multimodal Representation Learning**  
  Unifying language, vision, audio, and other modalities across multiple languages, especially those underrepresented in current benchmarks.

- **Ethical, Interpretable, and Responsible AI for Multimodal Systems**  
  Auditing and mitigating bias in multimodal systems; developing transparent models that explain decisions across modalities in high-stakes domains.

- **Benchmarking and Evaluation for Real-World Robustness**  
  Proposing new datasets, metrics, and evaluations that reflect deployment challenges in regions with limited resources or infrastructure.

- **Applications in Social Good**, including:
  - Ecological and biodiversity monitoring (e.g., combining satellite, image, and audio data)
  - Public health and epidemiology in underserved regions
  - Language documentation and cultural preservation
  - Crisis response, misinformation detection, and social justice  

---
## 📝 <a id="guidelines"></a> Submission Guidelines

The workshop invites submissions in two formats. All page limits exclude unlimited pages for references.
 - Long papers (up to 8 pages):
    This format is for presenting a substantial and complete version of research.
 - Short papers (up to 4 pages):
    This format is ideal for presenting more focused contributions, including preliminary work, work-in-progress, position papers, or descriptions of systems.

📅 **Submission link:** [OpenReview Submission Portal](https://openreview.net/group?id=aclweb.org/AACL-IJCNLP/2025/Workshop/MMLoSo)  
📑 **Review process:** Review Process: Each paper will be reviewed by at least three program committee members. The submissions will be evaluated based on their technical soundness, relevance, significance, originality, and clarity.

---

## 🏆 <a id="task"></a> Shared Task & Competition  
Details coming soon 

---
## 🎤 <a id="keynotes"></a> Keynote Speakers    

Details coming soon..
 
---

## 📅 <a id="dates"></a> Important Dates  
*(Subject to change based on IJCNLP-AACL 2025)*

- 📝 Submission Deadline: **September 29, 2025**  
- 📢 Notification: **November 3, 2025**  
- 🖋 Camera-ready Deadline: **November 11, 2025**  
- 📍 Workshop:  **December 23, 2025**

---

## 👥 <a id="organizers"></a> Organizers

<div style="display: flex; flex-wrap: wrap; gap: 20px;">
  <div style="flex: 1; min-width: 200px; text-align: center;">
    <img src="/assets/img/ankita.jpeg" alt="Ankita Shukla" style="width:120px; height:120px; object-fit: cover; border-radius: 50%;"><br>
    <strong>Ankita Shukla</strong><br>
    University of Nevada, Reno
  </div>
  <div style="flex: 1; min-width: 200px; text-align: center;">
    <img src="/assets/img/sandeep.png" alt="Sandeep Kumar" style="width:120px; height:120px; object-fit: cover; border-radius: 50%;"><br>
    <strong>Sandeep Kumar</strong><br>
    IIT Delhi
  </div>
  <div style="flex: 1; min-width: 200px; text-align: center;">
    <img src="/assets/img/amrit.jpg" alt="Amrit Singh Bedi" style="width:120px; height:120px; object-fit: cover; border-radius: 50%;"><br>
    <strong>Amrit Singh Bedi</strong><br>
    University of Central Florida
  </div>
  <div style="flex: 1; min-width: 200px; text-align: center;">
    <img src="/assets/img/tanmoy.png" alt="Tanmoy Chakraborty" style="width:120px; height:120px; object-fit: cover; border-radius: 50%;"><br>
    <strong>Tanmoy Chakraborty</strong><br>
    IIT Delhi
  </div>
</div>

---
## 📝 <a id="pc"></a> Program Committee 

We’re looking for dedicated reviewers to help maintain the high standard of our review process. Each reviewer is assigned no more than two submissions. 
Interested? [Sign up here](https://docs.google.com/forms/d/e/1FAIpQLScknm1maEyFuSNxqDqzWcYkaIOwbQbVigPzNwFJPzl-c15miw/viewform?usp=header)

---
## 🙋‍♀️ <a id="volunteers"></a> Student Volunteers
  - Shashwat Bhardwaj 
  - Debarchan Basu
  - Vaibhav Sharma
  - Pooja Singh
--- 
## ✉️ <a id="contact"></a> Contact

For any queries, email us at:  
📧 [ankitas@unr.edu](mailto:ankitas@unr.edu)



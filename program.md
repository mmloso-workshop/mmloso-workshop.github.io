---
layout: default                      # use the global layout
title: Program                       # text that shows in <title> and banner
permalink: /program/                 # URL will be …/program/
---

# Program Schedule
[← Back to main page]({{ '/' | relative_url }})

<style>
/* Table styling (GitHub Pages will render this) */
.program-table { width: 100%; border-collapse: collapse; }
.program-table th, .program-table td {
  padding: 6px 8px;
  border-bottom: 1px solid #e5e7eb;
  vertical-align: top;
  text-align: left;
}

/* Zebra striping for non-invited rows */
.program-table tr:nth-child(even):not(.invited) { background: #f5fbfd; }

/* Invited row highlight: teal-blue */
.program-table .invited {
  background: #e0f7fa;        /* soft teal-blue */
  border-left: 4px solid #26c6da;
}
</style>

<table class="program-table">
  <thead>
    <tr>
      <th>Time</th>
      <th>Session</th>
      <th>Title</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>9:00 –9: 10 am</td>
      <td>Workshop Opening</td>
      <td>—</td>
    </tr>
    <tr class="invited">
      <td>9:10–9:55 am</td>
      <td><strong>Invited Talk: David Adeline</strong><br><em>Mila – Quebec AI Institute</em></td>
      <td>Scaling Multilingual Evaluation of LLMs to Many Languages</td>
    </tr>
    <tr class="invited">
      <td>10:00–10:45 am</td>
      <td><strong>Invited Talk: Dinesh Manocha</strong><br><em>University of Maryland, College Park</em></td>
      <td>Towards Audio Intelligence and LLMs: Simulation and Understanding</td>
    </tr>
    <tr>
      <td>10:45–11:00 am</td>
      <td>Break / Posters</td>
      <td>—</td>
    </tr>
    <tr>
      <td>11:05–11:20 am</td>
      <td>Oral Talk 1</td>
      <td>Toward Automatic Safe Driving Instruction: A Large-Scale Vision-Language Model Approach</td>
    </tr>
    <tr>
      <td>11:25–11:40 am</td>
      <td>Oral Talk 2</td>
      <td>BengaliFig: A Low-Resource Challenge for Figurative and Culturally Grounded Reasoning in Bengali</td>
    </tr>
    <tr>
      <td>11:45 am–12:00 pm</td>
      <td>Oral Talk 3</td>
      <td>Towards Blind and Low-Vision Accessibility of Lightweight VLMs and Custom LLM-Evals</td>
    </tr>
    <tr>
      <td>12:00–12:15 pm</td>
      <td>Oral Talk 4</td>
      <td>Artwork Interpretation with Vision Language Models: A Case Study on Emotions and Emotion Symbols</td>
    </tr>
    <tr>
      <td>12:15–12:30 pm</td>
      <td>Oral Talk 5</td>
      <td>TRepLiNa: Layer-wise CKA + REPINA Alignment Improves Low-Resource Machine Translation in Aya-23 8B</td>
    </tr>
    <tr>
      <td>12:30–1:45 pm</td>
      <td>Lunch / Posters</td>
      <td>—</td>
    </tr>
    <tr class="invited">
      <td>1:45–2:30 pm</td>
      <td><strong>Invited Talk: Roy Ka-Wei Lee</strong><br><em>Singapore University of Technology and Design</em></td>
      <td>AI for Safer Online Spaces: Combating Hate and Harm in the Digital World</td>
    </tr>
    <tr class="invited">
      <td>2:35–3:20 pm</td>
      <td><strong>Invited Talk: Shamsudeen Muhammad</strong><br><em>Google DeepMind Academic Fellow</em></td>
      <td>The Illusion of Inclusion: How LLMs Misrepresent African Languages and Cultural Contexts</td>
    </tr>
    <tr>
      <td>3:25–3:40 pm</td>
      <td>Oral Talk 6</td>
      <td>MemeGuard: Transformer-Based Fusion for Multimodal Propaganda Detection in Low-Resource Social Media Memes</td>
    </tr>
    <tr>
      <td>3:45–4:00 pm</td>
      <td>Oral Talk 8 (Challenge Track)</td>
      <td>LoRAs in All Directions: Directional Adapters and Noisy-Channel Reranking for Indic MT</td>
    </tr>
    <tr>
      <td>4:00–4:15 pm</td>
      <td>Oral Talk 9 (Challenge Track)</td>
      <td>Breaking Language Barriers: Adapting NLLB-200 and mBART for Bhilli, Gondi, Mundari, and Santali Without Source Language Proficiency</td>
    </tr>
    <tr>
      <td>4:15–4:30 pm</td>
      <td>Oral Talk 10 (Challenge Track)</td>
      <td>Divide and Translate: Parameter Isolation with Encoder Freezing for Low-Resource Indic NMT</td>
    </tr>
    <tr>
      <td>4:30–4:45 pm</td>
      <td>Oral Talk 11 (Challenge Track)</td>
      <td>JHARNA-MT: A Copy-Augmented Hybrid of LoRA-Tuned NLLB and Lexical SMT with Minimum Bayes Risk Decoding for Low-Resource Indic Languages</td>
    </tr>
  </tbody>
</table>

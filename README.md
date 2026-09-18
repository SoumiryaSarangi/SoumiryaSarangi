<!--
  ══════════════════════════════════════════════════════════════
   SOUMIRYA SARANGI — PROFILE README  ·  v3
   Repo: github.com/SoumiryaSarangi/SoumiryaSarangi

   Palette (keep consistent if you edit):
     bg #0D1117 · accent #00D9FF · deep #0A3D62 · text #C9D1D9

   WIDGET POLICY: every image here renders without burning a
   shared GitHub API token. The API-backed cards (stats,
   top-langs, activity graph) sit in a commented block in
   section 05 — uncomment them AFTER you deploy your own
   instance.
  ══════════════════════════════════════════════════════════════
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:0A3D62,100:00D9FF&height=210&section=header&text=Soumirya%20Sarangi&fontSize=54&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=AI%2FML%20Engineer%20%C2%B7%20Full-Stack%20Developer&descSize=18&descAlignY=56" alt="Soumirya Sarangi" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3200&pause=700&color=00D9FF&center=true&vCenter=true&width=780&lines=Deep+learning+on+satellite+imagery.;Full-stack+products+around+the+models.;PyTorch+%C2%B7+Next.js+%C2%B7+TypeScript+%C2%B7+Python;Models+that+survive+a+sealed+holdout." alt="Intro" />

<br />

<a href="https://www.linkedin.com/in/soumirya-sarangi-262b38320/"><img src="https://img.shields.io/badge/LinkedIn-0A3D62?style=for-the-badge&logo=linkedin&logoColor=00D9FF" alt="LinkedIn" /></a>
<a href="mailto:soumiryasarangi@gmail.com"><img src="https://img.shields.io/badge/Email-0A3D62?style=for-the-badge&logo=gmail&logoColor=00D9FF" alt="Email" /></a>
<a href="https://github.com/SoumiryaSarangi?tab=repositories"><img src="https://img.shields.io/badge/Repositories-0A3D62?style=for-the-badge&logo=github&logoColor=00D9FF" alt="Repos" /></a>
<img src="https://img.shields.io/github/followers/SoumiryaSarangi?style=for-the-badge&logo=github&label=Followers&color=00D9FF&labelColor=0A3D62" alt="Followers" />
<img src="https://komarev.com/ghpvc/?username=SoumiryaSarangi&style=for-the-badge&color=00D9FF&label=VIEWS" alt="Views" />

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:00D9FF,100:0D1117&height=3" width="100%" alt="" />

## `01` &nbsp;·&nbsp; Overview

```yaml
name:      Soumirya Sarangi
role:      AI/ML Engineer  ·  Full-Stack Developer
education: B.Tech CSE @ Lovely Professional University  ·  CGPA 8.4
based_in:  Phagwara, Punjab, India
focus:     LLM-powered product surfaces in Next.js
stack:     PyTorch · Python · Next.js · TypeScript
```

I build machine learning systems end to end — the model, the evaluation harness that decides whether the model is any good, and the product surface that puts it in front of a user.

Most of my recent work sits in remote sensing, where the imagery is single-channel, speckled, and nothing like the natural-image datasets standard architectures are tuned for. That constraint has shaped how I approach the rest of it: establish a classical baseline before reaching for a network, measure against a holdout that was sealed before training started, and treat the interface between pipeline stages as a contract rather than an assumption.

The other half of my time goes into full-stack product work — Next.js applications with real auth, offline-capable storage, and deploys that stay up without supervision.

<table>
<tr>
<td width="50%" valign="top">

**Areas of focus**

**Computer vision** — semantic segmentation and scene classification on non-RGB, low-SNR imagery.

**Classical machine learning** — feature engineering with HOG and TF-IDF, SVMs, ensemble methods. Often the correct answer, and always the right baseline.

**Applied full-stack** — the model is a component. I build the system it lives inside.

</td>
<td width="50%" valign="top">

**Background**

| | |
|:--|:--|
| 🛰️ | Smart India Hackathon 2026 |
| 🏆 | Top 10 of 50+ teams, college hackathon |
| 📜 | Data Science & ML with GenAI — Cipher School |
| 🧪 | Software Testing — NPTEL |
| 💾 | DBMS & C++ — Infosys Springboard |
| 🐙 | Pull Shark |

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:00D9FF,100:0D1117&height=3" width="100%" alt="" />

## `02` &nbsp;·&nbsp; How I work

A model that reports 94% accuracy and a model that *has* 94% accuracy are different objects, and the difference is entirely in how the number was produced. These are the practices I hold to, and most of them exist because I have been burned by the alternative.

<table>
<tr>
<td width="33%" valign="top">

**Baseline before architecture**

A classical method goes in first — thresholding, hand-built features, a linear model. Without it there is no way to know whether a network is contributing anything beyond parameter count.

</td>
<td width="33%" valign="top">

**Evaluation before optimisation**

Splits at the scene level, never the tile level, so that neighbouring crops cannot leak across the boundary. Thresholds chosen on validation and frozen. The holdout stays sealed until the run is finished.

</td>
<td width="33%" valign="top">

**Contracts between stages**

Pipeline stages communicate through schema-validated files, not shared imports. Each stage can be rewritten, or handed to someone else, without touching the ones around it.

</td>
</tr>
<tr>
<td width="33%" valign="top">

**Failure modes over headline metrics**

An aggregate score hides the cases that matter. I spend more time on the confusion matrix and on the specific inputs a model gets wrong than on the summary number.

</td>
<td width="33%" valign="top">

**Interpretability where it is cheap**

If a feature-based model gets within a few points of a network, the feature-based model usually wins — it can be debugged, explained, and defended.

</td>
<td width="33%" valign="top">

**Ship the whole thing**

A result in a notebook is not a deliverable. I take projects through to a deployed interface, because the last 20% is where most of the real problems surface.

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:00D9FF,100:0D1117&height=3" width="100%" alt="" />

## `03` &nbsp;·&nbsp; Selected work

### 🛰️ &nbsp; UDGAM — Oil Spill Detection & Vessel Attribution from Sentinel-1 SAR

<img src="https://img.shields.io/badge/Smart%20India%20Hackathon%202026-00D9FF?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/PyTorch%202.6-0A3D62?style=flat-square&logo=pytorch&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Python%203.13-0A3D62?style=flat-square&logo=python&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/private%20repository-0A3D62?style=flat-square&labelColor=0D1117" />

> **Problem** — Synthetic aperture radar can see oil slicks through cloud and darkness, which makes it the only practical sensor for continuous maritime monitoring. It also renders wind shadows, biogenic slicks and low-wind zones as dark patches that look almost identical to oil. A segmenter trained on spill imagery will confidently outline all of them.

> **Approach** — I own the detection stage of a three-stage pipeline (detect → backward drift to origin → vessel attribution). Rather than asking one network to both find and disambiguate, I built a gated two-network detector: a CNN scene classifier decides whether a scene plausibly contains oil at all, and only then does a U-Net segmenter run. Trained on a 2,570-scene corpus with per-scene MAD normalisation and scene-level splits.

> **Result** — 0.942 scene-classification accuracy and 0.757 pooled oil-class IoU against a 0.689 classical baseline, measured on a 450-scene holdout sealed before training. The gate lifted look-alike rejection from 0.08 to 0.84 at equal IoU — the clearest evidence that the architectural decision, not the extra capacity, was doing the work. Against SkyTruth Cerulean on real incidents, median agreement was 0.553 IoU.

<sub>Also built the classical CV path behind the live demo — dark-spot thresholding, a 10-feature RandomForest, and a land-masked ship-contact detector that cut false contacts from 142 to 110 — emitting schema-validated GeoJSON for the downstream stages.</sub>

<sub>`PyTorch` · `CUDA 12.4` · `rasterio` · `OpenCV` · `scikit-image` · `Shapely` · `Google Earth Engine`</sub>

<br />

### 🎓 &nbsp; SenseiAI — AI Study Platform

<a href="https://exam-prep-ai-ebon.vercel.app"><img src="https://img.shields.io/badge/live%20demo-00D9FF?style=flat-square&labelColor=0D1117" /></a>
<a href="https://github.com/SoumiryaSarangi/ExamPrep-AI"><img src="https://img.shields.io/badge/source-0A3D62?style=flat-square&logo=github&logoColor=00D9FF&labelColor=0D1117" /></a>
<img src="https://img.shields.io/github/stars/SoumiryaSarangi/ExamPrep-AI?style=flat-square&labelColor=0D1117&color=0A3D62" />
<img src="https://img.shields.io/github/last-commit/SoumiryaSarangi/ExamPrep-AI?style=flat-square&labelColor=0D1117&color=0A3D62" />

> **Problem** — Students receive lecture material as slides and get no structure on top of it. The tools that promise to fix this require an account, an API key, and permission to upload coursework to someone else's server — which is enough friction that most people give up before the first session.

> **Approach** — A Next.js 15 application that ingests PDF and PPTX slides and generates structured notes, flashcards, quizzes and timed exam simulations through LLaMA 3.3 70B on Groq. Flashcards run on SM-2 spaced repetition. A per-topic weak-area tracker reads quiz history and assembles the next practice set from the topics the user is actually failing. The architecture is local-first: all user data lives in IndexedDB via Dexie, Supabase auth is optional, and a demo mode works with no API key at all.

> **Result** — A deployed, working product that needs no signup to try. The offline-first decision turned out to matter more than any model choice — it removed the entire onboarding barrier and made the tool usable on unreliable campus networks.

<sub>`Next.js 15 (App Router)` · `TypeScript` · `Radix UI / shadcn` · `Zustand` · `Dexie` · `PDF.js` · `Supabase`</sub>

<br />

### 🤖 &nbsp; ML Educational Chatbot

<a href="https://github.com/SoumiryaSarangi/ml-educational-chatbot"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/github/stars/SoumiryaSarangi/ml-educational-chatbot?style=flat-square&labelColor=0D1117&color=0A3D62" />
<img src="https://img.shields.io/github/languages/top/SoumiryaSarangi/ml-educational-chatbot?style=flat-square&labelColor=0D1117&color=0A3D62" />

> **Problem** — Conversational Q&A has become synonymous with calling a large language model, which makes it easy to forget where the genuine difficulty lies. For a narrow, well-bounded domain, it is not obvious that an LLM is required at all — but almost nobody checks.

> **Approach** — A domain-restricted assistant for AI, ML and data science questions, built with no LLM anywhere in the stack. TF-IDF vectorisation feeds a Naive Bayes intent classifier; responses are retrieved by cosine similarity over a curated knowledge base; the interface runs on Dash.

> **Result** — Within its domain the system answers reliably, responds in milliseconds, runs on CPU, costs nothing per query, and every decision it makes can be traced to a specific feature weight. It also fails cleanly and visibly outside its domain, which is arguably a feature. A useful calibration of what the classical toolbox still covers.

<sub>`Python` · `scikit-learn` · `Dash` · `NumPy`</sub>

<br />

### 👕 &nbsp; Fashion-MNIST Classifier — HOG + Linear SVM

<a href="https://github.com/SoumiryaSarangi/Image-Classifier-for-fashion-mnist-hog-svm"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/github/stars/SoumiryaSarangi/Image-Classifier-for-fashion-mnist-hog-svm?style=flat-square&labelColor=0D1117&color=0A3D62" />
<img src="https://img.shields.io/github/languages/top/SoumiryaSarangi/Image-Classifier-for-fashion-mnist-hog-svm?style=flat-square&labelColor=0D1117&color=0A3D62" />

> **Problem** — Fashion-MNIST is usually approached as a CNN exercise. The more instructive question is how much of the accuracy comes from learned features versus from the classifier on top of them — and how good a well-chosen hand-built descriptor still is.

> **Approach** — A modular scikit-learn pipeline: HOG descriptors into a linear SVM, with each stage independently swappable. Feature extraction and fitted models are cached to disk, so re-running an experiment costs seconds rather than minutes. Evaluation produces per-class precision, recall and a full confusion matrix rather than a single accuracy figure.

> **Result** — 89.2% test accuracy with no neural network and no GPU. The per-class breakdown localises nearly all remaining error to the shirt/coat/pullover cluster, which is exactly where texture-based descriptors would be expected to struggle — a result that explains itself instead of requiring interpretation.

<sub>`Python` · `scikit-learn` · `scikit-image` · `NumPy` · `Matplotlib`</sub>

<br />

<sub>Further work — including a mobile-first [meat freshness analyser](https://github.com/SoumiryaSarangi/Meat-freshness-analyzer) and an [interactive OS deadlock detection tool](https://github.com/SoumiryaSarangi/OS-CA-Automated-Deadlock-Detection-Tool) — is in the <a href="https://github.com/SoumiryaSarangi?tab=repositories">repositories tab</a>.</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:00D9FF,100:0D1117&height=3" width="100%" alt="" />

## `04` &nbsp;·&nbsp; Toolkit

<div align="center">

<sub>**LANGUAGES**</sub>

<img src="https://skillicons.dev/icons?i=python,cpp,c,java,ts,js&theme=dark" alt="Languages" />

<sub>**DEEP LEARNING & COMPUTER VISION**</sub>

<img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv&theme=dark" alt="ML" />

<img src="https://img.shields.io/badge/rasterio-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/scikit--image-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Shapely-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/NumPy-0A3D62?style=flat-square&logo=numpy&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Google%20Earth%20Engine-0A3D62?style=flat-square&logo=googleearth&logoColor=00D9FF&labelColor=0D1117" />

<sub>**WEB & FULL-STACK**</sub>

<img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,tailwind,html,css&theme=dark" alt="Web" />

<sub>**DATA, INFRASTRUCTURE & TOOLING**</sub>

<img src="https://skillicons.dev/icons?i=mysql,postgres,supabase,git,github,vercel,linux,vscode&theme=dark" alt="Tools" />

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:00D9FF,100:0D1117&height=3" width="100%" alt="" />

## `05` &nbsp;·&nbsp; Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=SoumiryaSarangi&hide_border=true&background=0D1117&stroke=1F6FEB&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF&sideLabels=C9D1D9&dates=8B949E&sideNums=C9D1D9&currStreakNum=FFFFFF" alt="Streak" />

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SoumiryaSarangi/SoumiryaSarangi/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SoumiryaSarangi/SoumiryaSarangi/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/SoumiryaSarangi/SoumiryaSarangi/output/github-contribution-grid-snake.svg" />
</picture>

</div>

<!--
  ┌──────────────────────────────────────────────────────────────┐
  │  SELF-HOSTED STATS — uncomment after deploying your own      │
  │  instance. These cards need a GitHub token, which is why     │
  │  the shared public instances keep failing.                   │
  │                                                              │
  │  1. Fork  github.com/anuraghazra/github-readme-stats         │
  │  2. Import the fork on vercel.com, accept all defaults       │
  │  3. Add env var  PAT_1 = a classic token, public_repo scope  │
  │  4. Replace YOUR-INSTANCE with your new Vercel domain        │
  │  5. Delete the two comment markers around this block         │
  │                                                              │
  │  Same procedure for the activity graph:                      │
  │  github.com/Ashutosh00710/github-readme-activity-graph       │
  └──────────────────────────────────────────────────────────────┘

<div align="center">

<img height="165" src="https://YOUR-INSTANCE.vercel.app/api?username=SoumiryaSarangi&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9&icon_color=00D9FF&rank_icon=github" alt="Stats" />
<img height="165" src="https://YOUR-INSTANCE.vercel.app/api/top-langs/?username=SoumiryaSarangi&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9" alt="Top languages" />

<br /><br />

<img src="https://YOUR-GRAPH-INSTANCE.vercel.app/graph?username=SoumiryaSarangi&bg_color=0D1117&color=00D9FF&line=1F6FEB&point=FFFFFF&area=true&hide_border=true&custom_title=Contribution%20Activity" alt="Activity graph" />

</div>

-->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:00D9FF,100:0D1117&height=3" width="100%" alt="" />

## `06` &nbsp;·&nbsp; Contact

<div align="center">

**Open to internships and research collaborations in computer vision, remote sensing, and applied machine learning.**

If you are working on something in geospatial AI — or you have a problem where the classical approach deserves a fair trial before the network — I would be glad to hear about it.

<br />

<a href="https://www.linkedin.com/in/soumirya-sarangi-262b38320/"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A3D62?style=for-the-badge&logo=linkedin&logoColor=00D9FF" /></a>
<a href="mailto:soumiryasarangi@gmail.com"><img src="https://img.shields.io/badge/soumiryasarangi%40gmail.com-0A3D62?style=for-the-badge&logo=gmail&logoColor=00D9FF" /></a>

<br /><br />

<sub><i>Evaluation discipline beats model complexity. Most of the time.</i></sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,55:0A3D62,100:0D1117&height=130&section=footer" width="100%" alt="" />

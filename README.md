<!--
  ══════════════════════════════════════════════════════════════
   SOUMIRYA SARANGI — PROFILE README  ·  v4
   Repo: github.com/SoumiryaSarangi/SoumiryaSarangi

   This version uses BESPOKE SVG ASSETS in ./assets/.
   Commit the assets/ folder alongside this file or the hero,
   dividers and project icons will not render.

   Palette:  bg #0D1117 · accent #00D9FF · deep #0A3D62 · #C9D1D9
  ══════════════════════════════════════════════════════════════
-->

<img src="assets/header.svg" width="100%" alt="Soumirya Sarangi — AI/ML Engineer and Full-Stack Developer" />

<div align="center">

<a href="https://www.linkedin.com/in/soumirya-sarangi-262b38320/"><img src="https://img.shields.io/badge/LinkedIn-0A3D62?style=for-the-badge&logo=linkedin&logoColor=00D9FF" alt="LinkedIn" /></a>
<a href="mailto:soumiryasarangi@gmail.com"><img src="https://img.shields.io/badge/Email-0A3D62?style=for-the-badge&logo=gmail&logoColor=00D9FF" alt="Email" /></a>
<a href="https://github.com/SoumiryaSarangi?tab=repositories"><img src="https://img.shields.io/badge/Repositories-0A3D62?style=for-the-badge&logo=github&logoColor=00D9FF" alt="Repositories" /></a>
<img src="https://img.shields.io/github/followers/SoumiryaSarangi?style=for-the-badge&logo=github&label=Followers&color=00D9FF&labelColor=0A3D62" alt="Followers" />
<img src="https://komarev.com/ghpvc/?username=SoumiryaSarangi&style=for-the-badge&color=00D9FF&label=VIEWS" alt="Views" />

</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `01` &nbsp;·&nbsp; About

```yaml
name:      Soumirya Sarangi
role:      AI/ML Engineer  ·  Full-Stack Developer
education: B.Tech CSE @ Lovely Professional University  ·  CGPA 8.4
domain:    computer vision on satellite SAR imagery
stack:     PyTorch · Python · Next.js · TypeScript
```

I build machine learning systems end to end — the model, the evaluation that decides whether it is any good, and the product surface that puts it in front of a user. Most of my recent work is in remote sensing, on imagery that looks nothing like the natural-image datasets standard architectures are tuned for.

<img src="assets/divider.svg" width="100%" alt="" />

## `02` &nbsp;·&nbsp; Selected work

<table>
<tr>
<td width="50%" valign="top">

### <img src="assets/icons/satellite.svg" width="21" align="top" /> &nbsp;UDGAM

<img src="https://img.shields.io/badge/SIH%202026-00D9FF?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/PyTorch-0A3D62?style=flat-square&logo=pytorch&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/private-0A3D62?style=flat-square&labelColor=0D1117" />

*SAR sees through cloud and darkness — but renders wind shadows and algal slicks almost identically to oil.*

Detection stage of a maritime oil spill pipeline. I gated a U-Net segmenter behind a CNN scene classifier, trained on 2,570 Sentinel-1 scenes.

**0.942** scene accuracy · **0.757** pooled IoU on a sealed holdout · look-alike rejection **0.08 → 0.84**

<sub>`PyTorch` · `rasterio` · `OpenCV` · `Earth Engine`</sub>

</td>
<td width="50%" valign="top">

### <img src="assets/icons/study.svg" width="21" align="top" /> &nbsp;SenseiAI

<a href="https://exam-prep-ai-ebon.vercel.app"><img src="https://img.shields.io/badge/live%20demo-00D9FF?style=flat-square&labelColor=0D1117" /></a>
<a href="https://github.com/SoumiryaSarangi/ExamPrep-AI"><img src="https://img.shields.io/badge/source-0A3D62?style=flat-square&logo=github&logoColor=00D9FF&labelColor=0D1117" /></a>
<img src="https://img.shields.io/github/last-commit/SoumiryaSarangi/ExamPrep-AI?style=flat-square&label=updated&labelColor=0D1117&color=0A3D62" />

*Study tools demand an account and an API key before the first session — enough friction that most students never reach it.*

Turns lecture PDFs into notes, flashcards, quizzes and timed exams via LLaMA 3.3 70B on Groq. SM-2 spaced repetition and a weak-area tracker that builds practice sets from what you are failing.

Local-first on IndexedDB — demo mode needs no key at all.

<sub>`Next.js 15` · `TypeScript` · `Zustand` · `Dexie`</sub>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### <img src="assets/icons/shield.svg" width="21" align="top" /> &nbsp;A.R.T.H.U.R.

<a href="https://github.com/SoumiryaSarangi/A.R.T.H.U.R.-Active-Response-Tether-Heuristic-User-Recognizer"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/badge/FastAPI-0A3D62?style=flat-square&logo=fastapi&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/real--time%20CV-0A3D62?style=flat-square&labelColor=0D1117" />

*Screen locks fire while you are still sitting there, and stay open after you walk away.*

Physical zero-trust workstation guard. MediaPipe face detection establishes presence, Bluetooth proximity confirms it, and a three-state machine escalates between them instead of flipping a boolean.

FastAPI streaming over WebSockets to a Next.js front end.

<sub>`Python` · `FastAPI` · `MediaPipe` · `WebSockets`</sub>

</td>
<td width="50%" valign="top">

### <img src="assets/icons/chatbot.svg" width="21" align="top" /> &nbsp;ML Educational Chatbot

<a href="https://github.com/SoumiryaSarangi/ml-educational-chatbot"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/badge/no%20LLM-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/github/last-commit/SoumiryaSarangi/ml-educational-chatbot?style=flat-square&label=updated&labelColor=0D1117&color=0A3D62" />

*Conversational Q&A has become synonymous with calling an LLM. For a narrow domain it may not be necessary — but almost nobody checks.*

TF-IDF into a Naive Bayes intent classifier, responses retrieved by cosine similarity over a curated knowledge base, served through Dash.

Millisecond responses on CPU, zero cost per query, every decision traceable to a feature weight.

<sub>`Python` · `scikit-learn` · `Dash`</sub>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### <img src="assets/icons/grid.svg" width="21" align="top" /> &nbsp;Fashion-MNIST · HOG + SVM

<a href="https://github.com/SoumiryaSarangi/Image-Classifier-for-fashion-mnist-hog-svm"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/badge/89.2%25%20accuracy-0A3D62?style=flat-square&labelColor=0D1117" />

*Usually treated as a CNN exercise. The more useful question is how far a hand-built descriptor still gets you.*

HOG descriptors into a linear SVM, each stage swappable, features and models cached so re-runs cost seconds.

**89.2%** test accuracy, no network and no GPU. Per-class evaluation puts nearly all residual error in the shirt/coat/pullover cluster — exactly where texture descriptors should struggle.

<sub>`Python` · `scikit-learn` · `scikit-image`</sub>

</td>
<td width="50%" valign="top">

### <img src="assets/icons/scan.svg" width="21" align="top" /> &nbsp;Meat Freshness Analyzer

<a href="https://marbl-app.onrender.com"><img src="https://img.shields.io/badge/live%20demo-00D9FF?style=flat-square&labelColor=0D1117" /></a>
<a href="https://github.com/SoumiryaSarangi/Meat-freshness-analyzer"><img src="https://img.shields.io/badge/source-0A3D62?style=flat-square&logo=github&logoColor=00D9FF&labelColor=0D1117" /></a>
<img src="https://img.shields.io/github/last-commit/SoumiryaSarangi/Meat-freshness-analyzer?style=flat-square&label=updated&labelColor=0D1117&color=0A3D62" />

*Freshness at point of sale is judged by eye, inconsistently, by people with no time to be careful.*

Camera-based classifier that grades a cut for freshness and routes it by physical size. Mobile-first, because the user is standing at a counter.

The deployment constraint drove the modelling — everything had to run fast on a phone browser.

<sub>`Python` · `OpenCV` · `scikit-learn` · `Flask`</sub>

</td>
</tr>
</table>

<sub>Also: an <a href="https://github.com/SoumiryaSarangi/OS-CA-Automated-Deadlock-Detection-Tool">interactive OS deadlock detection tool</a> — matrix-based and Wait-For Graph, visualised step by step.</sub>

<img src="assets/divider.svg" width="100%" alt="" />

## `03` &nbsp;·&nbsp; How I work

<table>
<tr>
<td width="33%" valign="top">

**Baseline first**

A classical method goes in before a network, so there is something to measure the network against.

</td>
<td width="33%" valign="top">

**Honest splits**

Splits at the scene level, thresholds fixed on validation, holdout opened once at the end.

</td>
<td width="33%" valign="top">

**Ship it**

A result in a notebook is not a deliverable. I take projects through to something deployed.

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="" />

## `04` &nbsp;·&nbsp; Toolkit

<div align="center">

<sub>**LANGUAGES**</sub>

<img src="https://skillicons.dev/icons?i=python,cpp,c,java,ts,js&theme=dark" alt="Languages" />

<sub>**DEEP LEARNING & COMPUTER VISION**</sub>

<img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv&theme=dark" alt="Machine learning" />

<img src="https://img.shields.io/badge/rasterio-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/scikit--image-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Shapely-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/MediaPipe-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/NumPy-0A3D62?style=flat-square&logo=numpy&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Google%20Earth%20Engine-0A3D62?style=flat-square&logo=googleearth&logoColor=00D9FF&labelColor=0D1117" />

<sub>**WEB & FULL-STACK**</sub>

<img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,fastapi,tailwind,html,css&theme=dark" alt="Web" />

<sub>**DATA, INFRASTRUCTURE & TOOLING**</sub>

<img src="https://skillicons.dev/icons?i=mysql,postgres,supabase,git,github,vercel,linux,vscode&theme=dark" alt="Tooling" />

</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `05` &nbsp;·&nbsp; Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=SoumiryaSarangi&hide_border=true&background=0D1117&stroke=1F6FEB&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF&sideLabels=C9D1D9&dates=8B949E&sideNums=C9D1D9&currStreakNum=FFFFFF" alt="Contribution streak" />

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
  └──────────────────────────────────────────────────────────────┘

<div align="center">

<img height="165" src="https://YOUR-INSTANCE.vercel.app/api?username=SoumiryaSarangi&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9&icon_color=00D9FF&rank_icon=github" alt="Stats" />
<img height="165" src="https://YOUR-INSTANCE.vercel.app/api/top-langs/?username=SoumiryaSarangi&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9" alt="Top languages" />

</div>

-->

<img src="assets/divider.svg" width="100%" alt="" />

## `06` &nbsp;·&nbsp; Contact

<div align="center">

**Open to internships and research collaborations in computer vision, remote sensing, and applied machine learning.**

<br />

<a href="https://www.linkedin.com/in/soumirya-sarangi-262b38320/"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A3D62?style=for-the-badge&logo=linkedin&logoColor=00D9FF" /></a>
<a href="mailto:soumiryasarangi@gmail.com"><img src="https://img.shields.io/badge/soumiryasarangi%40gmail.com-0A3D62?style=for-the-badge&logo=gmail&logoColor=00D9FF" /></a>

</div>

<img src="assets/divider.svg" width="100%" alt="" />

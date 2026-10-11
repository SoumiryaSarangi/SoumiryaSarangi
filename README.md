<!--
  SOUMIRYA SARANGI · PROFILE README · v5
  Assets live in ./assets/ (header, divider, icons). Commit them with this file.
  Palette: bg #0D1117 · accent #00D9FF · deep #0A3D62 · text #C9D1D9
-->

<img src="assets/header.svg" width="100%" alt="Soumirya Sarangi, backend and distributed systems with applied ML" />

<div align="center">

<a href="https://www.linkedin.com/in/soumirya-sarangi"><img src="https://img.shields.io/badge/LinkedIn-0A3D62?style=for-the-badge&logo=linkedin&logoColor=00D9FF" alt="LinkedIn" /></a>
<a href="mailto:soumiryasarangi@gmail.com"><img src="https://img.shields.io/badge/Email-0A3D62?style=for-the-badge&logo=gmail&logoColor=00D9FF" alt="Email" /></a>
<a href="https://code-arena-eta-mauve.vercel.app"><img src="https://img.shields.io/badge/CodeArena%20live-0A3D62?style=for-the-badge&logo=vercel&logoColor=00D9FF" alt="CodeArena live" /></a>
<img src="https://img.shields.io/github/followers/SoumiryaSarangi?style=for-the-badge&logo=github&label=Followers&color=00D9FF&labelColor=0A3D62" alt="Followers" />

</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `01` &nbsp;·&nbsp; About

```yaml
name:      Soumirya Sarangi
studying:  B.Tech CSE @ Lovely Professional University · 2024 to 2028 · CGPA 8.4
focus:     backend and distributed systems, with applied ML
building:  a vertical search engine, a flash-sale ticketing system, a multi-region uptime monitor
looking:   SDE and AI/ML internships
```

I build backend systems and then measure them: load tests on the real deployment, failure drills, and models scored on data they never trained on. Every number below names the split or the setup it came from.

<img src="assets/divider.svg" width="100%" alt="" />

## `02` &nbsp;·&nbsp; Selected work

<table>
<tr>
<td width="50%" valign="top">

### <img src="assets/icons/judge.svg" width="21" align="top" /> &nbsp;CodeArena

<a href="https://code-arena-eta-mauve.vercel.app"><img src="https://img.shields.io/badge/live%20demo-00D9FF?style=flat-square&labelColor=0D1117" /></a>
<a href="https://github.com/SoumiryaSarangi/CodeArena"><img src="https://img.shields.io/badge/source-0A3D62?style=flat-square&logo=github&logoColor=00D9FF&labelColor=0D1117" /></a>
<img src="https://img.shields.io/badge/solo-0A3D62?style=flat-square&labelColor=0D1117" />

*A campus contest needs a judge that survives hostile code and a burst of submissions in the last minute.*

Online judge and contest platform. Code runs in isolate sandboxes on separate Azure VMs; jobs move through Redis Streams with leases; scoreboards update live over SSE.

**0.4 s** median verdict, **2.1 s** p95 on a 500-submission burst with two judge VMs · **28** sandbox attacks contained nightly · **6 of 6** failure drills pass on production

<sub>`Go` · `NestJS` · `Next.js` · `PostgreSQL` · `Redis` · `Terraform`</sub>

</td>
<td width="50%" valign="top">

### <img src="assets/icons/satellite.svg" width="21" align="top" /> &nbsp;UDGAM

<a href="https://github.com/SoumiryaSarangi/Udgam"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/badge/SIH%202026-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/team%20%C2%B7%20detection%20stage-0A3D62?style=flat-square&labelColor=0D1117" />

*Radar sees through cloud and darkness, but wind shadows and algae look almost the same as oil.*

Traces an oil spill in Sentinel-1 radar back to the ship that caused it. I built the detection stage: a CNN scene classifier that gates a U-Net, trained on 2,570 scenes.

**0.942** scene accuracy on the sealed 450-scene holdout · on validation, **0.757** pooled oil IoU and look-alike rejection **0.08 → 0.84** with the gate

<sub>`PyTorch` · `Python` · `OpenCV`</sub>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### <img src="assets/icons/verify.svg" width="21" align="top" /> &nbsp;TruthLens

<a href="https://github.com/SoumiryaSarangi/TruthLens"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/badge/EN%20%C2%B7%20HI%20%C2%B7%20PA-0A3D62?style=flat-square&labelColor=0D1117" />

*Hindi and Punjabi forwards often arrive typed in Latin letters. TruthLens treats that as the main case, not an edge case.*

Returns a verdict, its sources and a calibrated confidence for a forward, or refuses when it isn't sure. It checks for an existing fact-check first, then retrieves evidence.

Test ECE **0.039** · live verdict rule passed on **350** fresh claims, **100 of 106** answers right · the report shows it still trails an evidence-blind control on macro-F1

<sub>`PyTorch` · `Hugging Face Transformers` · `FastAPI`</sub>

</td>
<td width="50%" valign="top">

### <img src="assets/icons/storage.svg" width="21" align="top" /> &nbsp;Vault

<a href="https://github.com/SoumiryaSarangi/Vault"><img src="https://img.shields.io/badge/source-00D9FF?style=flat-square&logo=github&logoColor=0D1117&labelColor=0D1117" /></a>
<img src="https://img.shields.io/badge/20--hour%20hackathon-0A3D62?style=flat-square&labelColor=0D1117" />

*A clinic with four ordinary computers and no IT staff still can't afford to lose a file.*

Self-healing object store. I wrote the data plane: storage nodes, the gateway, Reed-Solomon erasure coding, repair, and LAN mode across four physical laptops.

Close a laptop's lid and Vault declares it failed in **8 s** (demo mode), then rebuilds its pieces on the others · **4 + 2** pieces per object at **1.5x** storage

<sub>`Python` · `FastAPI` · `SQLite`</sub>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### <img src="assets/icons/scan.svg" width="21" align="top" /> &nbsp;Marbl

<a href="https://marbl-app.onrender.com"><img src="https://img.shields.io/badge/live%20demo-00D9FF?style=flat-square&labelColor=0D1117" /></a>
<a href="https://github.com/SoumiryaSarangi/Meat-freshness-analyzer"><img src="https://img.shields.io/badge/source-0A3D62?style=flat-square&logo=github&logoColor=00D9FF&labelColor=0D1117" /></a>

*Freshness at the counter is judged by eye, by someone with no time to be careful.*

Grades a cut of meat from a phone photo and routes it by physical size, measured against a card in the frame.

**94.2%** on 831 validation images, from a random split, so an upper bound until the leakage audit

<sub>`PyTorch` · `OpenCV` · `FastAPI`</sub>

</td>
<td width="50%" valign="top">

### <img src="assets/icons/study.svg" width="21" align="top" /> &nbsp;SenseiAI

<a href="https://exam-prep-ai-ebon.vercel.app"><img src="https://img.shields.io/badge/live%20demo-00D9FF?style=flat-square&labelColor=0D1117" /></a>
<a href="https://github.com/SoumiryaSarangi/ExamPrep-AI"><img src="https://img.shields.io/badge/source-0A3D62?style=flat-square&logo=github&logoColor=00D9FF&labelColor=0D1117" /></a>

*Most study tools want an account and an API key before the first session.*

Turns lecture PDFs into notes, flashcards, quizzes and timed exams, with SM-2 spaced repetition and a tutor that answers only from your own uploads.

Local-first on IndexedDB · demo mode needs no key

<sub>`Next.js` · `TypeScript` · `React`</sub>

</td>
</tr>
</table>

<sub>Also: <a href="https://github.com/SoumiryaSarangi/DM-Rewind">DM Rewind</a> (jump to any date in an Instagram DM export, offline) · <a href="https://github.com/SoumiryaSarangi/OS-CA-Automated-Deadlock-Detection-Tool">Deadlock Detective</a> (matrix and wait-for-graph detection, visualised) · <a href="https://github.com/SoumiryaSarangi/Image-Classifier-for-fashion-mnist-hog-svm">Fashion-MNIST with HOG + SVM</a> (91.36% test) · <a href="https://github.com/SoumiryaSarangi/ml-educational-chatbot">an ML chatbot with no LLM</a></sub>

<img src="assets/divider.svg" width="100%" alt="" />

## `03` &nbsp;·&nbsp; How I work

<table>
<tr>
<td width="33%" valign="top">

**Estimate, then measure**

I write the capacity estimate down before the load test, so the result shows which assumption was wrong.

</td>
<td width="33%" valign="top">

**Name the split**

Thresholds are set on validation, the holdout is opened once, and every number says which one it came from.

</td>
<td width="33%" valign="top">

**Ship it**

A result in a notebook is not a deliverable. I take projects through to something deployed that other people can use.

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="" />

## `04` &nbsp;·&nbsp; Toolkit

<div align="center">

<sub>**LANGUAGES**</sub>

<img src="https://skillicons.dev/icons?i=go,ts,js,py,cpp,java&theme=dark" alt="Go, TypeScript, JavaScript, Python, C++, Java" />

<sub>**BACKEND & DATA**</sub>

<img src="https://skillicons.dev/icons?i=nestjs,fastapi,postgres,redis,sqlite&theme=dark" alt="NestJS, FastAPI, PostgreSQL, Redis, SQLite" />

<sub>**INFRASTRUCTURE**</sub>

<img src="https://skillicons.dev/icons?i=docker,terraform,azure,linux,githubactions&theme=dark" alt="Docker, Terraform, Azure, Linux, GitHub Actions" />

<sub>**FRONTEND**</sub>

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind&theme=dark" alt="Next.js, React, Tailwind CSS" />

<sub>**MACHINE LEARNING**</sub>

<img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv&theme=dark" alt="PyTorch, scikit-learn, OpenCV" />

<img src="https://img.shields.io/badge/Hugging%20Face%20Transformers-0A3D62?style=flat-square&logo=huggingface&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/OpenTelemetry-0A3D62?style=flat-square&logo=opentelemetry&logoColor=00D9FF&labelColor=0D1117" />
<img src="https://img.shields.io/badge/SQL-0A3D62?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/WebSockets-0A3D62?style=flat-square&labelColor=0D1117" />

</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `05` &nbsp;·&nbsp; Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=SoumiryaSarangi&hide_border=true&background=0D1117&stroke=1F6FEB&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF&sideLabels=C9D1D9&dates=8B949E&sideNums=C9D1D9&currStreakNum=FFFFFF" alt="Contribution streak" />

<br /><br />

<img src="assets/footer-pulse.svg" width="100%" alt="Animated failure drill: a storage node goes silent, is declared failed after 8 seconds, and Reed-Solomon rebuilds its shard on a surviving node" />

</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `06` &nbsp;·&nbsp; Contact

<div align="center">

**Open to SDE and AI/ML internships.**

<br />

<a href="https://www.linkedin.com/in/soumirya-sarangi"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A3D62?style=for-the-badge&logo=linkedin&logoColor=00D9FF" /></a>
<a href="mailto:soumiryasarangi@gmail.com"><img src="https://img.shields.io/badge/soumiryasarangi%40gmail.com-0A3D62?style=for-the-badge&logo=gmail&logoColor=00D9FF" /></a>

</div>

<img src="assets/divider.svg" width="100%" alt="" />

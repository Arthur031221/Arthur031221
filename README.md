<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0b1220,60:13306b,100:1d4ed8&text=Chi-Wei%20Lee&fontColor=ffffff&fontSize=44&fontAlignY=36&desc=NeuroAI%20%20%7C%20%203D%20Vision%20%20%7C%20%20GPU%20Computing&descSize=16&descAlignY=58&descColor=dbeafe" alt="Chi-Wei Lee" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=19&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=640&height=40&lines=Decoding+3D+space+from+human+brain+activity;Predictive+coding+and+Bayesian+inference;Fixing+correctness+bugs+in+GPU+and+scientific+software" alt="Research focus"/>

<a href="https://arthur031221.github.io/"><img src="https://img.shields.io/badge/Website-arthur031221.github.io-2563eb?style=flat-square" alt="Website"/></a>
<img src="https://img.shields.io/badge/NTHU-Physics%20%2B%20EECS%20(AI)-6e7781?style=flat-square" alt="NTHU Physics and EECS AI"/>
<img src="https://img.shields.io/badge/PhD%20applicant-2027-16a34a?style=flat-square" alt="PhD applicant 2027"/>
</div>

<p align="center">
  <a href="https://github.com/Arthur031221?tab=repositories">All repositories</a> ·
  <a href="https://github.com/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged">Merged pull requests</a>
</p>

I am **Chi-Wei Lee**, a Physics and EECS (AI track) double major at National Tsing Hua University. At the HMI Lab, I work on generative models that reconstruct 3D spatial structure from fMRI. I also build local developer tools and fix correctness bugs in scientific software. My interests span predictive coding, associative memory, and sampling-based inference.

### Selected work

| I build | I contribute upstream |
| --- | --- |
| [quantum-allosteric-scanner](https://github.com/Arthur031221/quantum-allosteric-scanner) explores protein allosteric sites from one unbound structure with continuous-time quantum walks. | [NVIDIA cuDF](https://github.com/NVIDIA/cudf): fixed [empty-string joins](https://github.com/NVIDIA/cudf/pull/24308) and [time-of-day loss](https://github.com/NVIDIA/cudf/pull/24310). |
| [agentleaks](https://github.com/Arthur031221/agentleaks) finds and redacts exposed API keys in local coding-agent histories. | [Stanza](https://github.com/stanfordnlp/stanza): repaired multi-word token reconstruction in [three merged PRs](https://github.com/stanfordnlp/stanza/pulls?q=is%3Apr+is%3Amerged+author%3AArthur031221). |
| [inference-visually](https://github.com/Arthur031221/inference-visually) makes LLM inference mechanics explorable in the browser. [Open the live demo](https://arthur031221.github.io/inference-visually/). | [Kornia](https://github.com/kornia/kornia): corrected [per-class recall in mean average precision](https://github.com/kornia/kornia/pull/5079). |

This selection connects research software, practical systems work, and fixes merged into established libraries. The links point to runnable projects or reviewable pull requests.

### More upstream fixes

- [Burn](https://github.com/tracel-ai/burn/pull/5892): clamped probabilities in label-smoothed cross entropy.
- [pymdp](https://github.com/infer-actively/pymdp/pull/442): fixed label-list indexing that selected diagonals instead of blocks.
- [braindecode](https://github.com/braindecode/braindecode/pull/1188): corrected Hilbert-frequency output length and Nyquist handling.

<div align="center">
  <img src="assets/workflow.svg" width="100%" alt="My approach: reproduce a failure, verify the fix, and contribute a reviewable patch." />
</div>

### Local-first tools

Twenty small tools, built and shipped end to end over one long session. Each ships as a complete v1 with tests, CI, and a README that states what it does not do.

**Security and supply chain**

| Project | What it does |
| --- | --- |
| [agentleaks](https://github.com/Arthur031221/agentleaks) | Finds, redacts, and blocks the API keys left in Claude Code, Codex, Cursor, Gemini CLI, Cline, and Aider history. Single binary. |
| [installwall](https://github.com/Arthur031221/installwall) | Checks direct npm, pip, gem, and cargo installs for typosquats, brand-new packages, and known malicious names. |
| [slopblock](https://github.com/Arthur031221/slopblock) | Adblock for AI slop. Blurs machine-written posts in your feeds on-device and shows why. Chrome and Firefox. |
| [docling-guard](https://github.com/Arthur031221/docling-guard) | Offline provenance validation and regression checks for Docling JSON. |

**Local LLM tooling**

| Project | What it does |
| --- | --- |
| [llm-doctor](https://github.com/Arthur031221/llm-doctor) | brew doctor for local LLMs. Dedupes Ollama, LM Studio, HF, and MLX weights, catches stale templates, probes agent endpoints. |
| [modelshift](https://github.com/Arthur031221/modelshift) | Finds model IDs in your repo that retire soon, replays real prompts on the replacement, opens the migration PR. |
| [gpuwho](https://github.com/Arthur031221/gpuwho) | Live per-process GPU use next to named local LLM processes on Apple Silicon, with optional Neural Engine power. |
| [mlxtrace](https://github.com/Arthur031221/mlxtrace) | MLX training step profiler with power and memory sampling and a standalone HTML timeline. |
| [ollama-verify](https://github.com/Arthur031221/ollama-verify) | Read-only integrity and storage audit for local Ollama models. |
| [inference-visually](https://github.com/Arthur031221/inference-visually) | Interactive explainers of the LLM serving stack. KV cache, paged attention, continuous batching, prefix caching, speculative decoding, measured on my own Mac. [Live demo](https://arthur031221.github.io/inference-visually/). |
| [shiftgear](https://github.com/Arthur031221/shiftgear) | Model and effort routing skill for Claude Code, Codex, Gemini CLI, Cursor, and OpenCode, with quota awareness. |
| [cliffhanger](https://github.com/Arthur031221/cliffhanger) | Stop hook and skill that keeps Claude Code from ending a turn with work still owed, and counts every early stop. |

**Apple Silicon media and documents**

| Project | What it does |
| --- | --- |
| [snipmd](https://github.com/Arthur031221/snipmd) | Hotkey, drag a box, get Markdown or LaTeX on your clipboard. Offline Mathpix Snip alternative for macOS with GLM-OCR. |
| [songforge](https://github.com/Arthur031221/songforge) | Local Suno-style song studio for Apple Silicon. Lyrics to full songs with vocals and covers through YuE2 on MLX. |
| [reelrecipe](https://github.com/Arthur031221/reelrecipe) | Turns local cooking videos into recipe cards with Whisper, GLM-OCR, Ollama, and Mealie JSON export. |
| [labexplain](https://github.com/Arthur031221/labexplain) | Offline lab report reader with printed-range priority, cited adult examples, and optional local OCR. |
| [receiptwise](https://github.com/Arthur031221/receiptwise) | Local receipt and warranty tracker with OCR, spend summaries, and printed deadline reminders. |
| [cardsmith](https://github.com/Arthur031221/cardsmith) | Offline flashcards from PDFs, slides, and notes. Generate locally, study with SM-2, export to Anki. |
| [papercompass](https://github.com/Arthur031221/papercompass) | Recommendations over my own arXiv library, offline after setup. Not another digest bot. |

**Automation**

| Project | What it does |
| --- | --- |
| [oss-launchbot](https://github.com/Arthur031221/oss-launchbot) | Policy-aware launch queue and guarded Reddit posting for open-source repositories. |

Research and creative side projects include [X-Ray](https://github.com/Arthur031221/X-Ray), [NSF-HDR](https://github.com/Arthur031221/NSF-HDR), and [MatrixQR](https://github.com/Arthur031221/MatrixQR).

I captained a team that placed **2nd of 609** in the 2025 NSF HDR ML Challenge anomaly-detection track and visited UCLA Samueli through the Taiwan Global Pathfinders program in 2026. [Research and experience](https://arthur031221.github.io/).

### A small contribution trace

The snake follows my public contribution graph. Its source image is refreshed by a scheduled GitHub Action, so the drawing changes with the graph rather than displaying a fixed activity claim.

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arthur031221/Arthur031221/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Arthur031221/Arthur031221/output/snake.svg" />
    <img src="https://raw.githubusercontent.com/Arthur031221/Arthur031221/output/snake.svg" width="100%" alt="Animated snake moving through Chi-Wei Lee's public GitHub contribution graph." />
  </picture>
</div>

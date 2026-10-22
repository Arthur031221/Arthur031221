<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,60:13306b,100:1d4ed8&fontColor=ffffff&height=200&section=header&text=Hello%2C%20I%27m%20Arthur!&fontSize=52&fontAlignY=36&desc=NeuroAI%20%20%7C%20%203D%20Vision%20%20%7C%20%20GPU%20Computing&descSize=18&descAlignY=58&descColor=dbeafe&animation=fadeIn" width="100%" alt="Hello, I'm Arthur!"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=700&color=58A6FF&center=true&vCenter=true&width=720&height=44&lines=Decoding+3D+space+from+the+human+brain;Contributor+to+85+open+source+projects;Predictive+coding,+Bayesian+inference,+GPU+computing" alt="What I do"/>

<img src="https://img.shields.io/badge/Focus-NeuroAI-1d4ed8?style=flat-square" alt="Focus: NeuroAI"/> <img src="https://img.shields.io/badge/Focus-3D%20vision-0f172a?style=flat-square" alt="Focus: 3D vision"/> <img src="https://img.shields.io/badge/Focus-GPU%20computing-0a66c2?style=flat-square" alt="Focus: GPU computing"/> <img src="https://img.shields.io/badge/Open%20source-fixes%20and%20tools-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Open source: fixes and tools"/>

</div>

### 👋 About me

I build generative decoders that reconstruct 3D spatial structure from fMRI, and I contribute fixes to GPU and scientific software.

My recent research asks how the brain represents and infers the space around us: recovering the layout of rooms from fMRI
and camera motion, letting predictive coding carry full posterior distributions instead of single point estimates, and
understanding when associative memory defines a well-behaved energy and why sampling-based predictive coding generalizes.

### 🌟 Featured contributions

<div align="center">
<table>
<tr><td width="26%" align="center" valign="middle">🦥&nbsp;<b><a href="https://github.com/unslothai/unsloth">unsloth</a></b><br><sub><sub>&nbsp;</sub></sub><br><img src="assets/badge-contrib-unslothai-unsloth-stars.svg?v=35d61b8f" height="20" alt="GitHub stars of unslothai/unsloth"/></td><td valign="middle"><b>Fixes padding mask handling so left-padded prompts produce consistent text with cached Llama and Qwen3 attention.</b><br>Added CPU regression tests for both decoders and ran the test command and Qwen2.5-0.5B-Instruct generation on an RTX 5090.&nbsp;<a href="https://github.com/unslothai/unsloth/pull/13256">PR&nbsp;→</a></td></tr>
<tr><td width="26%" align="center" valign="middle">🤗&nbsp;<b><a href="https://github.com/huggingface/sentence-transformers">sentence-transformers</a></b><br><sub><sub>&nbsp;</sub></sub><br><img src="assets/badge-contrib-huggingface-sentence-transformers-stars.svg?v=5a72bfc6" height="20" alt="GitHub stars of huggingface/sentence-transformers"/></td><td valign="middle"><b>MaxSim scoring now stays within the memory budget when a batch mixes long and short queries.</b><br>With 200 queries of 16 tokens, one query of 2,000 tokens and four documents of 1,000 tokens, extra peak CUDA memory fell from 869.7 MiB to 18.3 MiB with identical scores.&nbsp;<a href="https://github.com/huggingface/sentence-transformers/pull/4153">PR&nbsp;→</a></td></tr>
<tr><td width="26%" align="center" valign="middle">🌲&nbsp;<b><a href="https://github.com/dmlc/xgboost">xgboost</a></b><br><sub><sub>&nbsp;</sub></sub><br><img src="assets/badge-contrib-dmlc-xgboost-stars.svg?v=318e85ce" height="20" alt="GitHub stars of dmlc/xgboost"/></td><td valign="middle"><b>XGBoost now rejects masked NumPy inputs that could silently corrupt training data.</b><br>Tests confirm masked inputs raise a clear error, while arrays with no masked elements remain accepted.&nbsp;<a href="https://github.com/dmlc/xgboost/pull/12636">PR&nbsp;→</a></td></tr>
</table>
</div>

<details open>
<summary><h3>🚀 Featured projects</h3></summary>

<table>
<tr><td width="200" align="center" valign="middle"><a href="https://github.com/Arthur031221/Sunspill"><img src="https://raw.githubusercontent.com/Arthur031221/Sunspill/main/assets/logo.svg" width="64" alt=""/></a><br><b><a href="https://github.com/Arthur031221/Sunspill">Sunspill</a></b></td><td width="680" valign="top"><a href="https://github.com/Arthur031221/Sunspill"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/tip-Sunspill-dark.svg?v=e991dc1b"><img src="assets/tip-Sunspill-light.svg?v=371bccc9" width="680" alt="Set up your own room in a few minutes, then see where the sun lands on its floor, by the hour and the season."></picture></a><br><a href="https://github.com/Arthur031221/Sunspill/stargazers"><img src="assets/badge-Sunspill-stars.svg?v=cd4a3e3f" height="20" alt="16 stars"/></a> <a href="https://github.com/Arthur031221/Sunspill/actions/workflows/ci.yml"><img src="https://github.com/Arthur031221/Sunspill/actions/workflows/ci.yml/badge.svg?branch=main" height="20" alt="CI"/></a> <a href="https://github.com/Arthur031221/Sunspill/blob/main/LICENSE"><img src="assets/badge-Sunspill-license.svg?v=b3aa215e" height="20" alt="MIT license"/></a> <a href="https://github.com/Arthur031221/Sunspill/releases"><img src="assets/badge-Sunspill-release.svg?v=267a1bdb" height="20" alt="latest release v0.2.3"/></a> <a href="https://arthur031221.github.io/Sunspill/"><img src="assets/badge-Sunspill-demo.svg?v=993d2f8b" height="20" alt="live demo"/></a><details><summary>▶ Watch the demo</summary><br><a href="https://github.com/Arthur031221/Sunspill"><img src="https://raw.githubusercontent.com/Arthur031221/Sunspill/main/assets/demo.gif" width="100%" alt="Sunspill demo"/></a></details></td></tr>
<tr><td width="200" align="center" valign="middle"><a href="https://github.com/Arthur031221/Rumbleback"><img src="https://raw.githubusercontent.com/Arthur031221/Rumbleback/main/public/logo.svg" width="64" alt=""/></a><br><b><a href="https://github.com/Arthur031221/Rumbleback">Rumbleback</a></b></td><td width="680" valign="top"><a href="https://github.com/Arthur031221/Rumbleback"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/tip-Rumbleback-dark.svg?v=d4f64bc0"><img src="assets/tip-Rumbleback-light.svg?v=216498f6" width="680" alt="Replay any earthquake. See your seconds."></picture></a><br><a href="https://github.com/Arthur031221/Rumbleback/stargazers"><img src="assets/badge-Rumbleback-stars.svg?v=0f7ee0e6" height="20" alt="9 stars"/></a> <a href="https://github.com/Arthur031221/Rumbleback/actions/workflows/ci.yml"><img src="https://github.com/Arthur031221/Rumbleback/actions/workflows/ci.yml/badge.svg?branch=main" height="20" alt="CI"/></a> <a href="https://github.com/Arthur031221/Rumbleback/blob/main/LICENSE"><img src="assets/badge-Rumbleback-license.svg?v=b3aa215e" height="20" alt="MIT license"/></a> <a href="https://github.com/Arthur031221/Rumbleback/releases"><img src="assets/badge-Rumbleback-release.svg?v=1f872346" height="20" alt="latest release v0.4.1"/></a> <a href="https://arthur031221.github.io/Rumbleback/"><img src="assets/badge-Rumbleback-demo.svg?v=993d2f8b" height="20" alt="live demo"/></a><details><summary>▶ Watch the demo</summary><br><a href="https://github.com/Arthur031221/Rumbleback"><img src="https://raw.githubusercontent.com/Arthur031221/Rumbleback/main/assets/demo.gif" width="100%" alt="Rumbleback demo"/></a></details></td></tr>
<tr><td width="200" align="center" valign="middle"><a href="https://github.com/Arthur031221/DoclingGuard"><img src="https://raw.githubusercontent.com/Arthur031221/DoclingGuard/main/assets/logo.svg" width="64" alt=""/></a><br><b><a href="https://github.com/Arthur031221/DoclingGuard">DoclingGuard</a></b></td><td width="680" valign="top"><a href="https://github.com/Arthur031221/DoclingGuard"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/tip-DoclingGuard-dark.svg?v=d3268bf9"><img src="assets/tip-DoclingGuard-light.svg?v=8ded2ed5" width="680" alt="Check Docling JSON exports for broken source spans and extraction loss before they reach a search index."></picture></a><br><a href="https://github.com/Arthur031221/DoclingGuard/stargazers"><img src="assets/badge-DoclingGuard-stars.svg?v=72467c4d" height="20" alt="2 stars"/></a> <a href="https://github.com/Arthur031221/DoclingGuard/actions/workflows/ci.yml"><img src="https://github.com/Arthur031221/DoclingGuard/actions/workflows/ci.yml/badge.svg?branch=main" height="20" alt="CI"/></a> <a href="https://github.com/Arthur031221/DoclingGuard/blob/main/LICENSE"><img src="assets/badge-DoclingGuard-license.svg?v=b3aa215e" height="20" alt="MIT license"/></a> <a href="https://github.com/Arthur031221/DoclingGuard/releases"><img src="assets/badge-DoclingGuard-release.svg?v=f2049d83" height="20" alt="latest release v0.2.0"/></a><details><summary>▶ Watch the demo</summary><br><a href="https://github.com/Arthur031221/DoclingGuard"><img src="https://raw.githubusercontent.com/Arthur031221/docling-guard/main/demo/demo.gif" width="100%" alt="DoclingGuard demo"/></a></details></td></tr>
</table>

</details>


### 📊 Open source at a glance

<p align="center"><a href="https://github.com/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/oss-dark.svg"><img src="assets/oss-light.svg" width="560" alt="Open source contributions"></picture></a></p>

<p align="center"><a href="https://www.holopin.io/@arthur031221"><img src="https://assets.holopin.io/eyJidWNrZXQiOiJob2xvcGluLWFzc2V0cyIsImtleSI6ImFzc2V0cy9jbHJxaGU4aGMzNjU4MGZqd3dsZHgxaG93IiwiZWRpdHMiOnsicm90YXRlIjpudWxsfX0=" height="120" alt="Dapr Runtime Contributor badge, issued by the Dapr maintainers for dapr/dapr#10776"/></a><br><sub>Dapr Runtime Contributor, issued by the Dapr maintainers for <a href="https://github.com/dapr/dapr/pull/10776">dapr/dapr#10776</a></sub></p>

<details>
<summary><b>All 0 projects with my merged pull requests</b></summary>
<br>



</details>

<details>
<summary><b>All 25 personal projects</b></summary>
<br>

<details open>
<summary>&nbsp;&nbsp;🤖 Coding agents and AI tooling <sub>(6)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [Cliffhanger](https://github.com/Arthur031221/Cliffhanger) | Stop hook and skill that keeps Claude Code from ending the turn with work still owed, and  | 1 |
| [AgentLeaks](https://github.com/Arthur031221/AgentLeaks) | Find, redact and block the API keys in Claude Code, Codex, Cursor, Gemini CLI, Cline and A | 1 |
| [ToolCallCheck](https://github.com/Arthur031221/ToolCallCheck) | Check nested tool arguments, streamed calls and the result handoff on a chat endpoint. | 1 |
| [ModelShift](https://github.com/Arthur031221/ModelShift) | Find model IDs in your repo that retire soon, replay real prompts on the replacement, and  | 0 |
| [Graticule](https://github.com/Arthur031221/Graticule) | A cartography skill for coding agents. It checks a map against 25 rules (raw counts, Merca | 0 |
| [Token-Beggar](https://github.com/Arthur031221/Token-Beggar) | A coding agent skill that routes each task to the cheapest model and effort that keeps the | 0 |

</details>

<details open>
<summary>&nbsp;&nbsp;🧠 Local LLMs and GPUs <sub>(2)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [Rumbleback](https://github.com/Arthur031221/Rumbleback) | Replay any past earthquake in the browser: P and S wavefronts from the iasp91 model, real  | 9 |
| [LLMDoctor](https://github.com/Arthur031221/LLMDoctor) | brew doctor for local LLMs: dedupe Ollama, LM Studio, HF and MLX weights, catch stale temp | 1 |

</details>

<details open>
<summary>&nbsp;&nbsp;📚 Documents, study and research <sub>(5)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [DoclingGuard](https://github.com/Arthur031221/DoclingGuard) | Offline provenance validation and regression checks for Docling JSON | 2 |
| [SnipMD](https://github.com/Arthur031221/SnipMD) | Hotkey, drag a box, get Markdown or LaTeX on your clipboard. Offline Mathpix Snip alternat | 2 |
| [Cardsmith](https://github.com/Arthur031221/Cardsmith) | Offline flashcards from PDFs, slides, and notes. Generate locally, study with SM-2, export | 1 |
| [PaperCompass](https://github.com/Arthur031221/PaperCompass) | Recommendations over your own arXiv library, offline after setup. Not another digest bot. | 0 |
| [Darnleaf](https://github.com/Arthur031221/Darnleaf) | Repair a scanned PDF with fresh rescans. Match shuffled rescans to damaged pages, review t | 0 |

</details>

<details open>
<summary>&nbsp;&nbsp;🌐 Web and JavaScript debugging <sub>(6)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [Sunspill](https://github.com/Arthur031221/Sunspill) | Plan a room on an OpenStreetMap building and see where sunlight falls through the day and  | 16 |
| [ChitWeave](https://github.com/Arthur031221/ChitWeave) | Turn a two-person LINE chat export into a woven picture of when you talk, one row a day an | 1 |
| [Deadpan](https://github.com/Arthur031221/Deadpan) | Passport photos that pass. A live camera guide in your browser checks head size against th | 1 |
| [OohAlive](https://github.com/Arthur031221/OohAlive) | Draw an arrow on a photo and it flows that way. Download the loop as a GIF. Free, in your  | 0 |
| [GlyphSprout](https://github.com/Arthur031221/GlyphSprout) | A browser workshop for turning handwriting pages into editable Latin, Han and kana font su | 0 |
| [Ridgereel](https://github.com/Arthur031221/Ridgereel) | Turn a GPX, TCX or FIT file into a 3D terrain flyover video in your browser, with nothing  | 0 |

</details>

<details open>
<summary>&nbsp;&nbsp;⚙️ Git, CI and build <sub>(2)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [WorktreePortCheck](https://github.com/Arthur031221/WorktreePortCheck) | Check whether a port listener runs from the Git worktree you are testing | 0 |
| [GHARerunLedger](https://github.com/Arthur031221/GHARerunLedger) | Inspect GitHub Actions rerun attempts and replay saved metadata offline. | 0 |

</details>

<details open>
<summary>&nbsp;&nbsp;🧩 Other tools <sub>(4)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [Unwedged](https://github.com/Arthur031221/Unwedged) | Plan and replay furniture turning routes in a measured floor plan. | 2 |
| [Reachbloom](https://github.com/Arthur031221/Reachbloom) | Explore dated transit timetables, reachable stops and two origins on a map | 0 |
| [Cleartake](https://github.com/Arthur031221/Cleartake) | Clean noisy speech recordings locally, hit a loudness target and check that no word change | 0 |
| [SeatReason](https://github.com/Arthur031221/SeatReason) | A classroom seating planner that names the few rules that clash and checks a repair before | 0 |

</details>

</details>

<details open>
<summary><b>Stars over the last 30 days</b></summary>
<br>
<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/stars-dark.svg?v=03c75cfa"><img src="assets/stars-light.svg?v=05d132c4" width="720" alt="Hand-drawn chart of stars across my projects over the last 30 days"></picture></p>

</details>

### 🛠️ Toolbox

<p align="center"><img src="https://skillicons.dev/icons?i=python,cpp,c,rust,go,julia,ts,js,bash,fortran,haskell,latex,pytorch,sklearn,opencv,threejs,linux,git,github,githubactions,nodejs,vscode,md&perline=23" width="100%" alt="python, cpp, c, rust, go, julia, ts, js, bash, fortran, haskell, latex, pytorch, sklearn, opencv, threejs, linux, git, github, githubactions, nodejs, vscode, md"/></p>
<p align="center"><img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/> <img src="https://img.shields.io/badge/JAX-A8B9CC?style=flat-square" alt="JAX"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/> <img src="https://img.shields.io/badge/Hugging%20Face-FFB000?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/> <img src="https://img.shields.io/badge/MNE--Python-367BB6?style=flat-square" alt="MNE-Python"/> <img src="https://img.shields.io/badge/nilearn-0F6E8C?style=flat-square" alt="nilearn"/> <img src="https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white" alt="WebGL"/> <img src="https://img.shields.io/badge/MPI-2563EB?style=flat-square" alt="MPI"/></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arthur031221/Arthur031221/output/snake-dark.svg">
  <img src="https://raw.githubusercontent.com/Arthur031221/Arthur031221/output/snake.svg" alt="Contribution graph"/>
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,60:13306b,100:1d4ed8&fontColor=ffffff&height=100&section=footer" width="100%" alt=""/>

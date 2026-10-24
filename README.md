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
<tr><td width="26%" align="center" valign="middle">🦥&nbsp;<b><a href="https://github.com/unslothai/unsloth">unsloth</a></b><br><sub><sub>&nbsp;</sub></sub><br><img src="assets/badge-contrib-unslothai-unsloth-stars.svg?v=04eb3ee0" height="20" alt="GitHub stars of unslothai/unsloth"/></td><td valign="middle"><b>Fixes padding mask handling so left-padded prompts produce consistent text with cached Llama and Qwen3 attention.</b><br>Added CPU regression tests for both decoders and ran the test command and Qwen2.5-0.5B-Instruct generation on an RTX 5090.&nbsp;<a href="https://github.com/unslothai/unsloth/pull/13256">PR&nbsp;→</a></td></tr>
<tr><td width="26%" align="center" valign="middle">🤗&nbsp;<b><a href="https://github.com/huggingface/sentence-transformers">sentence-transformers</a></b><br><sub><sub>&nbsp;</sub></sub><br><img src="assets/badge-contrib-huggingface-sentence-transformers-stars.svg?v=674135f1" height="20" alt="GitHub stars of huggingface/sentence-transformers"/></td><td valign="middle"><b>MaxSim scoring now stays within the memory budget when a batch mixes long and short queries.</b><br>With 200 queries of 16 tokens, one query of 2,000 tokens and four documents of 1,000 tokens, extra peak CUDA memory fell from 869.7 MiB to 18.3 MiB with identical scores.&nbsp;<a href="https://github.com/huggingface/sentence-transformers/pull/4153">PR&nbsp;→</a></td></tr>
<tr><td width="26%" align="center" valign="middle">🌲&nbsp;<b><a href="https://github.com/dmlc/xgboost">xgboost</a></b><br><sub><sub>&nbsp;</sub></sub><br><img src="assets/badge-contrib-dmlc-xgboost-stars.svg?v=5e23ab68" height="20" alt="GitHub stars of dmlc/xgboost"/></td><td valign="middle"><b>XGBoost now rejects masked NumPy inputs that could silently corrupt training data.</b><br>Tests confirm masked inputs raise a clear error, while arrays with no masked elements remain accepted.&nbsp;<a href="https://github.com/dmlc/xgboost/pull/12636">PR&nbsp;→</a></td></tr>
</table>
</div>

<details open>
<summary><h3>🚀 Featured projects</h3></summary>

<table>
<tr><td width="200" align="center" valign="middle"><a href="https://github.com/Arthur031221/Sunspill"><img src="https://raw.githubusercontent.com/Arthur031221/Sunspill/main/assets/logo.svg" width="64" alt=""/></a><br><b><a href="https://github.com/Arthur031221/Sunspill">Sunspill</a></b></td><td width="680" valign="top"><a href="https://github.com/Arthur031221/Sunspill"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/tip-Sunspill-dark.svg?v=e991dc1b"><img src="assets/tip-Sunspill-light.svg?v=371bccc9" width="680" alt="Set up your own room in a few minutes, then see where the sun lands on its floor, by the hour and the season."></picture></a><br><a href="https://github.com/Arthur031221/Sunspill/stargazers"><img src="assets/badge-Sunspill-stars.svg?v=1c7696d6" height="20" alt="17 stars"/></a> <a href="https://github.com/Arthur031221/Sunspill/actions/workflows/ci.yml"><img src="https://github.com/Arthur031221/Sunspill/actions/workflows/ci.yml/badge.svg?branch=main" height="20" alt="CI"/></a> <a href="https://github.com/Arthur031221/Sunspill/blob/main/LICENSE"><img src="assets/badge-Sunspill-license.svg?v=b3aa215e" height="20" alt="MIT license"/></a> <a href="https://github.com/Arthur031221/Sunspill/releases"><img src="assets/badge-Sunspill-release.svg?v=267a1bdb" height="20" alt="latest release v0.2.3"/></a> <a href="https://arthur031221.github.io/Sunspill/"><img src="assets/badge-Sunspill-demo.svg?v=993d2f8b" height="20" alt="live demo"/></a><details><summary>▶ Watch the demo</summary><br><a href="https://github.com/Arthur031221/Sunspill"><img src="https://raw.githubusercontent.com/Arthur031221/Sunspill/main/assets/demo.gif" width="100%" alt="Sunspill demo"/></a></details></td></tr>
<tr><td width="200" align="center" valign="middle"><a href="https://github.com/Arthur031221/Rumbleback"><img src="https://raw.githubusercontent.com/Arthur031221/Rumbleback/main/public/logo.svg" width="64" alt=""/></a><br><b><a href="https://github.com/Arthur031221/Rumbleback">Rumbleback</a></b></td><td width="680" valign="top"><a href="https://github.com/Arthur031221/Rumbleback"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/tip-Rumbleback-dark.svg?v=d4f64bc0"><img src="assets/tip-Rumbleback-light.svg?v=216498f6" width="680" alt="Replay any earthquake. See your seconds."></picture></a><br><a href="https://github.com/Arthur031221/Rumbleback/stargazers"><img src="assets/badge-Rumbleback-stars.svg?v=3501a038" height="20" alt="10 stars"/></a> <a href="https://github.com/Arthur031221/Rumbleback/actions/workflows/ci.yml"><img src="https://github.com/Arthur031221/Rumbleback/actions/workflows/ci.yml/badge.svg?branch=main" height="20" alt="CI"/></a> <a href="https://github.com/Arthur031221/Rumbleback/blob/main/LICENSE"><img src="assets/badge-Rumbleback-license.svg?v=b3aa215e" height="20" alt="MIT license"/></a> <a href="https://github.com/Arthur031221/Rumbleback/releases"><img src="assets/badge-Rumbleback-release.svg?v=1f872346" height="20" alt="latest release v0.4.1"/></a> <a href="https://arthur031221.github.io/Rumbleback/"><img src="assets/badge-Rumbleback-demo.svg?v=993d2f8b" height="20" alt="live demo"/></a><details><summary>▶ Watch the demo</summary><br><a href="https://github.com/Arthur031221/Rumbleback"><img src="https://raw.githubusercontent.com/Arthur031221/Rumbleback/main/assets/demo.gif" width="100%" alt="Rumbleback demo"/></a></details></td></tr>
<tr><td width="200" align="center" valign="middle"><a href="https://github.com/Arthur031221/DoclingGuard"><img src="https://raw.githubusercontent.com/Arthur031221/DoclingGuard/main/assets/logo.svg" width="64" alt=""/></a><br><b><a href="https://github.com/Arthur031221/DoclingGuard">DoclingGuard</a></b></td><td width="680" valign="top"><a href="https://github.com/Arthur031221/DoclingGuard"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/tip-DoclingGuard-dark.svg?v=d3268bf9"><img src="assets/tip-DoclingGuard-light.svg?v=8ded2ed5" width="680" alt="Check Docling JSON exports for broken source spans and extraction loss before they reach a search index."></picture></a><br><a href="https://github.com/Arthur031221/DoclingGuard/stargazers"><img src="assets/badge-DoclingGuard-stars.svg?v=dfb94e50" height="20" alt="3 stars"/></a> <a href="https://github.com/Arthur031221/DoclingGuard/actions/workflows/ci.yml"><img src="https://github.com/Arthur031221/DoclingGuard/actions/workflows/ci.yml/badge.svg?branch=main" height="20" alt="CI"/></a> <a href="https://github.com/Arthur031221/DoclingGuard/blob/main/LICENSE"><img src="assets/badge-DoclingGuard-license.svg?v=b3aa215e" height="20" alt="MIT license"/></a> <a href="https://github.com/Arthur031221/DoclingGuard/releases"><img src="assets/badge-DoclingGuard-release.svg?v=f2049d83" height="20" alt="latest release v0.2.0"/></a><details><summary>▶ Watch the demo</summary><br><a href="https://github.com/Arthur031221/DoclingGuard"><img src="https://raw.githubusercontent.com/Arthur031221/docling-guard/main/demo/demo.gif" width="100%" alt="DoclingGuard demo"/></a></details></td></tr>
</table>

</details>


### 📊 Open source at a glance

<p align="center"><a href="https://github.com/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/oss-dark.svg"><img src="assets/oss-light.svg" width="560" alt="Open source contributions"></picture></a></p>

<p align="center"><a href="https://www.holopin.io/@arthur031221"><img src="https://assets.holopin.io/eyJidWNrZXQiOiJob2xvcGluLWFzc2V0cyIsImtleSI6ImFzc2V0cy9jbHJxaGU4aGMzNjU4MGZqd3dsZHgxaG93IiwiZWRpdHMiOnsicm90YXRlIjpudWxsfX0=" height="120" alt="Dapr Runtime Contributor badge, issued by the Dapr maintainers for dapr/dapr#10776"/></a><br><sub>Dapr Runtime Contributor, issued by the Dapr maintainers for <a href="https://github.com/dapr/dapr/pull/10776">dapr/dapr#10776</a></sub></p>

<details>
<summary><b>All 125 projects with my merged pull requests</b></summary>
<br>

<details open>
<summary>&nbsp;&nbsp;🤖 AI and machine learning <sub>(16)</sub></summary>
<br>

[100-Days-Of-ML-Code](https://github.com/MLEveryday/100-Days-Of-ML-Code/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [awesome-YuE](https://github.com/RevolutionLA/awesome-YuE/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [awesome-mlx](https://github.com/antranapp/awesome-mlx/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [DocsGPT](https://github.com/arc53/DocsGPT/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [agent-device](https://github.com/callstack/agent-device/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [xgboost](https://github.com/dmlc/xgboost/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [gufo](https://github.com/gufo-org/gufo/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [pytorch-image-models](https://github.com/huggingface/pytorch-image-models/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [hypit](https://github.com/hypit-ai/hypit/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [kornia](https://github.com/kornia/kornia/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [lancedb](https://github.com/lancedb/lancedb/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [FunASR](https://github.com/modelscope/FunASR/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [openchamber](https://github.com/openchamber/openchamber/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [recommenders](https://github.com/recommenders-team/recommenders/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [stanza](https://github.com/stanfordnlp/stanza/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [burn](https://github.com/tracel-ai/burn/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;🧠 Neuroscience and brain-computer interfaces <sub>(4)</sub></summary>
<br>

[moabb](https://github.com/NeuroTechX/moabb/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [braindecode](https://github.com/braindecode/braindecode/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [pymdp](https://github.com/infer-actively/pymdp/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [psychopy](https://github.com/psychopy/psychopy/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;🧊 3D, vision and graphics <sub>(15)</sub></summary>
<br>

[Babylon.js](https://github.com/BabylonJS/Babylon.js/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [3d-tiles](https://github.com/CesiumGS/3d-tiles/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [CloudCompare](https://github.com/CloudCompare/CloudCompare/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [ImageMagick](https://github.com/ImageMagick/ImageMagick/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [K3D-jupyter](https://github.com/K3D-tools/K3D-jupyter/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [orillusion](https://github.com/Orillusion/orillusion/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [AliceVision](https://github.com/alicevision/AliceVision/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Meshroom](https://github.com/alicevision/Meshroom/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [colmap](https://github.com/colmap/colmap/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [model-viewer](https://github.com/google/model-viewer/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [openFrameworks](https://github.com/openframeworks/openFrameworks/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [splat-transform](https://github.com/playcanvas/splat-transform/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [supersplat](https://github.com/playcanvas/supersplat/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [postprocessing](https://github.com/pmndrs/postprocessing/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Pillow](https://github.com/python-pillow/Pillow/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;⚡ GPU, HPC and scientific computing <sub>(14)</sub></summary>
<br>

[Symbolics.jl](https://github.com/JuliaSymbolics/Symbolics.jl/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [MultiQC](https://github.com/MultiQC/MultiQC/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [MatX](https://github.com/NVIDIA/MatX/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [cccl](https://github.com/NVIDIA/cccl/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [cudf](https://github.com/NVIDIA/cudf/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [OpenBLAS](https://github.com/OpenMathLib/OpenBLAS/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [cp2k](https://github.com/cp2k/cp2k/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [highway](https://github.com/google/highway/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [mpi4py](https://github.com/mpi4py/mpi4py/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [nextflow](https://github.com/nextflow-io/nextflow/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [ohpc](https://github.com/openhpc/ohpc/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [openmc](https://github.com/openmc-dev/openmc/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [numpyro](https://github.com/pyro-ppl/numpyro/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [oneTBB](https://github.com/uxlfoundation/oneTBB/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;🔌 Hardware, robotics and firmware <sub>(5)</sub></summary>
<br>

[drake](https://github.com/RobotLocomotion/drake/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [canboatjs](https://github.com/canboat/canboatjs/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [webots](https://github.com/cyberbotics/webots/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [rtabmap](https://github.com/introlab/rtabmap/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [allwpilib](https://github.com/wpilibsuite/allwpilib/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;🎵 Audio and signal processing <sub>(2)</sub></summary>
<br>

[faust](https://github.com/grame-cncm/faust/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [kfr](https://github.com/kfrlib/kfr/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;🛠️ Languages, compilers and developer tools <sub>(7)</sub></summary>
<br>

[futhark](https://github.com/diku-dk/futhark/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [luceneutil](https://github.com/mikemccand/luceneutil/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Odin](https://github.com/odin-lang/Odin/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [smlnj](https://github.com/smlnj/smlnj/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [testng](https://github.com/testng-team/testng/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [v](https://github.com/vlang/v/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [nox](https://github.com/wntrblm/nox/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;🖥️ Apps and productivity <sub>(3)</sub></summary>
<br>

[naps2](https://github.com/cyanfish/naps2/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [OSS-DocumentScanner](https://github.com/ossappscollective/OSS-DocumentScanner/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [zotero-better-bibtex](https://github.com/retorquere/zotero-better-bibtex/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

<details open>
<summary>&nbsp;&nbsp;✨ Other <sub>(59)</sub></summary>
<br>

[ANTs](https://github.com/ANTsX/ANTs/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [ATSynEdit](https://github.com/Alexey-T/ATSynEdit/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [UniGetUI](https://github.com/Devolutions/UniGetUI/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [DroidDeck](https://github.com/Droid-Deck/DroidDeck/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [evox](https://github.com/EMI-Group/evox/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [EllesmereUI](https://github.com/EllesmereGaming/EllesmereUI/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [elmerfem](https://github.com/ElmerCSC/elmerfem/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [saw-script](https://github.com/GaloisInc/saw-script/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Indy](https://github.com/IndySockets/Indy/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [MaaAssistantArknights](https://github.com/MaaAssistantArknights/MaaAssistantArknights/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [DALI](https://github.com/NVIDIA/DALI/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [kaolin](https://github.com/NVIDIAGameWorks/kaolin/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Sana](https://github.com/NVlabs/Sana/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Slicer](https://github.com/Slicer/Slicer/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [actix-web](https://github.com/actix/actix-web/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [apexcharts.js](https://github.com/apexcharts/apexcharts.js/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [apptainer](https://github.com/apptainer/apptainer/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [assistant-ui](https://github.com/assistant-ui/assistant-ui/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [llrt](https://github.com/awslabs/llrt/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [mediamtx](https://github.com/bluenviron/mediamtx/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [brian2](https://github.com/brian-team/brian2/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [cdk](https://github.com/cashubtc/cdk/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [vinext](https://github.com/cloudflare/vinext/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [workers-sdk](https://github.com/cloudflare/workers-sdk/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [coregex](https://github.com/coregx/coregex/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [doodle](https://github.com/creativescala/doodle/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [dapr](https://github.com/dapr/dapr/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [emqx](https://github.com/emqx/emqx/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [openarm](https://github.com/enactic/openarm/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [fairlearn](https://github.com/fairlearn/fairlearn/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [fyne](https://github.com/fyne-io/fyne/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [engine](https://github.com/galacean/engine/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [gyroflow](https://github.com/gyroflow/gyroflow/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [sentence-transformers](https://github.com/huggingface/sentence-transformers/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [joern](https://github.com/joernio/joern/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [zig-esp-idf-sample](https://github.com/kassane/zig-esp-idf-sample/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [kepler.gl](https://github.com/keplergl/kepler.gl/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Maestro](https://github.com/mobile-dev-inc/Maestro/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [parsons](https://github.com/move-coop/parsons/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [Nim](https://github.com/nim-lang/Nim/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [nullclaw](https://github.com/nullclaw/nullclaw/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [openvino](https://github.com/openvinotoolkit/openvino/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [node-redis](https://github.com/redis/node-redis/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [remotion](https://github.com/remotion-dev/remotion/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [scikit-bio](https://github.com/scikit-bio/scikit-bio/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [sequelize](https://github.com/sequelize/sequelize/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [DiPlay](https://github.com/shihabal3amri/DiPlay/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [sql.js](https://github.com/sql-js/sql.js/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [taskflow](https://github.com/taskflow/taskflow/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [trpc](https://github.com/trpc/trpc/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [uccl](https://github.com/uccl-project/uccl/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [unsloth](https://github.com/unslothai/unsloth/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [USearch](https://github.com/unum-cloud/USearch/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [hls.js](https://github.com/video-dev/hls.js/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [xsimd](https://github.com/xtensor-stack/xsimd/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [node-red-contrib-home-assistant-websocket](https://github.com/zachowj/node-red-contrib-home-assistant-websocket/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [zml](https://github.com/zml/zml/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [zwasm](https://github.com/zwasm/zwasm/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged), [zxing](https://github.com/zxing/zxing/pulls?q=is%3Apr+author%3AArthur031221+is%3Amerged)

</details>

</details>

<details>
<summary><b>All 26 personal projects</b></summary>
<br>

<details open>
<summary>&nbsp;&nbsp;🤖 Coding agents and AI tooling <sub>(6)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [Cliffhanger](https://github.com/Arthur031221/Cliffhanger) | Stop hook and skill that keeps Claude Code from ending the turn with work still owed, and  | 1 |
| [AgentLeaks](https://github.com/Arthur031221/AgentLeaks) | Find, redact and block the API keys in Claude Code, Codex, Cursor, Gemini CLI, Cline and A | 1 |
| [ToolCallCheck](https://github.com/Arthur031221/ToolCallCheck) | Check nested tool arguments, streamed calls and the result handoff on a chat endpoint. | 1 |
| [Token-Beggar](https://github.com/Arthur031221/Token-Beggar) | A coding agent skill that routes each task to the cheapest model and effort that keeps the | 1 |
| [ModelShift](https://github.com/Arthur031221/ModelShift) | Find model IDs in your repo that retire soon, replay real prompts on the replacement, and  | 0 |
| [Graticule](https://github.com/Arthur031221/Graticule) | A cartography skill for coding agents. It checks a map against 25 rules (raw counts, Merca | 0 |

</details>

<details open>
<summary>&nbsp;&nbsp;🧠 Local LLMs and GPUs <sub>(2)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [Rumbleback](https://github.com/Arthur031221/Rumbleback) | Replay any past earthquake in the browser: P and S wavefronts from the iasp91 model, real  | 10 |
| [LLMDoctor](https://github.com/Arthur031221/LLMDoctor) | brew doctor for local LLMs: dedupe Ollama, LM Studio, HF and MLX weights, catch stale temp | 1 |

</details>

<details open>
<summary>&nbsp;&nbsp;📚 Documents, study and research <sub>(5)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [DoclingGuard](https://github.com/Arthur031221/DoclingGuard) | Offline provenance validation and regression checks for Docling JSON | 3 |
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
| [Sunspill](https://github.com/Arthur031221/Sunspill) | Plan a room on an OpenStreetMap building and see where sunlight falls through the day and  | 17 |
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
<summary>&nbsp;&nbsp;🧩 Other tools <sub>(5)</sub></summary>
<br>

| Project | What it does | Stars |
|:--|:--|--:|
| [Unwedged](https://github.com/Arthur031221/Unwedged) | Plan and replay furniture turning routes in a measured floor plan. | 3 |
| [Reachbloom](https://github.com/Arthur031221/Reachbloom) | Explore dated transit timetables, reachable stops and two origins on a map | 0 |
| [Cleartake](https://github.com/Arthur031221/Cleartake) | Clean noisy speech recordings locally, hit a loudness target and check that no word change | 0 |
| [SeatReason](https://github.com/Arthur031221/SeatReason) | A classroom seating planner that names the few rules that clash and checks a repair before | 0 |
| [AiSniff](https://github.com/Arthur031221/AiSniff) | Paste English or Traditional Chinese text and see which phrases read like AI wrote them, w | 0 |

</details>

</details>

<details open>
<summary><b>Stars over the last 30 days</b></summary>
<br>
<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/stars-dark.svg?v=85011a63"><img src="assets/stars-light.svg?v=03ab3233" width="720" alt="Hand-drawn chart of stars across my projects over the last 30 days"></picture></p>

</details>

### 🛠️ Toolbox

<p align="center"><img src="https://skillicons.dev/icons?i=python,cpp,c,rust,go,julia,ts,js,bash,fortran,haskell,latex,pytorch,sklearn,opencv,threejs,linux,git,github,githubactions,nodejs,vscode,md&perline=23" width="100%" alt="python, cpp, c, rust, go, julia, ts, js, bash, fortran, haskell, latex, pytorch, sklearn, opencv, threejs, linux, git, github, githubactions, nodejs, vscode, md"/></p>
<p align="center"><img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA"/> <img src="https://img.shields.io/badge/JAX-A8B9CC?style=flat-square" alt="JAX"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/> <img src="https://img.shields.io/badge/Hugging%20Face-FFB000?style=flat-square&logo=huggingface&logoColor=white" alt="Hugging Face"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/> <img src="https://img.shields.io/badge/MNE--Python-367BB6?style=flat-square" alt="MNE-Python"/> <img src="https://img.shields.io/badge/nilearn-0F6E8C?style=flat-square" alt="nilearn"/> <img src="https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white" alt="WebGL"/> <img src="https://img.shields.io/badge/MPI-2563EB?style=flat-square" alt="MPI"/></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arthur031221/Arthur031221/output/snake-dark.svg">
  <img src="https://raw.githubusercontent.com/Arthur031221/Arthur031221/output/snake.svg" alt="Contribution graph"/>
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,60:13306b,100:1d4ed8&fontColor=ffffff&height=100&section=footer" width="100%" alt=""/>

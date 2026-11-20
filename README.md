# Arthur

I work on 3D and 4D reconstruction from measurements that are sparse or badly timed, like single-photon counts, rolling-shutter video and fMRI.

I also send fixes to open source libraries I depend on. In [unsloth](https://github.com/unslothai/unsloth/pull/13256), left-padded prompts now generate the same text with cached Llama and Qwen3 attention. [xgboost](https://github.com/dmlc/xgboost/pull/12636) now refuses NumPy masked arrays, which used to slip through and could silently corrupt training data. MaxSim scoring in [sentence-transformers](https://github.com/huggingface/sentence-transformers/pull/4153) stays within its memory budget when a batch mixes long and short queries.

Tools I wrote and maintain:

- [Sunspill](https://github.com/Arthur031221/Sunspill) shows where sunlight lands in a room, by hour and season
- [Rumbleback](https://github.com/Arthur031221/Rumbleback) replays past earthquakes in the browser
- [Token-Beggar](https://github.com/Arthur031221/Token-Beggar) routes each coding agent task to the cheapest model
- [SnipMD](https://github.com/Arthur031221/SnipMD) turns a screen region into Markdown or LaTeX, offline
- [Unwedged](https://github.com/Arthur031221/Unwedged) plans how to turn furniture through a measured floor plan
- [DoclingGuard](https://github.com/Arthur031221/DoclingGuard) checks Docling JSON exports before they reach a search index

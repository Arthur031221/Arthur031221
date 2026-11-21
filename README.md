# Arthur

I am an undergraduate at National Tsing Hua University in Taiwan, double majoring in Physics and in Electrical Engineering and Computer Science. Most of my research is in computer vision, mainly 3D and 4D reconstruction from measurements that are sparse or badly timed, like single-photon counts, rolling-shutter video and fMRI. I also work on predictive coding networks, neural networks modeled on how the brain predicts its own sensory input and learns from what it gets wrong.

Code for our papers:

- [FirstCross](https://github.com/Arthur031221/firstcross) reconstructs an object from a few single-photon lidar views by solving a short sequence of convex problems, about a minute per object

I also send fixes to open source libraries I depend on. In [unsloth](https://github.com/unslothai/unsloth/pull/13256), left-padded prompts now generate the same text with cached Llama and Qwen3 attention. [xgboost](https://github.com/dmlc/xgboost/pull/12636) now refuses NumPy masked arrays, which used to slip through and could silently corrupt training data. MaxSim scoring in [sentence-transformers](https://github.com/huggingface/sentence-transformers/pull/4153) stays within its memory budget when a batch mixes long and short queries.

Selected tools I built:

- [Sunspill](https://github.com/Arthur031221/Sunspill) shows where sunlight lands in a room, by hour and season
- [Rumbleback](https://github.com/Arthur031221/Rumbleback) replays past earthquakes in the browser
- [SnipMD](https://github.com/Arthur031221/SnipMD) turns a screen region into Markdown or LaTeX, offline

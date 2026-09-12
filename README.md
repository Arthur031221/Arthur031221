## Chi-Wei Lee 李騏維

NeuroAI and computer vision. Physics and EECS (AI track) double major at National Tsing Hua
University, currently visiting UCLA, applying for PhD entry in 2027.

I work on predictive coding, Bayesian inference and generative models. At the HMI Lab I build
generative decoders that reconstruct 3D spatial representations from fMRI.

[arthur031221.github.io](https://arthur031221.github.io/)

### Open source

I look for correctness defects in scientific Python libraries, the kind that return a wrong
number rather than raising. Each report carries a reproduction a maintainer can run, and a test
that fails on the released version and passes after the fix.

Merged upstream:

- [stanfordnlp/stanza#1663](https://github.com/stanfordnlp/stanza/pull/1663), convert a multi word token id back to a tuple when a Document is rebuilt
- [stanfordnlp/stanza#1664](https://github.com/stanfordnlp/stanza/pull/1664), keep empty words out of the token list
- [stanfordnlp/stanza#1665](https://github.com/stanfordnlp/stanza/pull/1665), interleave empty words per word rather than per token
- [infer-actively/pymdp#442](https://github.com/infer-actively/pymdp/pull/442), label lists on multiple axes selected diagonals instead of blocks

Reported here, fixed upstream by someone else:

- [poldracklab/pydeface#82](https://github.com/poldracklab/pydeface/issues/82), the FSL launcher was probed instead of the binary actually called. Fixed in [#83](https://github.com/poldracklab/pydeface/pull/83).
- [SpikeInterface/spikeinterface#4735](https://github.com/SpikeInterface/spikeinterface/issues/4735), a frame window read from the wrong variable when merging units. Fixed in [#4743](https://github.com/SpikeInterface/spikeinterface/pull/4743).

Reported here, a fix is open:

- [NeuralEnsemble/python-neo#1889](https://github.com/NeuralEnsemble/python-neo/issues/1889), a circular ROI dropped the pixels on its own boundary. [#1895](https://github.com/NeuralEnsemble/python-neo/pull/1895).
- [BerkeleyLearnVerify/Scenic#493](https://github.com/BerkeleyLearnVerify/Scenic/issues/493), undefined names reachable at runtime. [#500](https://github.com/BerkeleyLearnVerify/Scenic/pull/500).

In review:

- [nilearn/nilearn#6480](https://github.com/nilearn/nilearn/pull/6480), keep the column of data axis in `t` and `conf_int`
- [poldracklab/pydeface#84](https://github.com/poldracklab/pydeface/pull/84), apply the defacing mask to every volume of a 4D image

Open reports awaiting triage sit in
[nipy/nibabel](https://github.com/nipy/nibabel/issues/1533),
[nipreps/mriqc](https://github.com/nipreps/mriqc/issues/1445),
[scverse/scanpy](https://github.com/scverse/scanpy/issues/4347),
[scikit-bio](https://github.com/scikit-bio/scikit-bio/issues/2571),
[stanford-crfm/helm](https://github.com/stanford-crfm/helm/issues/4337) and others.

### Selected work

- [X-Ray](https://github.com/Arthur031221/X-Ray), chest X-ray pathology classification trained on one demographic subgroup and evaluated across all five, DenseNet121 against Xception
- [NSF-HDR](https://github.com/Arthur031221/NSF-HDR), team entry for the 2025 NSF HDR anomaly detection challenge, all three tracks
- [quantum-allosteric-scanner](https://github.com/Arthur031221/quantum-allosteric-scanner), continuous time quantum walk prediction of allosteric sites from a single unbound protein structure
- [MatrixQR](https://github.com/Arthur031221/MatrixQR), video generation that keeps a QR code scannable while it is stylised
- [Arthur031221.github.io](https://github.com/Arthur031221/Arthur031221.github.io), bilingual research site, static HTML with no framework or runtime dependency

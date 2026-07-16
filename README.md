# 👋 @aRealGem

**30-odd years building production software - now pointed at open-source cancer genomics.**

- 🛠️ **The day job, for three decades:** full-stack Java/Spring for banks - developer up through team lead, dev manager, systems architect. Mostly the connective tissue of large financial systems: service and integration layers (SOAP and REST) over core systems of record, and the real-time and back-office processing behind them. The kind of work where an outage means somebody's paycheck doesn't clear, so you learn to build like it counts. Retired 2025 - turns out that frees up a lot of time.

- 💞️ **What I'm setting out to do:** point three decades of production engineering at open cancer-genomics tooling. I'm at the starting line here, not mid-stream - no merged PRs to my name yet, which is rather the point of starting. [cBioPortal](https://github.com/cBioPortal/cbioportal) (Java/Spring + React - home ground, minus the 15 years of rust I'm scraping off the tooling) and [nf-core](https://github.com/nf-core) (Nextflow) are the two that fit me best so far, and the ones I'd most want to start on - though I'm open to wherever a senior pair of hands is short. Researchers and clinicians run this software to make real calls about real tumors, and plenty of it is held together by people who'd frankly rather be doing the science. Fine. The help I want to give is at the unglamorous end - validators, backend, CI, the plumbing that decides whether you can trust the numbers. The scoreboard I care about is merged PRs. Not planting a flag on anyone's repo, just looking to lighten the load.

- 🔬 **Why me, dear reader:** I've been in a fight with colorectal Cancer for over half a decade now and, so far, holding my own (which means I've read more of my own genomic reports than I ever intended to). Cancer is, at bottom, a coding error - delivery's the hard part, not the concept (CRISPR a suppressor back on here, an oncogene off there, and in principle, presto). I'd like the tools that hunt those errors down built like they matter. Because they do.

- 🧰 **Toolkit:** Java/Spring, Python, TypeScript/React, Nextflow, TensorFlow/Keras, and a Raspberry Pi 5 (ARM64) fleet I keep around for pipeline-portability testing and ETL.

- 🧪 **Applied ML:** [histopath-cancer-detection](https://github.com/aRealGem/histopath-cancer-detection) - a leakage-aware PatchCamelyon pipeline with a private scored AUROC north of 0.95. MobileNetV3 transfer on a WSI-grouped split (no slide's patches leak across train/val - the thing that quietly inflates val scores if you skip it). Reported baseline: 0.907 public / 0.876 private AUROC on Kaggle's late-submission board - a Playground comp, so no medal, but val and public landed within 0.001, so the number's honest, not luck. Built a spread of diversifiers around it too - from-scratch CNNs, a domain-adversarial (DANN) stain-adaptation head, and a P4M group-equivariant DenseNet (rotation symmetry, straight from the PCam literature). Config-driven TF/Keras, reproducible on a free Kaggle GPU. Also: [AnimalDetector](https://github.com/aRealGem/AnimalDetector) (CNN/RNN).

- 👀 **Reading up on:** multi-omics, microbiology, the gene-therapy frontier, and whether we get the benevolent Singularity or the other kind (rooting hard for the former).

- 📫 **Reach me:** open an issue on any repo here, or tag @aRealGem in a PR or thread. A proper email alias is on the way (never the personal inbox - I like my threat model boring).

- 😄 **Pronouns:** she/her

- ⚡ **Fun fact:** black belt in Taekwondo. Also deep in SpaceFlight Simulator and working up the nerve to graduate to Kerbal Space Program (rockets being physics with immediate, fiery feedback).

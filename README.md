# About

I'm Tornike Onoprishvili (aka `tornikeo`). I specialize in AI, GPUs, and the Cloud. If you have a cool research idea or project please reach out by email at `tornikeonoprishvili [AT] gmail [dot] com`. I'm always happy to help out and collaborate.

# Projects

- I built and maintain the fastest exact [Cosine Similarity calculation tool](https://github.com/PangeAI/simms). It's a simple, unoptimized CUDA kernel that calculates mass spectrum [Cosine Similarity](https://matchms.readthedocs.io/en/latest/api/matchms.similarity.CosineGreedy.html) and [Modified Cosine Similarity](https://matchms.readthedocs.io/en/latest/api/matchms.similarity.ModifiedCosine.html) scores. The 1700x speedup comes from the typically massive memory bandwidth of GPUs. No shared memory or highly optimized memory access is used. I hope to optimize this further at some point.
- I've designed key parts of an upcoming [MS/MS Foundation model, SpectruMS](https://github.com/tornikeo/cdn/raw/master/assets/spectrums/iccs_presentation.pdf). The paper is a work in progress.
- I built a [finite-difference time-domain simulation tool](https://github.com/tornikeo/optical_nand) for fully all-optical logic gates. These "optical gates" are made of a special glass that changes its refractive index $n$ as the power of the laser increases. This allows us to make a fully optical AND gate. The simulations also show how the all-powerful NAND gate can be built. All simulation code is in MATLAB.

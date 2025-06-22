# About

I'm Tornike Onoprishvili (aka `tornikeo`). I am a master's degree student in Computer Science at [USI](https://www.usi.ch/en). You can reach me at `[my firstname][my lastname]@gmail.com`. My interests include graphics processing units (GPUs), high-performance computing, and machine learning.

# Projects

- I built and maintain the fastest exact [Cosine Similarity calculation tool](https://github.com/PangeAI/simms). It's a fairly simple, unoptimized CUDA kernel that calculates mass spectrum [Cosine Similarity](https://matchms.readthedocs.io/en/latest/api/matchms.similarity.CosineGreedy.html) and [Modified Cosine Similarity](https://matchms.readthedocs.io/en/latest/api/matchms.similarity.ModifiedCosine.html) scores. The 1700x speedup comes from the typically massive memory bandwidth of GPUs. No shared memory or overly optimized memory access is used. I'll hopefully optimize this at some point.
- I've designed key parts of an upcoming [MS/MS Foundation model, SpectruMS](https://github.com/tornikeo/cdn/raw/master/assets/spectrums/iccs_presentation.pdf). The paper is a work in progress.
- I built a [finite-difference time-domain simulation tool](https://github.com/tornikeo/optical_nand) for fully all-optical logic gates. These "optical gates" are made of a special glass that changes its refractive index $n$ as the power of the laser increases. This allows us to make a fully optical AND gate. The simulations also show how the all-powerful NAND gate can be built. All simulation code is in MATLAB.

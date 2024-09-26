__Abstract:__ The virtualization of physical acoustic environments, essential for augmented reality and immersive spatial audio applications, typically requires the storage and transmission of a large quantity of room impulse responses (RIRs). Real-world RIRs often comprise tens of thousands of coefficients. As such, working with large databases of room acoustic measurements presents significant challenges in terms of memory and bandwidth requirements. To address this issue, we investigate neural audio codecs as a means to achieve lossy RIR data compression. In particular, by focusing on two publicly available datasets, we show that EnCodec, a recently proposed state-of-the-art neural audio codec with bitrate as low as 1.5 kbps, is able to achieve a compression ratio over two orders of magnitude larger than lossless coding. Objective metrics and a listening test reveal that EnCodec preserves perceptually relevant features of the decoded reverberation better than a traditional dimensionality reduction method based on singular value decomposition, encouraging further research on the topic of neural RIR coding. 

This page features several audio examples of compressed reverberation obtained by encoding room impulse responses (RIRs) using [EnCodec](https://github.com/facebookresearch/encodec) and a classic SVD-based dimensionality reduction algorithm ([Huang et al., 2023](https://doi.org/10.1109/LSP.2023.3306619)).
These audio clips were part of the listening test presented in the following paper.

> A. I. Mezza, A. Bernardini, and F. Antonacci, "Large-Scale Room Impulse Response Dataset Compression With Neural Audio Codecs," in *Proc. 5th IEEE International Symposium on the Internet of Sounds*, 2024.

## Audio Examples

Coming soon

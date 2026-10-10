<p>
  <a href="https://demohatesrng1.github.io/demohatesrng1/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/github/header-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/github/header-light.svg">
      <img alt="Dhruv Dabas, ドルブ・ダバス" src="assets/github/header-light.svg" width="100%">
    </picture>
  </a>
</p>

Master's student at **Waseda University**, in the [Katto Laboratory](https://www.katto.comm.waseda.ac.jp/wordpress/).
I research **image and video information processing**, especially how images and video are compressed,
both for people and for the machines that watch them.

[Website](https://demohatesrng1.github.io/demohatesrng1/) &nbsp;·&nbsp; [日本語](https://demohatesrng1.github.io/demohatesrng1/ja/) &nbsp;·&nbsp; [CV](https://demohatesrng1.github.io/demohatesrng1/cv.html) &nbsp;·&nbsp; [onidemorng@gmail.com](mailto:onidemorng@gmail.com)

### Research

**Image and video information processing** &nbsp;<sub>Katto Laboratory, Waseda · 2026–</sub>

- **Neural video compression** (DCVC): video codecs built from neural networks
- **Coding for machines** (ICM / VCM): compressing images and video for the models that analyse them, not only for human eyes
- **ROI coding**: spending more bits on the regions of a frame that matter
- **Diffusion models** and **computer vision**

Papers and results will be listed here.

<!-- Research entries go here, newest first. Copy this block for each one:

**Paper or project title** &nbsp;<sub>Venue or status · Year</sub><br>
Authors, with **Dhruv Dabas** in bold. One sentence on the question, one on the result.
[paper](URL) · [code](URL) · [slides](URL)

-->

### Selected work

**[Neural video compression pipeline](https://demohatesrng1.github.io/demohatesrng1/#projects)** &nbsp;<sub>CUDA · C++ · PyTorch · YOLOv8</sub><br>
I deployed DCVC-RT, the CVPR 2025 real-time neural video codec, on a CUDA GPU server and built its custom C++/CUDA extensions.
Rate–distortion at four quantization levels, on 4K and lower-resolution video: 38–53 dB PSNR at 0.0008–0.011 bpp.
Then I ran YOLOv8 multi-object tracking on the decoded frames, to see where tracking starts to break.

**[Mimi](https://demohatesrng1.github.io/demohatesrng1/#projects)** &nbsp;<sub>C++ · Qt6 · Whisper · Metal · CoreAudio</sub><br>
A privacy-first Japanese voice assistant for macOS that never calls the cloud: speech recognition, a local LLM and speech synthesis all run on the Mac.
I ported the Python prototype to about 17.6K lines of C++/Qt6 so Whisper runs on the Metal GPU at 13–15× real time.
A lock-free 30-second ring buffer, fed from the CoreAudio real-time thread, lets voice-activity detection, wake-word spotting and transcription run in parallel.

**[Poker](https://github.com/demohatesrng1/Poker)** &nbsp;<sub>C++</sub><br>
The game of poker, built from scratch in C++.

### 日本語

<p lang="ja">はじめまして、ドルブです。早稲田大学大学院の1年生で、甲藤研究室にいます。画像と動画の情報<ruby>処理<rp>（</rp><rt>しょり</rt><rp>）</rp></ruby>を研究しています。テーマは、ニューラル動画<ruby>圧縮<rp>（</rp><rt>あっしゅく</rt><rp>）</rp></ruby>（DCVC）、AIのための画像・動画の圧縮（ICM / VCM）、ROI、<ruby>拡散<rp>（</rp><rt>かくさん</rt><rp>）</rp></ruby>モデル、コンピュータビジョンです。日本語はJLPT N3です。日本語で話しかけてもらえると、うれしいです。</p>

<sub>Python · C++ · CUDA · PyTorch · Qt6 · Docker &nbsp;—&nbsp; English · 日本語 (JLPT N3) · 中文 (HSK 3)</sub>

<br>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/github/gop-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/github/gop-light.svg">
    <img alt="" src="assets/github/gop-light.svg" width="200">
  </picture>
  <br>
  <sub><em>If it doesn’t challenge you, it doesn’t change you.</em></sub>
</p>

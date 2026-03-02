---
caption:
  title: "Speed-Aware Audio-Driven Speech Animation using Adaptive Windows"
  subtitle: |
    ACM Transactions on Graphics (TOG)
    SIGGRAPH Asia 2024
  thumbnail: assets/img/publications/2024_TOG_th.png


title: |
  Speed-Aware Audio-Driven Speech Animation using Adaptive Windows
authors: |
  Sunjin Jung, Yeongho Seol, Kwanggyoon Seo,<br>
  Hyeonho Na, Seonghyeon Kim, Vanessa Tan, Junyong Noh
journal: "ACM Transactions on Graphics, Volume 44, Issue 1, October 2024, Pages 1-14"
conference: "SIGGRAPH Asia 2024"
paper_url: "https://dl.acm.org/doi/10.1145/3691341"

image: assets/img/publications/2024_TOG.png

abstract: |
  We present a novel method that can generate realistic speech animations of a 3D face from audio using multiple adaptive windows. In contrast to previous studies that use a fixed size audio window, our method accepts an adaptive audio window as input, reflecting the audio speaking rate to use consistent phonemic information. Our system consists of three parts. First, the speaking rate is estimated from the input audio using a neural network trained in a self-supervised manner. Second, the appropriate window size that encloses the audio features is predicted adaptively based on the estimated speaking rate. Another key element lies in the use of multiple audio windows of different sizes as input to the animation generator: a small window to concentrate on detailed information and a large window to consider broad phonemic information near the center frame. Finally, the speech animation is generated from the multiple adaptive audio windows. Our method can generate realistic speech animations from inthe-wild audios at any speaking rate, i.e., fast raps, slow songs, as well as normal speech. We demonstrate via extensive quantitative and qualitative evaluations including a user study that our method outperforms state-ofthe-art approaches.
---




<div align="center">

OffensiveContentPredictionTF
===========================
<h4> A TensorFLow Implementation for predicting offensive content in a video or video URL. </h4>

<!-- [![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](https://huggingface.co/docs/optimum/index)
[![python](https://img.shields.io/badge/python-3.10.12-green)](https://www.python.org/downloads/release/python-31013/)
[![cuda](https://img.shields.io/badge/cuda-12.2-green)](https://developer.nvidia.com/cuda-downloads)
[![trt-llm](https://img.shields.io/badge/TensorRT--LLM-0.9.0-green)](https://github.com/nvidia/tensorrt-llm)
[![license](https://img.shields.io/badge/license-Apache%202-blue)](./LICENSE) -->

---
<div align="left">

Refer to the audio_transcription_notebook.ipynb for the code. The notebook offers data preparation, training, inference, and gradio UI implementations for performing realtime inference.

</div></div>

# Dataset
The dataset used for this problem is Toxic Tweets Challenge dataset from Kaggle. (https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/code?competitionId=8076&sortBy=voteCount).

# Demo UI
A gradio UI demo is giving below. The UI takes both Video or and Video URL and computes the %age of the offensive content falling in one of the following categories:
  1. toxic
  2. severe_toxic
  3. obscene
  4. threat
  5. insult
  6. identity_hate
  7. Not Offensive

https://github.com/mjehanzaib999/OffensiveContentPredictionTF/assets/66511746/9656528c-687b-4de2-89f4-600b58990cd9




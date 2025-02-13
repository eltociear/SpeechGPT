# SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities

<a href='https://0nutation.github.io/SpeechGPT.github.io/'><img src='https://img.shields.io/badge/Project-Page-Green'></a>  <a href='https://arxiv.org/abs/2305.11000'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a>

<p align="center">
    <img src="Pictures/logo.png" width="20%"> <br>
</p>

## Introduction
SpeechGPT is a large language model with **intrinsic cross-modal conversational abilities**, capable of perceiving and generating multi-model content following human instructions. With discrete speech representations, we first construct **SpeechInstruct**, a large-scale cross-modal speech instruction dataset. Additionally, we employ a three-stage training strategy that includes **modality-adaptation pre-training**, **cross-modal instruction fine-tuning**, and **chain-of-modality instruction fine-tuning**. The experimental results demonstrate that SpeechGPT has an impressive capacity to follow multi-modal human instructions and highlight the potential of handling multiple modalities with one model. <br>
SpeechGPT demos are shown in our [project page](https://0nutation.github.io/SpeechGPT.github.io/). As shown in the demos, SpeechGPT has strong cross-modal instruction-following ability and spoken dialogue ability. SpeechGPT can be **a talking encyclopedia, your personal assistant, your chat partner, a poet, a psychologist and your educational assistant**...

<br>
<br>
<p align="center">
    <img src="Pictures/speechgpt-intro.png" width="95%"> <br>
    SpeechGPT’s capabilities to tackle multiple cross-modal tasks
</p>
<br>
<br>
<p align="center">
    <img src="Pictures/SpeechGPT-main.png" width="95%"> <br>
    Left: SpeechInstruct construction process.  Right: SpeechGPT model structure
</p>


## Release
- [5/18] 🔥 We released **SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities**. We propose SpeechGPT, the first multi-modal LLM capable of perceiving and generating multi-modal contents following multi-modal human instructions.  Checkout the [paper]() and [demo](https://0nutation.github.io/SpeechGPT.github.io/).


## Contents
- [Dataset](#dataset)
- [Models](#models)
- [Talk with SpeechGPT](#talk-with-speechgpt)
- [Fine-tune SpeechGPT](#fine-tune-speechgpt)
- [Performance](#performance)



## Dataset
We will release SpeechInstruct dataset.
## Models
We will release modality-adaptation pre-trained model, cross-modal instruction fine-tuned model and chain-of-modality instruction fine-tuned model.
## Talk with SpeechGPT
## Fine-tune SpeechGPT
## Performance
SpeechGPT demos are shown in our [project page](https://0nutation.github.io/SpeechGPT.github.io/). As shown in the demos, SpeechGPT has strong cross-modal instruction-following ability and spoken dialogue ability. SpeechGPT can be a talking encyclopedia, your personal assistant, your chat partner, a poet, a psychologist andd your educational assistant etc.
<br>
<br>
<p align="center">
    <img src="Pictures/cases_cm_inst_follow.png" width="95%"> <br>
    Cases of cross-modal instruction-following results
</p>
<br>
<br>
<p align="center">
    <img src="Pictures/cases_spoken_dialogue.png" width="95%"> <br>
    Cases of spoken dialogue results
</p>

## Acknowledgement
- [MOSS](https://github.com/OpenLMLab/MOSS): We use moss-sft-002-data.
- [stanford_alpaca](https://github.com/tatsu-lab/stanford_alpaca):The codebase we built upon.

If you find SpeechGPT useful for your research and applications, please cite using the BibTex:

```
@misc{zhang2023speechgpt,
      title={SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities}, 
      author={Dong Zhang and Shimin Li and Xin Zhang and Jun Zhan and Pengyu Wang and Yaqian Zhou and Xipeng Qiu},
      year={2023},
      eprint={2305.11000},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

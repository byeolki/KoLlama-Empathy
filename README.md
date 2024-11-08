# 🤖 Llama-KoEmpathy

Llama-KoEmpathy는 LLaMA 기반의 한국어 감정 인식 챗봇 모델입니다. 해당 레포에서는 학습 코드를 공유하고 있습니다.<br>
**해당 프로젝트는 단대소고 포트폴리오 제출을 위해 제작되었습니다.**

*Built with Llama*

## ✨ Features
- LLaMA 아키텍처 기반 한국어 챗봇
- 감정 인식 및 공감 능력
- LoRA를 활용한 효율적인 파인튜닝

## ⚠️ License Requirements
이 프로젝트를 사용할 때 다음 사항을 준수해야 합니다:
- Meta의 [Acceptable Use Policy](https://llama.meta.com/llama3_1/use-policy)를 따라야 합니다
- 월간 활성 사용자가 7억명을 초과하는 제품/서비스에 사용할 경우 Meta의 별도 라이선스가 필요합니다

## ⚙️ Training Configuration

- 📏 Max Sequence Length: 2048
- 📦 Batch Size: 128
- 🔄 Gradient Accumulation Steps: 4
- 📈 Learning Rate: 2e-4
- 🛠️ Optimizer: AdamW 8bit
- 💾 Quantization: GGUF q8_0
- 🔁 Training Epochs: 3

## ⚙️ Installation
```bash
git clone https://github.com/byeolki/Llama-KoEmpathy.git
cd Llama-KoEmpathy
pip install -r requirements.txt
```

## 🚀 Usage
자세한 사용법은 `tutorial.ipynb`를 참고해주세요.

학습된 모델을 사용하시려면 [HuggingFace Hub](https://huggingface.co/byeolki/Llama-KoEmpathy)를 방문해주세요.

## 🙏 Credits & References
이 프로젝트는 다음 오픈소스 프로젝트들을 참고 및 활용했습니다:

- [Llama 3.1](https://llama.meta.com/) - Meta AI의 Language Model (Llama 3.1 Community License)
  - 공감 능력을 가진 한국어 챗봇을 위해 파인튜닝한 [Llama-KoEmpathy](https://huggingface.co/byeolki/Llama-KoEmpathy) 모델을 사용합니다

## ⚖️ License
이 프로젝트는 다음 라이선스를 따릅니다:
- 프로젝트 코드: MIT License Copyright (c) 2024 Byeolki
- Llama 모델 및 관련 코드: Llama 3.1 Community License

## 📢 Notice
Llama 3.1 is licensed under the Llama 3.1 Community License, Copyright © Meta Platforms, Inc. All Rights Reserved.

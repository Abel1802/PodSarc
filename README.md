# PodSarc: A Podcast Sarcasm Speech Dataset

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]()
[![License](https://img.shields.io/badge/license-CC--BY--NC--4.0-green.svg)]()
[![Interspeech 2026](https://img.shields.io/badge/Interspeech-2026-orange.svg)]()
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)]()

> **PodSarc** is a large-scale bimodal sarcasm dataset consisting of podcast speech segments paired with transcripts and sarcasm annotations, designed to facilitate research in speech-based sarcasm detection.

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset Statistics](#dataset-statistics)
- [Citation](#citation)
- [License](#license)

---

## Overview

Sarcasm plays a crucial role in human communication by conveying meanings that contradict literal interpretations. Detecting sarcasm in speech remains challenging due to the scarcity of annotated datasets and the complexity of prosodic and contextual cues.

**PodSarc** addresses this challenge by providing a large-scale speech dataset specifically designed for sarcasm detection in audio-only environments, such as podcasts, radio broadcasts, and conversational AI systems.

The dataset is collected from the **Overly Sarcastic Podcast (OSPod)** and annotated using a hybrid pipeline combining LLM-based annotation and human verification.

### ✨ Key Features

- 🎙️ **29.42 hours** of speech data
- 📝 **11,024 utterances**
- 🔀 **Bimodal annotations** (Speech + Text)
- 👥 **8 speakers**
- ✅ **Human-verified** annotations

### 🎯 Research Applications

- Sarcasm detection in speech
- Multimodal sarcasm detection
- Prosody and pragmatic meaning
- Conversational AI
- Speech understanding

---

## Dataset Statistics

| Property | Value |
|----------|-------|
| Total utterances | 11,024 |
| Sarcastic | 4,026 (36.5%) |
| Non-sarcastic | 6,998 (63.5%) |
| Total duration | 29.42 hours |
| Avg. utterance duration | 9.61 seconds |
| Avg. transcript length | 31.18 words |
| Number of speakers | 8 |


---

## JSON Format
```json
{
    "text": "They are citizens. Why do you think the population is so big?",
    "gpt4o_sarcasm": true,
    "gpt4o_emotion": "sarcasm",
    "comment": "The speaker sarcastically refers to pigeons as 'citizens' to humorously imply they contribute to the city population, enhancing the exaggerated tone.",
    "index": 355,
    "nid": "66_355",
    "llama3_sarcasm": false,
    "human_check": "sarcasm"
  }
```

You can find the full dataset [here](https://drive.google.com/file/d/15gS1m_SBBbI3RKfoYYHJCcO0CiEXy9dO/view?usp=drive_link).


# Citation
If you use PodSarc in your research, please cite:
```bibtex
@inproceedings{li2026podsarc,
  title={Leveraging Large Language Models for Sarcastic Speech Annotation in Sarcasm Detection},
  author={Li, Zhu and Zhang, Yuqing and Gao, Xiyuan and Nayak, Shekhar and Coler, Matt},
  booktitle={Interspeech},
  year={2026}
}
```

---

# License
This dataset is released under the CC BY-NC 4.0 License.

- Permission	Status
- Academic research	✅ Allowed
- Modification & distribution	✅ Allowed
- Commercial use	❌ Not allowed

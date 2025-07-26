# Keyword Spotting System
-----

**`Attention Driven Fewshot Keyword Spotting System`**

## System Architecture
<img width="1680" height="761" alt="Blank diagram(1)" src="https://github.com/user-attachments/assets/d2583751-35a0-48d1-bbae-57a13902994d" />


## Background
Speech recognition technology has advanced significantly over the years, becoming vital to many modern applications such as virtual assistants, voice-activated devices, and security systems. Traditional Large Vocabulary Continuous Speech Recognition (LVCSR) systems achieve high accuracy by leveraging vast labeled datasets and complex models that transcribe continuous speech. However, these systems struggle with scalability, high computational costs, and adaptability to new keywords, languages, or dialects without having a lot of retraining.
Keyword Spotting (KWS) focuses on detecting predefined keywords within continuous audio streams, enabling efficient and low-latency voice interactions in devices with limited resources. Traditional KWS methods often require extensive labeled data per keyword, which restricts flexibility and deployment in dynamic or low-resource settings.
Few-shot learning has emerged as a promising solution to these challenges by enabling models to learn from a small number of labeled examples. Few-shot keyword spotting systems leverage metric learning and prototypical networks to represent keywords as embeddings, allowing recognition of new keywords with minimal data. Integrating attention mechanisms further enhances the ability to emphasize representative examples and adapt prototypes dynamically, improving robustness and accuracy.
This study builds upon the work of Parnami and Lee (2021), who introduced a few-shot keyword spotting framework based on dilated convolutional networks and prototypical learning, extending it with attention-driven prototype refinement to better handle noisy or limited data and context variability.



### AUTHOR(S)
- Abdulrahman Kalli Mustapha - kmustapha9564@gmail.com


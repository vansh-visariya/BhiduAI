# BhiduAI
This chatbot is part of an experiment in localizing LLMs to reflect cultural language nuances, starting with Mumbai. The idea is to build LLMs that talk like real people from the city — with humor, slang, and streetwise empathy.


To fine-tune BhiduAI, I created a custom instruction dataset in .jsonl format, based on tatsu-lab/alpaca.
3000+ entry was rewritten in authentic Mumbai Bambaiyya slang, mixing Hindi, English, and local street language to reflect everyday conversation styles.

---

## Quick Example

**User:**  
> *Write a motivational message for someone starting their first job.*

**BhiduAI:**  
> *Arre bhai, apun pehla job shuru kar raha hai na?  Waat lag gayi!  Tension nahi lene ka, apun tereko ek solid message deta hai.  Pehla, apun ki hard work karne ka, boss.  Apun ki dedication dikhao, aur apun ki passion se kaam karo.  Dusra, apun ki confidence rakhna hai, bhai.  Apun ki apun ki hai, aur apun ki apun ki hai.  Teesra, apun ki mistakes se seekhne ka, aur apun ki apun ki mistakes se learn karne ka.  Aur chautha, apun ki apun*

---

This model is available as a LoRA adapter on the Hugging Face Hub: [mumbai_slang-adapter](https://huggingface.co/vansh-myth/gemma-2-mumbai_slang-adapter)

If you want to run this model in google-colab or in your local machine run ```run.ipynb```

Tech Stack

Base Model: google/gemma-2-9b-it

Adapter Format: LoRA

Quantization: 4-bit QLoRA

Libraries: Unsloth, Hugging Face Transformers, PEFT


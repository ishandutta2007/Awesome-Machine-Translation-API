# Awesome-Machine-Translation-API

# Top Machine Translation API Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Neural Machine Translation, Multilingual APIs, Self-Hosted Translation Engines & Language Pair Coverage*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Machine Translation APIs**. These services and engines provide programmatic access to high-quality text (and sometimes document) translation across dozens or hundreds of languages, powering localization, content pipelines, chat, and global applications.

**Examples** include Microsoft Translator, Google Cloud Translation, DeepL API, AWS Translate, ModernMT, Systran, IBM Watson Language Translator, Baidu Translate API, Yandex Translate API, and Translated (the category leaders).

**Open-source emphasis**: Commercial APIs still lead in quality and language coverage for many pairs, but strong open-source alternatives exist. **LibreTranslate**, **Argos Translate**, **OPUS-MT / Marian**, **NLLB**, **M2M-100**, and related projects enable fully self-hosted, offline-capable translation. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Microsoft Translator](https://www.microsoft.com/translator/)**  
  Microsoft’s cloud translation API (part of Azure AI Services) supporting a wide range of languages, custom models, and document translation.

- **[Google Cloud Translation](https://cloud.google.com/translate)**  
  Google’s neural machine translation API with broad language coverage, glossary support, and integration across Google Cloud services.

- **[DeepL API](https://www.deepl.com/pro-api)**  
  Highly regarded neural translation API known for natural-sounding output, especially for European language pairs, with formal/informal tone controls.

- **[AWS Translate](https://aws.amazon.com/translate/)**  
  Amazon’s neural machine translation service integrated with the AWS ecosystem, supporting real-time and batch translation.

- **[ModernMT](https://www.modernmt.com/)**  
  Adaptive machine translation platform that learns from user corrections and translation memories for improved domain-specific quality.

- **[Systran](https://www.systransoft.com/)**  
  Enterprise machine translation provider offering both generic and specialized (domain-adapted) translation engines and APIs.

- **[IBM Watson Language Translator](https://www.ibm.com/products/language-translator)**  
  IBM’s cloud translation service with support for multiple languages and customization options within the Watson ecosystem.

- **[Baidu Translate API](https://fanyi-api.baidu.com/)**  
  Baidu’s machine translation API with strong coverage of Chinese and other languages, popular in Asia-focused applications.

- **[Yandex Translate API](https://yandex.com/dev/translate/)**  
  Yandex’s translation API offering solid support for Russian and many other languages with straightforward REST access.

- **[Translated](https://translated.com/)**  
  Language service provider offering machine translation APIs and hybrid human+MT solutions for professional localization workflows.

## Open-Source GitHub Projects
- **[LibreTranslate](https://github.com/LibreTranslate/LibreTranslate)**  
  Free and open-source machine translation API that is fully self-hosted and offline-capable, powered by Argos Translate models.

- **[Argos Translate](https://github.com/argosopentech/argos-translate)**  
  Open-source neural machine translation library written in Python, providing the models and engine behind LibreTranslate.

- **[OPUS-MT / MarianMT models](https://github.com/Helsinki-NLP/OPUS-MT-train)**  
  Large collection of open machine translation models trained on the OPUS corpus, usable with Marian or Hugging Face Transformers.

- **[NLLB (No Language Left Behind)](https://github.com/facebookresearch/fairseq/tree/nllb)**  
  Meta’s open multilingual translation models covering 200+ languages, available via fairseq and Hugging Face.

- **[M2M-100](https://github.com/facebookresearch/fairseq/tree/main/examples/m2m_100)**  
  Meta’s many-to-many multilingual translation model supporting direct translation between 100 languages without English pivoting.

- **[OpenNMT](https://github.com/OpenNMT)**  
  Open-source neural machine translation framework (OpenNMT-py / OpenNMT-tf) for training and deploying custom translation models.

- **[CTranslate2](https://github.com/OpenNMT/CTranslate2)**  
  Fast inference engine for Transformer models, commonly used to serve open MT models efficiently in production.

- **[Documentation and LibreTranslate / Argos / OPUS-MT guides](https://libretranslate.com/)**  
  Resources for self-hosting translation APIs, downloading models, and integrating open MT into applications.

- **[Hugging Face Transformers translation pipelines](https://github.com/huggingface/transformers)**  
  Ready-to-use pipelines and model hubs for running open translation models (OPUS-MT, NLLB, M2M-100, etc.).

- **[Community model conversion and training toolkits (Locomotive, etc.)](https://github.com/LibreTranslate/Locomotive)**  
  Tools for training or converting models to formats compatible with LibreTranslate and Argos Translate.

### Additional Strong Open-Source Options
- Self-hosting **LibreTranslate** for a simple, privacy-friendly translation API.
- Using **Argos Translate** or **CTranslate2** for lightweight local inference.
- Leveraging **OPUS-MT**, **NLLB**, or **M2M-100** models via Hugging Face or Marian for high-quality open translation.
- Training domain-specific models with **OpenNMT** when specialized quality is required.
- Accepting that commercial APIs (DeepL, Google, Microsoft, AWS) still lead in overall quality, latency SLAs, and language coverage for many production use cases.
- Focusing open-source efforts on data privacy, offline capability, cost control, and custom model training.

**Frameworks for building custom systems**: Deploy LibreTranslate or a CTranslate2-backed service → load OPUS-MT / NLLB / Argos models → expose a simple REST API → optionally fine-tune on domain data. Suitable for privacy-sensitive applications, air-gapped environments, and cost-conscious high-volume translation. Many products still call commercial APIs for the highest quality or broadest language support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Machine translation quality varies by language pair and domain. Open-source models may lag commercial engines on some pairs. This list is not localization or quality assurance advice.

---
**Made for developers, localization teams, and open-language technology advocates.**
Let's keep translation accessible, private, and as open as practical.

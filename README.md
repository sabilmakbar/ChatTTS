<div align="center">

# ChatTTS w/ Toolkit
Forked from ChatTTS Repo

[![Licence](https://img.shields.io/github/license/2noise/ChatTTS?style=for-the-badge)](https://github.com/2noise/ChatTTS/blob/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/ChatTTS.svg?style=for-the-badge&color=green)](https://pypi.org/project/ChatTTS)

[![Huggingface](https://img.shields.io/badge/🤗%20-Models-yellow.svg?style=for-the-badge)](https://huggingface.co/2Noise/ChatTTS)
[![Open In Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)](https://colab.research.google.com/github/2noise/ChatTTS/blob/main/examples/ipynb/colab.ipynb)
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Ud5Jxgx5yD)

**English** | [**简体中文**](docs/cn/README.md) | [**日本語**](docs/jp/README.md) | [**Русский**](docs/ru/README.md) | [**Español**](docs/es/README.md) | [**Français**](docs/fr/README.md) | [**한국어**](docs/kr/README.md)

</div>

## Introduction
This repo contains patch of ChatTTS that will include `tools`

To utilize the `tools` module, just simply do 
```python
from ChatTTS import tools as chattts_tools
```

> [!Note]
> The `tests` is already adjusted to use `tools` calling from this repo dir structure, but not with the `examples`

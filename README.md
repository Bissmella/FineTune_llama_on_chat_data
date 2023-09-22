# FineTune llama on chat data
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://mit-license.org/)
[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![PyPI - Python Version](https://img.shields.io/pypi/v/llm-guard)](https://pypi.org/project/guardrail-ml)


Llama v2 7b is a large language model (LLM) with 7 billion parameters that can be used for a variety of tasks, including text generation, translation, and question answering. In this notebook, we will show you how to fine-tune Llama v2 7b on your personal WhatsApp chats for private use using Google Colab free GPU.

## 🤖Instructions:
- First of all ask for the consent of your friends of whom you are using your chat with them for fine-tuning Llama model.
- Download the chat from whatsapp.
- Upload the chat text file to the notebook provided. The chats will be processed and converted to a dataset using your replies as "response" the previous 5 chats as "context" and the chat before your reply as "instruction".
- Request for access to Llama v2 model in Huggingface🤗 and provide your credentials when asked in notebook for downloading the mode.
- Test and evaluate the fine-tuned model.
- Make sure not to share the fine-tuned model in public.


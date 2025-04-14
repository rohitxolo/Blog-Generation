# ✍️ LLama2 Blog Generator

**LLama2 Blog Generator** is an interactive web app built with **Streamlit** that leverages the power of **Meta's LLama 2** model to generate short, professional blogs tailored for different audiences. It supports custom blog topics, word count limits, and writing styles like *Researchers*, *Data Scientists*, or *Common People*.

---

## 🚀 Features

- 🔗 Local inference using **CTransformers** and **LLama2 GGML**
- ✍️ Generates blogs for various audiences
- 📏 Custom word count input
- ⚡ Fast and lightweight — runs locally without the need for API keys
- 🧠 Simple interface with Streamlit UI

---

## 🧠 Tech Stack

| Layer       | Tool/Library                 |
|-------------|------------------------------|
| 💬 LLM      | [LLama 2 7B Chat GGML](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML) |
| 🧠 Wrapper   | [CTransformers](https://github.com/marella/ctransformers) |
| ⚙️ Backend   | Python 3.x                   |
| 🖥️ Frontend  | [Streamlit](https://streamlit.io) |

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/llama2-blog-generator.git
cd llama2-blog-generator

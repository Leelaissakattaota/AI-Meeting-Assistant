# 🎙️ AI Meeting Assistant: Instant Notes, Zero Worries

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![IBM watsonx.ai](https://img.shields.io/badge/Powered%20By-IBM%20watsonx.ai-7D3CFF?style=for-the-badge)
![Gradio](https://img.shields.io/badge/UI-Gradio-orange?style=for-the-badge)

In today's fast-paced work environment, capturing every detail of a meeting manually is a challenge. This project provides an **AI-powered transformative solution** for meeting documentation by leveraging Large Language Models (LLMs) and Generative AI to automate note-taking and extract critical insights efficiently.

---

## 🚀 Key Features

* **🎙️ Intelligent Transcription**: Uses **OpenAI Whisper** to convert audio speech from multiple formats into accurate text.
* **🛠️ Text Preprocessing**: Automatically cleans transcripts by removing non-ASCII characters and correcting punctuation.
* **🧠 Context-Aware Corrections**: Employs **Llama 3.2** as a product assistant to ensure technical and financial terminology is correctly formatted.
* **📝 Automated Minutes**: Leverages **IBM Granite 3.0** via **LangChain** to generate structured meeting minutes and task lists.
* **💻 Seamless UI**: A user-friendly web interface built with **Gradio** for easy audio uploads and one-click processing.

---

## 🏗️ Technical Workflow

The application follows a robust end-to-end pipeline:
1.  **Audio Input**: Users upload a `.wav` or `.mp3` recording.
2.  **Whisper Processing**: Converts the audio to a raw transcript.
3.  **Refinement**: A specialized LLM assistant cleans the text and standardizes terms.
4.  **Intelligence Layer**: A LangChain-driven prompt template instructs the LLM to identify key points and actionable items.
5.  **Output**: The user receives a structured text report available for instant download.

---

## 🛠️ Installation & Setup

### Prerequisites
* Python 3.10+
* `ffmpeg` installed on your system

### Setup Environment
```bash
pip3 install virtualenv
virtualenv my_env
source my_env/bin/activate


# 🤖 **B-Bot: Your Emotion-Aware AI Companion**  
**Unlocking Human Emotion Through AI**  
> 🚀 A project built for the [Summer of Scribbling 2025 Hackathon](https://hub.scribbler.live)

---

## 🧠 Overview

**B-Bot** is a browser-based AI companion that can **see your face**, **sense your emotion**, and **respond with empathy** — in real-time. It combines cutting-edge generative AI tools and browser APIs to create an emotionally intelligent, hands-free conversation experience.

---

## 🖼️ System Architecture

![System Architecture](https://github.com/user-attachments/assets/01167513-30cd-496d-ad75-395d3a2e2dd5)

---

## ⚙️ Prerequisites

| 🔑 Requirement         | 📌 Description                                                                                                   |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| **OpenAI API Key**     | Get your key from [OpenAI Platform](https://platform.openai.com/settings/organization/api-keys).               |
| **Groq API Key**       | Generate from [Groq Console](https://console.groq.com/keys).                                                    |
| **WebLLM**             | Setup guide on [WebLLM GitHub](https://github.com/mlc-ai/web-llm). <br> ⏱️ First load: ~3–4 min, then ~25 sec. |
| **Notebook Access**    | Click the 🔴 red button in the top-right to take the notebook **out of sandbox** before running.                |

---

## 🎯 What B-Bot Does

| 🛠️ Feature                   | 💡 Description                                                                                           |
|-----------------------------|-----------------------------------------------------------------------------------------------------------|
| 📸 **Face Snapshot**         | Captures your image via webcam in real-time.                                                              |
| 🧠 **Emotion Detection**     | Uses **Groq’s LLaMA-4 model** to detect your emotion from the image.                                       |
| 💬 **Empathetic Reply**      | Local LLM (WebLLM) generates a warm, caring message based on detected emotion.                            |
| 🔊 **AI Voice Response**     | Speaks the message using **OpenAI’s TTS** API — like a thoughtful friend.                                 |
| 🗣️ **Voice Input**           | Speak your replies using browser audio APIs — B-Bot updates its response based on your new expression.     |

---

## 🧰 Tech Stack

| 🔧 Category         | 🧠 Tools & Technologies                                                                                                                  |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| 💻 **Frontend**     | HTML, CSS, JavaScript                                                                                                                    |
| 🧠 **AI Models**    | - [Groq LLaMA-4](https://groq.com/) <br> - [WebLLM (local)](https://github.com/mlc-ai/web-llm)                                            |
| 🔉 **Voice Features** | - [OpenAI TTS](https://platform.openai.com/docs/guides/text-to-speech) <br> - Browser Web Speech API for voice input                   |
| 🖥️ **Browser APIs** | Webcam: `MediaDevices.getUserMedia` <br> Audio Input: `webkitSpeechRecognition`, `SpeechRecognition`                                     |
| 📒 **Notebook**     | [Scribbler Notebook](https://app.scribbler.live) – for interactive code execution                                                        |

---

## 🚀 How to Run It

### ▶️ [Launch the Notebook on Scribbler](https://app.scribbler.live/?jsnb=github:sudarsan2k5/B-Bot/B-Bot.jsnb)

1. Take the notebook **out of sandbox** (use the toolbar).
2. Click **Run All** or run each cell manually to start your AI-powered interaction.

---

## 📦 Submission Details

- **🏷️ Team**: ZOD  
- **📝 Notebook**: [`B-Bot`](https://app.scribbler.live/?jsnb=github:sudarsan2k5/B-Bot/B-Bot.jsnb)  
- **🏁 Hackathon**: Summer of Scribbling 2025  
- **🔗 GitHub**: [github.com/sudarsan2k5/B-Bot](https://github.com/sudarsan2k5/B-Bot)

> 👨‍💻 Built with love by [**TEAM ZOD**](https://github.com/sudarsan2k5/)

---

## 🌟 The Experience

> **Imagine this**: You're having a tough day. You open your browser.  
> B-Bot sees you, understands your emotion, and gently speaks to you —  
> just like a friend who really *gets* how you feel. 💛

# 🤖 B-Bot: Your Emotion-Aware AI Companion
Unlocking Human Emotion Through AI 
> 🚀 Built for the [Summer of Scribbling 2025 Hackathon](https://hub.scribbler.live)
# System Architecture Overview
![Project System Architecture](https://github.com/user-attachments/assets/01167513-30cd-496d-ad75-395d3a2e2dd5)

# Prerequisite

| Item                | Description                                                                                                      |
| ------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **OpenAI API Key**  | Get your API key [here](https://platform.openai.com/settings/organization/api-keys).                             |
| **Groq API Key**    | Get your API key [here](https://console.groq.com/keys).                                                          |
| **Web LLM**         | Reference: [Web LLM GitHub](https://github.com/mlc-ai/web-llm) <br> ⚠️ First load: 3–4 min, Subsequent: ~25 sec. |
| **Notebook Access** | Click the red button at the top-right corner to take the notebook out of sandbox. 

# 🎭 B-Bot: Your Emotion-Aware AI Companion

**B-Bot** is a browser-based app that understands how you feel just by looking at your face — and responds with empathy. It combines cutting-edge AI tools to create a hands-free, emotionally aware conversation experience.

---

## 🔍 What It Does

| 🔧 Feature                       | 💡 Description                                                                                        |
| -------------------------------- | ----------------------------------------------------------------------------------------------------- |
| 📸 **Face Snapshot**             | Captures an image from your webcam in real time.                                                      |
| 🧠 **Emotion Detection (Groq)**  | Uses Groq’s **LLaMA-4** model to interpret your facial expression and describe your emotion in words. |
| 💬 **Empathetic Reply (WebLLM)** | Local LLM generates a natural, kind response based on how you're feeling — like a caring friend.      |
| 🔊 **Text-to-Speech (OpenAI)**   | Speaks the AI's reply using OpenAI’s TTS API, simulating a real conversation.                         |
| 🗣️ **Voice Reply (STT)**         | Optional voice input lets you talk back — or just let the cycle continue with updated emotions.       |

---

## 🛠️ Tools & Technologies Used

| 🧩 Category           | ⚙️ Tools & Technologies                                                                                                                        |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| 📒 **Notebook**       | [Scribbler Notebook](https://app.scribbler.live/)                                                                                                  |
| 🌐 **Frontend**       | HTML, CSS, JavaScript                                                                                                                          |
| 🧠 **AI Models**      | - [Groq LLaMA-4](https://groq.com/) for emotion interpretation <br> - WebLLM (runs locally using WebGPU)                                       |
| 🔊 **Voice Features** | - [OpenAI TTS](https://platform.openai.com/docs/guides/text-to-speech) for speaking responses <br> - Browser Audio APIs for speech recognition |
| 🖥️ **Browser APIs**   | - Webcam via MediaDevices API <br> - Audio capture via Web Speech API.                                                                         |

---

---

## 🧪 How to Run
### 📎 [Open the Notebook in Scribbler](https://app.scribbler.live/?jsnb=github:sudarsan2k5/B-Bot/B-Bot.jsnb)
1. Take the notebook out of sandbox by choosing the option from the toolbar
2. Run all the cells one by one via 'Run' option from the toolbar

## 📝 Submission Info

- **Team Name**: ZOD  
- **Notebook**: [`B-Bot`](https://app.scribbler.live/?jsnb=github:sudarsan2k5/B-Bot/B-Bot.jsnb)
- **Hackathon**: Summer of Scribbling 2025  
- **GitHub Repo**: [B-Bot](https://github.com/sudarsan2k5/B-Bot)
---

> Built by [TEAM ZOD](https://github.com/sudarsan2k5/)



## 🌟 Experience

> ### Imagine talking to an AI that **sees you, understands how you feel**, and **responds with care** — all inside your browser.

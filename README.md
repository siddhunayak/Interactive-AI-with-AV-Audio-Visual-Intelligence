# **AI-Powered Voice and Vision Chatbot**

This project is an **AI-driven chatbot** designed to enhance **patient-doctor interactions** by integrating **advanced speech recognition** and **medical image analysis** capabilities.

## **Project Overview**

The **AI-Powered Voice and Vision Chatbot** bridges communication gaps in **healthcare** settings by:

- 🗣 **Voice Recognition**: Uses **OpenAI's Whisper** model for precise speech transcription.
- 🏥 **Visual Analysis**: Leverages **Meta’s Llama 3.2** multimodal model for medical image interpretation.
- 💬 **Human-Like Responses**: Generates **empathetic and natural** responses to patient inquiries.

## **Features**

✅ **Speech-to-Text (STT)**: Converts patient speech into text using Whisper.  
✅ **Image Analysis**: Processes and analyzes medical images using Llama 3.2.  
✅ **Text-to-Speech (TTS)**: Responds with natural-sounding speech via gTTS and ElevenLabs.  
✅ **User-Friendly Interface**: Built with **Gradio** for real-time interaction.  

## **Workflow Diagram**

![Process Flow](https://raw.githubusercontent.com/siddhunayak/Interactive-AI-with-AV-Audio-Visual-Intelligence/main/Process%20Flow.png)


---
## 🖼️ model Interface

![model Interface](https://raw.githubusercontent.com/siddhunayak/Interactive-AI-with-AV-Audio-Visual-Intelligence/main/Screenshot%202025-07-08%20082507.png)
---
🖼️ Application Preview
---
🌐 Click here to view the live app

[https://the-resume-refinery.onrender.com/](https://interactive-ai-with-av-audio-visual.onrender.com/)
---
## **Getting Started**

### **Prerequisites**

- **Python 3.8+**: Ensure Python is installed on your system.
- **Virtual Environment**: Recommended to manage dependencies.

### **Installation**

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/siddhunayak/Interactive-AI-with-AV-(Audio-Visual)-Intelligence.git

cd "Interactive-AI-with-AV-(Audio-Visual)-Intelligence"

```

#### 2️⃣ Set Up Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

#### 3️⃣ Install Dependencies

Run the following command to install all required dependencies:

```bash
pip install -r requirements.txt
```

#### 4️⃣ Set Up Environment Variables

Create a `.env` file in the project root directory and add the following content:

```bash
GROQ_API_KEY=your_groq_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
```

#### 5️⃣ Install FFmpeg (Required for Audio Processing)

FFmpeg is required for handling audio processing tasks. Install it based on your operating system:

- **Windows**:  
  Download FFmpeg from the [official website](https://ffmpeg.org/download.html), extract the files, and add the binary path to your **system PATH**.

- **macOS**:  
  Install FFmpeg using Homebrew:

  ```bash
  brew install ffmpeg
  ```

---

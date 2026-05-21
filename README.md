# Prompt-based-AI-Multimedia-Generator
Prompt-Based AI Multimedia Generator is an AI-powered educational multimedia generation system specially designed for kids and young learners. The application transforms simple text prompts into engaging multimedia content such as stories, AI-generated images, audio narration, and videos, making learning more interactive and enjoyable for children.


# 🎯 Prompt-Based AI Multimedia Generator

An AI-powered multimedia generation system developed during a **4-Month Internship in Artificial Intelligence with Cloud Computing at SupraMentr Technologies Pvt Ltd**.

This project generates complete multimedia content from a simple text prompt using Generative AI technologies. The system automatically creates stories, AI-generated images, audio narration, and combines them into a final video output.

---

# 🚀 Features

✅ Prompt-Based Story Generation
✅ AI Image Generation
✅ Text-to-Speech Audio Narration
✅ Automated Video Creation
✅ Streamlit-Based Interactive UI
✅ Real-Time Multimedia Processing
✅ End-to-End AI Automation

---

# 🛠️ Technologies Used

| Category             | Technologies                                 |
| -------------------- | -------------------------------------------- |
| Programming Language | Python                                       |
| Frontend             | Streamlit                                    |
| AI Models            | OpenAI GPT, DALL·E                           |
| Audio Processing     | gTTS                                         |
| Video Processing     | MoviePy, FFmpeg                              |
| Cloud & AI Domain    | Artificial Intelligence with Cloud Computing |

---

# 📌 Project Workflow

1️⃣ User enters a text prompt
2️⃣ AI generates story/script content
3️⃣ Images are generated for each scene
4️⃣ Text is converted into audio narration
5️⃣ Images and audio are combined into video
6️⃣ Final multimedia video is generated

---

# ⚙️ Steps to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone <your-github-repository-link>
```

Move into the project directory:

```bash
cd Prompt-Based-AI-Multimedia-Generator
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Required Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is unavailable:

```bash
pip install streamlit openai moviepy gtts pillow requests
```

---

## 4️⃣ Install FFmpeg

FFmpeg is required for video processing.

### Verify Installation

```bash
ffmpeg -version
```

---

## 5️⃣ Add API Key

Create a `.env` file in the root folder.

Example:

```env
OPENAI_API_KEY=your_api_key
```

---

## 6️⃣ Run the Streamlit Application

```bash
streamlit run app.py
```

After execution, open:

```bash
http://localhost:8501
```

in your browser.

---

# 📂 Project Structure

```text
Prompt-Based-AI-Multimedia-Generator/
│
├── app.py
├── requirements.txt
├── assets/
├── generated_images/
├── audio/
├── videos/
├── utils/
└── README.md
```

---

# 💡 Key Highlights

* Developed an AI-powered multimedia automation platform
* Implemented prompt engineering techniques for content generation
* Integrated Generative AI models for text and image creation
* Built an interactive frontend using Streamlit
* Automated complete multimedia pipeline for video generation

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Generative AI
* Prompt Engineering
* Cloud Computing
* AI Model Integration
* Multimedia Processing
* Real-Time AI Applications

---

# 🏢 Internship Details

| Field             | Details                                      |
| ----------------- | -------------------------------------------- |
| Company           | SupraMentr Technologies Pvt Ltd              |
| Internship Domain | Artificial Intelligence with Cloud Computing |
| Duration          | 4 Months                                     |

---

# 📷 Output

The system successfully generates:

✅ AI-generated stories
✅ AI-created images
✅ Audio narration
✅ Final multimedia videos

---

# 🔥 Future Enhancements

* Multi-language support
* AI voice cloning
* Background music generation
* Cloud deployment
* Real-time video editing
* Advanced AI video generation

---

# 🙌 Acknowledgement

Special thanks to the mentors and team at SupraMentr Technologies Pvt Ltd for their continuous guidance, support, and valuable learning opportunities throughout the internship journey.

---

# 🔖 Tags

`Artificial Intelligence` `Generative AI` `Python` `Streamlit` `OpenAI` `DALL·E` `MoviePy` `Prompt Engineering` `Cloud Computing` `AI Project` `Internship Project`

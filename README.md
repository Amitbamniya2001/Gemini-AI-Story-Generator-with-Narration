# 🎨 Gemini-AI-Story-Generator-with-images

A **Streamlit app** that generates and narrates stories from user-uploaded images.  
Upload 1–10 images, select a storytelling style, and let AI create a connected narrative with audio narration.  




---

## 🚀 Features  
- Upload and process **1–10 images**  
- Choose from multiple storytelling styles:  
  - Comedy  
  - Thriller (with a twist)  
  - Fairy Tale  
  - Sci-Fi  
  - Mystery (with solution reveal)  
  - Adventure  
  - Morale (with moral of the story)  
- AI-generated stories grounded in your uploaded images  
- Narration powered by **gTTS (Google Text-to-Speech)**  
- Interactive Streamlit UI showing:  
  - Uploaded images  
  - Generated story  
  - Story narration (audio)  

---

## 🤖 Models & Providers  
- **LLM:** Google Gemini API (`gemini-2.5-flash-lite`)  
- **Text-to-Speech:** gTTS  
- **Image Processing:** Pillow (PIL)  
- **UI:** Streamlit  

---
## ⚡ Quick Start  

Follow these steps to set up and run the app locally:  

### 1. Clone the repository  
```bash
git clone https://github.com/YOUR_USERNAME/ai-story-generator.git
cd ai-story-generator
```
### 2. Create and activate a virtual environment
```bash
# On Linux / Mac
python -m venv venv
source venv/bin/activate
```
```bash
# On Windows (PowerShell)
python -m venv venv
venv\Scripts\Activate.ps1
```

### 3.Install dependencies
```bash
pip install -r requirements.txt
```
### 4. Set environment variables
```bash
GITHUB_TOKEN_CHATGPT=your_token_here
```
### 5.Run the app
```bash
streamlit run app.p
```
#### 6.Now open the URL shown in the terminal (usually http://localhost:8501) in your browser.




##  Overview

**AI-Agent-02** is an intelligent app that helps you repurpose **YouTube videos into ready-to-publish social media content**. Whether you’re a content creator, educator, marketer, or founder — this tool can save you hours every week.

Just drop a YouTube video ID, select your platforms, and instantly get platform-specific content written by GPT-4o.

---

##  Features

-  Auto-fetch YouTube transcripts
-  AI agent using GPT-4o (via `openai-agents`)
-  Platform-specific writing style (LinkedIn, Instagram, Twitter)
-  Optional web search enrichment
-  Downloadable .txt files for each post
-  Streamlit UI for fast, local deployment

---

## ⚙ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/Nouman-wp/AI-Agent-02.git
cd AI-Agent-02
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add your OpenAI API Key

Create a `.env` file with:

```env
API_KEY=your_openai_api_key_here
```

### 4. Run the app

```bash
streamlit run app.py
```

---

## 🔍 Example Use Case

* YouTube Video ID: `OZ5OZZZ2cvk`
* Query: `Write a LinkedIn post and Instagram caption based on this video`
* Platforms: ✅ LinkedIn ✅ Instagram

**Output**: Two well-structured, audience-tailored posts ready to publish.

---

## 📂 Project Structure

```
AI-Agent-02/
├── agent.py               # Agent logic & transcript fetcher
├── app.py                 # Streamlit frontend
├── .env                   # API key (not included in repo)
├── requirements.txt       # Python packages
└── README.md              # You’re reading it
```

---

## ✨ Powered By

* [OpenAI GPT-4o](https://openai.com)
* [Streamlit](https://streamlit.io)
* [youtube\_transcript\_api](https://pypi.org/project/youtube-transcript-api/)
* [openai-agents](https://github.com/openai/openai-python)

---

## 📄 License

This project is open-source under the [MIT License](LICENSE)

---

> 💬 Feel free to open issues or contribute PRs to improve this tool!

```

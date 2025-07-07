# Text-api – AI Powered Text Summarizer ✨

A modern AI-powered text summarization tool that effortlessly condenses articles, blogs, research papers, and documents into clear, easy-to-read summaries.

---
### 📖 **Overview**
`Text-api` is a modern web application that automatically summarizes long-form text content into concise, readable summaries. The application allows users to input text directly or upload documents in various formats (TXT, PDF, DOCX). It leverages the DeepSeek-R1-Zero AI model through the OpenRouter API to generate high-quality summaries efficiently.

The application name `"TLDR" stands for "Too Long; Didn't Read"` - a common internet acronym that perfectly captures the application's purpose of condensing lengthy content into digestible summaries.

---

### 🚀 **Getting Started**

#### 1. **Clone the repository**

```bash
git clone (https://github.com/Tusharagrawal22-web/Text-api.git)
cd text-summarizer
```

#### 2. **Install dependencies**

```bash
npm install
```

#### 3. **Set up environment variables**

Create a `.env` file in the root directory and add your OpenRouter API key:

```
VITE_OPENROUTER_API_KEY=your_openrouter_api_key
```


#### 4. **Run the development server**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

### 🗂️ **Project Structure**

```
src/
  [App.jsx] -> Main app with routing, layout, and pages
  [main.jsx] -> Entry point, Chakra UI, router setup
  [index.css] -> Custom styles components

src/components/ 
    [Logo.jsx] -> SVG logo component
    [Loader.jsx] -> Loader/spinner for async actions
    [TextSummarizer.jsx] -> Summarizer component
```


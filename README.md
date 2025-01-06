<h1 align="center">ScireAI</h1>
<p align="center"><i>Empowering your research journey with intelligent AI assistance</i></p>
<p align="center">
  <img src="titleImage.png" alt="Scire AI Logo" width="700">
</p>

---

ScireAI is your intelligent research companion, streamlining your research process. Effortlessly upload PDF files, highlight any text you find unclear, and get instant AI-powered explanations—all seamlessly integrated into a single, user-friendly interface.

## Features

- **Term Lookup:** Highlight unclear text in your PDFs, right-click, and let the AI provide instant explanations.
- **Interactive AI Chat:** Engage with AI in a dedicated chat panel for effortless research support.
- **Frictionless and Intuitive:** Frictionless and intuitive, ScireAI simplifies research with effortless, seamless usability

## Usage
1. **Upload a PDF:** Click "Upload Your File" and select a PDF document.
2. **Highlight Text:**  Select any text you’d like to ask the AI for clarification.
3. **Query AI:** Right-click on the highlighted text and choose to query the AI. Responses will be displayed in the chat panel.

## Technologies Used

- **Frontend:**
  - React.js
  - @react-pdf-viewer/core
  - Tailwind CSS
- **LLMs**
  - Llama3-8b-8192 hosted on Groq
- **Hosting**
  - Vercel

## Installation

Follow the instructions below to set up Scire AI locally.

### Prerequisites

- Node.js (v16 or later)
- npm (v7 or later)

### Steps

1. Clone the repository:

```bash
   git clone git@github.com:unknown7703/scireai.git

   cd scireai

   npm install
```

2. Generate an LLM key from [Groq](https://groq.com/) and add the API key to the `.env` file in the root with the name `REACT_APP_GROQ_API_KEY` and reference it in your `src/api/groq.js` file.

3. Initialize Tailwind CSS with:
   
```bash
   npx tailwindcss init
```

4. Start your application on local:

```bash
   npm start
```



## Folder Structure

    Scire-AI/
    ├── public/
    ├── src/
    │   ├── assets/         
    │   ├── components/     
    │   ├── api/           
    │   ├── App.js          
    │   ├── index.js       
    ├── package.json
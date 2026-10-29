# Gen-Quiz: AI Document Quiz Generator & Study Platform

**Gen-Quiz** is an advanced AI-powered web platform that transforms uploaded study documents (**PDF**, **Word .docx**, **PowerPoint .pptx / .ppt**) into interactive, pedagogical quizzes and executive key summaries.

---

## 🚀 Key Features

### 1. Multi-Format Document Ingestion
- **PDF Documents (`.pdf`)**: Automatic text and page extraction powered by `pdfjs-dist`.
- **Microsoft Word (`.docx`)**: Clean document parsing powered by `mammoth`.
- **PowerPoint Slide Decks (`.pptx`, `.ppt`)**: Native XML slide text extraction across all presentation decks via `jszip`.
- **Text & Markdown (`.txt`, `.md`)**: Raw text ingestion.
- **Preloaded Sample Library**: 3 built-in academic sample documents (Computer Science / AI, Cellular Biology, World History) for instant 1-click testing.

### 2. High-Yield Topic Summaries
- **Executive Overview**: High-level synthetic paragraph summarizing the core thesis.
- **Key Concepts**: Bulleted list of critical takeaways and mechanisms.
- **Core Terminology & Definitions**: Flashcard-style definitions of essential subject terms.
- **Assessment Focus Areas**: Recommended conceptual zones for examination.
- **Export**: 1-click Markdown file download and clipboard copy.

### 3. Granular Quiz Customization
- **Complexity Levels**:
  - 🟢 **Easy**: Foundational definitions, direct factual recall, and clear contrasts.
  - 🔵 **Medium**: Applied concepts, process workflows, and comparative analysis.
  - 🟣 **Hard**: Multi-step deductive reasoning, edge cases, and subtle distractors.
- **Question Quantities**: 5, 10, 15, or 20 questions.
- **Per-Question Time Limits**: 15s, 30s, 45s, 60s, or Unlimited.
- **Total Quiz Duration Timer**: 3 min, 5 min, 10 min, 15 min, or Unlimited.

### 4. Interactive Quiz Taking & Immediate Wrong-Answer Explanations
- **Real-Time Dual Timers**:
  - Live progress countdown for the current question.
  - Total exam duration countdown timer with warning alerts.
- **Instant Explanations on Wrong Answers**:
  - Whenever an incorrect choice is selected (or when a question times out), the user's choice is highlighted in red, the correct choice is highlighted in green, and an **in-depth explanation card** expands instantly.
  - Explains the misconception of the incorrect choice.
  - Explains why the correct answer is right.
  - Highlights the direct **source context quote** from the uploaded document.
- **Synthesized Audio Effects**: Web Audio API chimes for correct answers, gentle buzz for errors, timeout blips, and victory fanfare.

### 5. Detailed Results & Performance Analytics
- **Performance Gauge**: Final percentage score with achievement badges (*Mastery*, *Proficient*, *Foundational*, *Needs Review*).
- **Missed Questions Drill**: 1-click button to **"Retry Missed Questions Only"** to solidify weak spots.
- **Filterable Question Review**: Filter by *All*, *Incorrect Only*, or *Correct Only*.
- **Comprehensive Report Export**: Download full plain-text / Markdown quiz audit reports.

### 6. Dual-Engine Intelligence
- **Google Gemini 2.5 Flash**: Connect with a free API key from [Google AI Studio](https://aistudio.google.com).
- **Built-in Local Heuristic AI**: Works 100% offline without requiring any API key or subscription.

---

## 🛠️ Quick Start

```bash
# 1. Install dependencies (if not already installed)
npm install

# 2. Start the development server
npm run dev

# 3. Build for production
npm run build

# 4. Preview production build
npm run preview
```

Open your browser at `http://localhost:3000` to launch Gen-Quiz!


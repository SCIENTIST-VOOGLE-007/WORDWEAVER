# WORDWEAVER
"WordWeaver: An intelligent NLP-based tool that weaves together accurate spell corrections, context-aware keyword suggestions, and part-of-speech categorizations to enhance content creation, search optimization, and user experience. Built for both text and speech inputs, WordWeaver transforms how you interact with language."

# WordWeaver: Your Companion for Seamless Language Processing

## 🚀 Overview
**WordWeaver** is your go-to tool for simplifying the way you interact with language. Whether you're typing or speaking, WordWeaver effortlessly corrects spelling errors, suggests relevant keywords, and organizes results based on grammar. It’s designed to enhance productivity and creativity, making language tools smarter and more accessible.

---

## 🎯 Features
- **Spelling Correction**: Instantly fixes spelling mistakes using a smart corpus-based algorithm.
- **Keyword Suggestions**: Offers context-aware keyword ideas tailored to your input.
- **POS Categorization**: Helps you understand grammatical usage by categorizing results (Nouns, Verbs, etc.).
- **Speech-to-Text**: Converts your voice into actionable text for hands-free usage.

---

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Framework**: Streamlit
- **NLP Libraries**: Hugging Face Transformers, NLTK
- **Speech Recognition**: Google Speech API, SpeechRecognition package
- **Utilities**: Autocorrect, `re`, `collections`
- **Corpus Data**: A text corpus file (`big.txt`) used for probability calculations and corrections.

---

## 📐 System Design
### Architecture:
1. **User Input**:
   - Text Input: For typing-based queries.
   - Voice Input: Voice commands transcribed into text.
2. **Spell Checker**:
   - Identifies and suggests corrections based on word-level edits.
3. **Keyword Suggestion**:
   - Analyzes input to generate meaningful, context-specific keywords.
4. **POS Categorization**:
   - Classifies results grammatically using pre-trained NLP models.

### Modules:
- **AutoCorrect**: Detects and fixes spelling errors.
- **Keyword Search**: Fetches relevant contexts from a text corpus.
- **POS Tagger**: Organizes results by grammatical categories.

---

## 🖥️ Installation & Usage
### Prerequisites:
- Python 3.8 or above
- Required libraries:
pip install streamlit transformers nltk SpeechRecognition autocorrect



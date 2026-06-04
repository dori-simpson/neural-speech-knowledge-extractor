# Neural Speech-Driven Knowledge Extractor (NSKE) 🎙️➡️🧠

An advanced AI pipeline engineered to process raw conversational audio, perform automated speech recognition (ASR), and execute entity-relation extraction to transform unstructured speech into structured, queryable knowledge graphs or semantic insights.

---

## 🚀 Core Features

* **Audio-to-Text Pipeline:** High-accuracy neural speech transcription handling variable audio quality and noise thresholds.
* **Semantic Triage & NLP:** Custom tokenization, part-of-speech (POS) tagging, and named entity recognition (NER) optimized for extracting actionable facts from dialogue.
* **Knowledge Synthesizer:** Maps discovered entities and their programmatic relationships into clean schemas (JSON/Graph ready) for downstream business intelligence.

---

## 🛠️ Tech Stack & Architecture

* **Languages & Core:** Python, Bash
* **Speech & NLP Processing:** Hugging Face Transformers, Whisper / Wav2Vec2 models, Spacy
* **Data & Math Foundations:** NumPy, Pandas, Scikit-Learn
* **Infrastructure Target:** Designed for containerized deployment (Docker) and scalable cloud inference pipelines (AWS EC2 / S3 storage triggers).

---

## 📦 Installation & Setup

Ensure you have Python 3.10+ installed along with `ffmpeg` for system-level audio processing.

```bash
# Clone the repository
git clone [https://github.com/dori-simpson/Neural-Speech-Driven-Knowledge-Extractor-NSKE-.git](https://github.com/dori-simpson/Neural-Speech-Driven-Knowledge-Extractor-NSKE-.git)
cd Neural-Speech-Driven-Knowledge-Extractor-NSKE-

# Set up virtual environment
python3 -m venv venv
source venv/bin/activate

# Install required dependencies
pip install -r requirements.txt

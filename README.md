# ml_meme_genedu

# 🤖 LMLM: Learning Machine Learning Concept through educational Memes

New way of learning ML fundamentals in the most Gen Z way possible 🎉

## 🚀 Features
- Search for ML concepts → get a meme + tooltip explanation
- Random meme feed for casual learning
- Validated outputs: memes must match core ML concepts and explanation
- Seed knowledge base + generated expansions

## 🛠️ Tech Stack
- **Backend:** FastAPI + OpenAI API + Pillow (image rendering)
- **Frontend:** React / Next.js
- **Storage:** JSON KB + local images
- **Deployment:** Docker + Vercel/Render

## 📂 Project Structure
See [docs/architecture.md](docs/architecture.md)

## 🏗️ Setup
### Backend
```bash
cd backend
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # add your OPENAI_API_KEY
uvicorn app.main:app --reload

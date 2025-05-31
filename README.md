# 🎤 Artist Fingerprint

**Artist Fingerprint** is a data-driven tool that analyzes a music artist’s lyrical style using their top songs. It combines APIs, NLP, topic modeling, and AI-powered summarization to generate a visual and textual "fingerprint" of an artist’s creative voice.

---

## Features

-  etrieves top songs using the **Genius** and **Spotify** APIs
- Extracts lyrics via **web scraping** and filters based on primary artist
- Computes stylistic **metrics**: 
  - Lexical diversity
  - Average sentiment
  - POS & verb tense distributions
- Identifies top **lyrical themes** using clustering and OpenAI-powered naming
- Generates a **natural-language summary** of the artist’s style
- Visualizes results with pie charts, word clouds, and clean text summaries

---

## Tools & Technologies

- **Python** · `requests` · `BeautifulSoup`
- **NLP**: `spaCy`, `NLTK`, `TextBlob`
- **Data Viz**: `matplotlib`, `seaborn`, `wordcloud`
- **APIs**: Genius API, Spotify API, OpenAI GPT
- **Other**: `scikit-learn`, `Jupyter`, `Counter`, `.env` config

---

## Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/artist-fingerprint.git
cd artist-fingerprint
```

### 2. Install dependencies:
```bash
pip install -r requirements.txt
```

### 3. Add your API keys:
Create a ```.env``` file and fill in your credentials
```
GENIUS_API_TOKEN=your_genius_key
SPOTIFY_CLIENT_ID=your_spotify_id
SPOTIFY_CLIENT_SECRET=your_spotify_secret
OPENAI_API_KEY=your_openai_key
```

### 4. Run artist_profile.ipynb

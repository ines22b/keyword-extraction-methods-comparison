# keyword-extraction-methods-comparison

# Keyword Extraction Methods Comparison

> Customizable analysis of keyword extraction methods (TF-IDF, RAKE, FastText, Word2Vec, hybrids) with web scraping, text preprocessing, and visual comparisons. Works on any dataset of URLs, tested on 500 computer science abstracts.

## 🚀 Features

- Implementation of several keyword extraction methods:
  - TF-IDF
  - RAKE
  - Word2Vec-based extraction
  - FastText-based extraction
  - Hybrid approaches (e.g., TF-IDF + Word2Vec, TF-IDF + FastText)
- Extensive experimentation and evaluation
- Visual comparison of keyword relevance and ranking
- Statistical and graphical analysis of method performance
- Web scraping of texts from URLs in the dataset
- Preprocessing and cleaning of raw text data
- Ready-to-use for academic or applied NLP research

## 📁 Files

- `Comparaison_des_Méthodes_Extraction_de_Mots_Clés_VERSION_FINALE_Computer_Sciences_Dataset.ipynb` – main notebook with full implementation and comparison
- `requirements.txt` – required packages to run the notebook

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/ines22b/keyword-extraction-methods-comparison.git
cd keyword-extraction-methods-comparison
```

2. Install the dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook
```

## 📊 Usage

1. Open the notebook.
2. Follow each section to explore the different keyword extraction techniques.
3. Run the evaluation and comparison cells to view performance metrics and visualizations.
4. Analyze which technique or combination gives the best result for your context.

## 🌐 Data Processing

- Extracted texts using web scraping from URLs present in the dataset
- Applied custom text preprocessing and cleaning techniques before keyword extraction
- Can be applied to any custom dataset of links, not limited to the original sample

## 🧠 Techniques Compared

- RAKE (Rapid Automatic Keyword Extraction)
- TF-IDF (Term Frequency–Inverse Document Frequency)
- Word2Vec (Semantic vector-based)
- FastText (Subword-aware embeddings)
- Hybrid combinations like:
  - TF-IDF + Word2Vec
  - TF-IDF + FastText

## 🙋 Author

Developed by [Inas Boudjeda]. Contributions and collaborations are welcome.

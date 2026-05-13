# Player-Reception-and-Cultural-Identity-A-Study-of-Chinese-Steam-Reviews-of-Firework

# Firework Steam Review Analysis Repository

This repository contains the anonymized research materials, preprocessing outputs, and analysis scripts associated with the master’s thesis:

*Player-Reception-and-Cultural-Identity-A-Study-of-Chinese-Steam-Reviews-of-Firework*

The project investigates how Chinese players interpret locally grounded narrative elements and construct cultural identity through Steam review discourse surrounding the Chinese indie game *Firework* (《烟火》).

---

# Repository Structure

| File Name | Description |
|---|---|
| `firework_raw.xlsx` | Raw manually collected review data with metadata. Player IDs and raw text are excluded for privacy. |
| `corpus_clean_text.txt` | Cleaned and preprocessed review corpus used for distant reading analysis |
| `word_freq_raw.csv` | Raw word frequency table before stopword filtering |
| `cn_stopwords.txt` | Initial Chinese stopword list |
| `cn_stopwords_final.txt` | Final optimized stopword list used in analysis |
| `word_freq_final.csv` | Final word frequency table after preprocessing |
| `bigram_freq.csv` | Bigram frequency table |
| `wordcloud.png` | Chinese word cloud visualization |
| `wordcloud_translation.png` | English-translated word cloud visualization |
| `data_log.pdf` | Research log documenting data collection and preprocessing procedures (Chinese) |
| `close_reading_sample.pdf` | 38 sample for close reading(in Chinese). Texts are lightly paraphrased to prevent traceability. |
| `firework_analysis.ipynb` | Jupyter Notebook containing preprocessing scripts and analysis code |

---

# Ethical Notice

This repository follows the ethical guidelines for internet research proposed by the Association of Internet Researchers (AoIR).

The original Steam reviews analyzed in this study are publicly accessible platform data. However, to minimize potential traceability and protect user privacy:

- Player IDs, usernames, and profile information are not included.
- Raw review texts are not publicly archived.
- Sensitive or potentially identifiable quotations have been paraphrased where necessary.
- The close reading sample preserves analytical meaning while reducing direct traceability to individual users.

This repository is intended to support methodological transparency and partial reproducibility rather than full reconstruction of the original dataset.

---

# Research Environment

Text preprocessing and corpus analysis were conducted in Python using the Jupyter Notebook environment provided through Anaconda.

Main analysis procedures include:

- Text preprocessing
- Chinese word segmentation
- Word frequency analysis
- Bigram analysis
- Word cloud visualization

---

# License

This repository is shared for academic and non-commercial research purposes only.

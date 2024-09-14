# PATH OF ABAI (PART I & PART II) TEXT ANALYSIS

---

## Project Overview:

The Path of Abai Text Analysis project focuses on analyzing translations of the first 2 parts of the epic Kazakh novel "Path of Abai" by Mukhtar Auezov in three different languages: Russian (ru), English (eng), and Kazakh (kaz). The project delves into various aspects of the translated texts, including linguistic features, sentiment, and more.

---

## Project Structure:

- **dataset:** This folder contains the translated texts in three languages (ru, eng, kaz).

- **preprocessing:** This folder contains code for text preprocessing and OCR.
  
- **analysis:** This folder contains separate Jupyter Notebooks (.ipynb) for each type of analysis performed:
    
    - **Collocation Analysis.ipynb:** This notebook examines collocations, or significant word combinations, within the translated texts.
    
    - **Vocabulary Richness.ipynb:** This notebook assesses the richness and diversity of vocabulary used in each translation.
    
    - **Sentiment Analysis.ipynb:** This notebook performs sentiment analysis to evaluate the overall sentiment of each translation.
    
    - **Emotion Analysis.ipynb:** This notebook performs emotion analysis to evaluate the overall emotions of each translation.

---

## Dataset Structure:

- **russian json** 
```json
{
    "part1": {
        "возвращение": {...},
        "в_вихре": {...},
        "в_пути": {...},
        "в_дебрях": {...},
        "по_предгорьям": {...},
        "на_подъеме": {...},
        "в_вышине": {...},
    },
    "part2": {
        "перед_бродом": {...},
        "на_жайляу": {...},
        "взгорьями": {...},
        "по_рытвинам": {...},
        "на_переволе": {...},
        "на_распутье": {...},
        "эпилог": {...},
    }
}
```
- **english json**
```json
{
    "part1": {
        "the_home_coming": {...},
        "the_whirlwind": {...},
        "on_the_road": {...},
        "in_the_thickets": {...},
        "along_the_foothills": {...},
        "the_ascent": {...},
        "in_the_heights": {...},
    },
    "part2": {
        "the_ford": {...},
        "the_foothills": {...},
        "over_the_ruts": {...},
        "through_the_ruts": {...},
        "at_the_crossroads": {...},
        "at_the_summit": {...},
        "epilogue": {...},
    }
}
```
- **kazakh json**
```json
{
    "part1": {
        "kaitkanda": {...},
        "kat_kabatta": {...},
        "zholda": {...},
        "shatyrmanda": {...},
        "bel_beleste": {...},
        "orde": {...},
        "kyiada": {...},
    },
    "part2": {
        "taigakta": {...},
        "zhailauda": {...},
        "enyste": {...},
        "okapta": {...},
        "asuda": {...},
        "tarauda": {...},
        "byikte": {...},
        "epilogue": {...},
    }
}
```

---

## Contributing:

Contributions to the project are welcome! If you have ideas for additional analyses or improvements to the existing code, feel free to fork the repository, make your changes, and submit a pull request.

---

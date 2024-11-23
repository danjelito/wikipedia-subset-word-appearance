# Wikipedia Subset Word Frequency Analysis  

This project explores the application of the **80/20 rule (Pareto Principle)** to the word frequencies in a subset of Wikipedia. Specifically, the goal is to determine whether 20% of the unique words account for 80% of all word occurrences.  

## Project Overview  
- **Objective**: Verify if the Pareto Principle applies to word usage in the dataset.  
- **Approach**: Analyze word frequencies and calculate the contribution of the most frequent words to the overall word count.  
- **Key Insight**: If the principle holds, a small percentage of unique words will dominate the text composition.  

## Data Source  
The dataset used for this analysis is a subset of Wikipedia in simple English:  
[Plain Text Wikipedia (Simple English) on Kaggle](https://www.kaggle.com/datasets/ffatty/plain-text-wikipedia-simpleenglish)  

## Methodology  
1. Preprocessed the text data to remove stopwords (e.g., "a," "an," "the") that do not provide meaningful information.  
2. Counted the occurrences of each unique word.  
3. Calculated the cumulative contribution of unique words to the total word count.  
4. Visualized the results to check for the 80/20 pattern.  
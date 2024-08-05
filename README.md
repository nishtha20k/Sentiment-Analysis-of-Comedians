## Project Overview
This project aims to perform a comprehensive analysis of comedian transcripts using Natural Language Processing (NLP) techniques. The primary objectives are to analyze the sentiment, topics, and patterns in comedians' styles and generate new comedic text based on the analyzed data. The project also explores similarities and differences in comedic styles, offering insights into the art of comedy through the lens of data science.

## Project Structure

### 1. Data Loading
-  Transcripts were sourced from "Scraps from the Loft."
-  Web scraping was performed using `requests` and `BeautifulSoup` libraries to extract the necessary data.

### 2. Data Cleaning
-  To prepare the raw transcripts for analysis by removing noise and standardizing the text.
- 
  - Removal of stop words, punctuation, and digits.
  - Exclusion of unnecessary characters and symbols.
  - Text normalization (lowercasing etc).

### 3. Data Organization
-  To structure the cleaned data into a standard format for analysis.
- `pandas` was used to organize the data into DataFrames for easier manipulation and analysis.

### 4. Exploratory Data Analysis (EDA)
- To explore and visualize the data, identifying key trends and patterns in the comedians' styles.
- `matplotlib` and `pandas` for plotting and data visualization.

### 5. Sentiment Analysis
- To determine the polarity (positive/negative), subjectivity, and emotional scores of the transcripts.
- `nltk` and other NLP libraries were used to calculate sentiment scores.

### 6. Topic Modeling
- To identify recurring themes and topics in the comedians' material.
- Technique like Latent Dirichlet Allocation (LDA) is applied for topic extraction.

### 7. Text Generation
- To generate new text based on the analyzed data, mimicking the style of the comedians.

## Conclusions
- The project reveals key insights into the styles of different comedians by analyzing their transcripts.
- Sentiment analysis and topic modeling show unique patterns in comedic content, which could be used to generate new material.
- This project provides a novel intersection of data science and comedy, offering a deeper understanding of humor through data-driven techniques.

## Future Work
- Expand the dataset to include more comedians.
- Improve the text generation model for more coherent and humorous content.
- Explore additional NLP techniques to enhance the analysis.


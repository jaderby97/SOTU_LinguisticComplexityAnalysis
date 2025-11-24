# SOTU_LinguisticComplexityAnalysis
This project analyzes the **linguistic complexity of U.S. Presidents’ State of the Union (SOTU) speeches** from the 2000s using natural language processing (NLP).  
The goal is to explore how language sophistication varies between presidents and changes over time.

## Project Overview
The analysis focuses on gathering speech transcripts, processing the text, and computing multiple linguistic complexity metrics to identify trends in presidential communication styles.

Key steps included:
- **Web-scraping** official SOTU transcripts from online archives  
- Cleaning and preprocessing text data (tokenization, stopword removal, etc.)  
- Calculating linguistic metrics such as:
  - Average sentence length  
  - Lexical diversity (unique word ratio)  
  - Readability scores (Flesch-Kincaid, Gunning Fog Index)  
- Comparing results across different presidents and time periods  
- Visualizing complexity trends with plots and summary tables  

## Results & Insights
- Linguistic complexity varied notably between presidents, often correlating with shifts in tone, audience, and political context.  
- Readability scores indicated a gradual simplification of speech language over the 2000s.  
- Demonstrates how quantitative NLP techniques can reveal communication trends in political discourse.

## Tools & Libraries
- Python  
- pandas, numpy  
- BeautifulSoup (for web-scraping)  
- nltk or spaCy (for text processing)  
- matplotlib, seaborn  

## Skills Demonstrated
- Web-scraping and data collection  
- Natural language processing (NLP)  
- Readability and linguistic analysis  
- Data visualization and interpretation  

## Repository Structure
- `Linguistic Complexity Analysis.ipynb` – main analysis notebook  
- `SOTU_archives` – link to the The American Presidency Project website, UC Santa Barbara   
- `README.md` – project overview and documentation

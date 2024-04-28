

---

## YouTube Comments Analysis

This Python script for scraping and analyzing comments from a YouTube video. The script utilizes Selenium to simulate user interactions, collects comments dynamically, preprocesses text, performs sentiment analysis, generates word clouds, clusters comments, and summarizes the findings.

### Features:

- **Scraping Comments**: Utilizes Selenium to scrape comments from a YouTube video by automating user interactions such as scrolling and collecting comments.

- **Text Preprocessing**: Cleans and preprocesses the text data by removing unwanted symbols, numbers, and stopwords, and tokenizing the text for further analysis.

- **Word Cloud Generation**: Generates word clouds to visually represent the frequency of words in the comments. Separate word clouds are created for positive and negative sentiments using predefined lists.

- **Sentiment Analysis**: Employs the VADER sentiment analysis tool to assess the sentiment of each comment and categorize them as positive, negative, or neutral.

- **Clustering**: Utilizes KMeans clustering to group similar comments together based on TF-IDF representations, facilitating thematic analysis.

- **Text Summarization**: Generates a summary of all comments using the PageRank algorithm, providing a concise overview of the key themes and sentiments expressed by users.

### Usage:

1. Clone the repository.
2. Install the required libraries (`selenium`, `numpy`, `wordcloud`, etc.).
3. Update the YouTube video URL in the script.
4. Run the Python script to scrape and analyze comments from the specified video.
5. Explore the generated visualizations and insights to understand viewer feedback effectively.

### Contributions:

Contributions are welcome! Feel free to submit pull requests or open issues for any enhancements, bug fixes, or additional features.

### License:

This project is licensed under the [MIT License](LICENSE).

---

This readme provides an overview of the project, its features, usage instructions, contribution guidelines, and licensing information, enabling users to understand and utilize the YouTube comments analysis tool effectively.

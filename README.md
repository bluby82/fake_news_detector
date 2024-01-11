this project uses Term Frequency-Inverse Document Frequency (TfidfVectorizer)
1. low frequency words will give high IDF score and therefore classified as red flags in news
2. high frequency words will give high TF score and is a green flag in the simplest means

some words like "crisis", "urgent", "breaking" or unusual sentences appear often in fake news and gives high IDF score

negative:
some real news might have those words aswell

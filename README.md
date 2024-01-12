This project uses Term Frequency-Inverse Document Frequency (TfidfVectorizer)
1. Low frequency words will give high IDF score and therefore classified as red flags in news
2. High frequency words will give high TF score and is a green flag in the simplest means

Some words like "crisis", "urgent", "breaking" or unusual sentences appear often in fake news and gives high IDF score

Negative:
Some real news might have those words aswell
Need larga ammount of data

1.	Introduction  
The spread of fake news is a major challenge in the digital world, threatening the reliability of information and public trust. . This report presents a semantic classification approach using Word2Vec embeddings and supervised machine learning to detect fake news automatically. The model focuses on understanding the meaning of news text beyond simple word patterns, allowing for more accurate detection.

2. Business Objective
The goal is to construct an automated system that classifies news articles as either true or fake based on their semantic content. This helps combat misinformation by enabling quicker, scalable, and consistent fake news identification, reducing manual verification efforts, and improving public trust in digital media.

3. Problem Statement
Distinguishing fake from real news is challenging due to the growing volume of articles and the subtlety of misinformation patterns. Traditional manual checks are slow and error-prone. The problem is thus a binary classification challenge that requires leveraging textual semantics to flag fake news early and efficiently.

Performance Summary Table

<img width="940" height="284" alt="image" src="https://github.com/user-attachments/assets/f5b4c30e-68a4-4d8b-a36f-0b493401180b" />

Outcome:

The Random Forest model was found to be the most effective for detecting fake news, achieving ~82% accuracy. It handled both true and fake news more robustly compared to Logistic Regression and Decision Tree, making it the recommended model for deployment.
Conclusion:
•	This assignment implemented a semantic classification approach to detect fake news using Word2Vec embeddings and supervised machine learning algorithms. The systematic process began with thorough data preparation and cleaning, followed by detailed exploratory data analysis that revealed distinct lexical and contextual differences between true and fake news articles.
•	The Word2Vec model effectively captured the semantic relationships between words, providing meaningful dense vector representations used to train classification models. Logistic Regression served as a useful baseline, while Decision Tree models captured more complex patterns but suffered from overfitting. The Random Forest classifier, as an ensemble method, achieved the highest accuracy (~82%) and balanced precision and recall, making it the most robust model for this task.

•	The semantic classification methodology demonstrated its effectiveness in distinguishing subtle differences in textual meaning beyond simple lexical matching. This approach is scalable and adaptable for automated fake news detection, aiding efforts to combat misinformation and maintain the integrity of information dissemination.


•	Future enhancements could include training custom embeddings on domain-specific data, integrating advanced transformer-based NLP models, and continuous retraining to adapt to evolving fake news patterns. Overall, this work showcases a promising direction for leveraging semantic understanding in real-world text classification problems.


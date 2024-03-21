Here are the packages I have imported：
pandas
numpy
json
torch
transformers
sklearn
tensorflow
re
concurrent.futures
time
neo4j


1. I initiated the process by employing three distinct models: the Bert-Base-Chinese Model, the BERT-Base-Chinese-Finetuning-Financial-News-Sentiment-V2 Model, and the Directly Matching model, with the objective of filtering A-share companies from within the news dataset.

2. Simultaneously, during the utilization of the BERT-Base-Chinese-Finetuning-Financial-News-Sentiment-V2 Model, I performed sentiment analysis on the news content.

3. Following this, I imported the content from the KnowledgeGraph file, utilizing it to generate a comprehensive knowledge graph.

4. In the final phase, I generated a list of company names associated with implicit positive and negative relationships for each news article, designating them as Implicit_Positive_Company and Implicit_Negative_Company, respectively.
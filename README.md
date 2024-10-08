# Fine-Tunning-pre-trained-model-for-twitter-sentiment-analysis

I recently worked on a project that involved fine-tuning pre-trained models on a Twitter sentiment dataset.

𝗦𝘁𝗲𝗽𝘀 𝗜𝗻𝘃𝗼𝗹𝘃𝗲𝗱:
𝗗𝗮𝘁𝗮 𝗣𝗿𝗲𝗽𝗮𝗿𝗮𝘁𝗶𝗼𝗻: Leveraged the "mteb/tweet_sentiment_extraction" dataset for training and evaluation from hugging face.

𝗧𝗼𝗸𝗲𝗻𝗶𝘇𝗮𝘁𝗶𝗼𝗻: Employed AutoTokenizer for both models to tokenize the tweets effectively, ensuring input consistency.

𝗠𝗼𝗱𝗲𝗹 𝗙𝗶𝗻𝗲-𝗧𝘂𝗻𝗶𝗻𝗴:
𝗠𝗶𝗻𝗶𝗟𝗠-𝗟𝟭𝟮-𝗛𝟯𝟴𝟰-𝘂𝗻𝗰𝗮𝘀𝗲𝗱: Fine-tuned with a focus on optimizing for a 3-label classification (Negative, Neutral, Positive).
𝗗𝗲𝗕𝗘𝗥𝗧𝗮-𝗯𝗮𝘀𝗲-𝗺𝗻𝗹𝗶: Similarly fine-tuned to enhance sentiment classification capabilities.

𝗧𝗿𝗮𝗶𝗻𝗶𝗻𝗴: Configured training with a learning rate of 2e-5 over two epochs, incorporating strategies like weight decay and evaluation at each epoch to ensure robust model performance.

𝗘𝘃𝗮𝗹𝘂𝗮𝘁𝗶𝗼𝗻: Used an accuracy metric to validate model predictions against true labels, ensuring model reliability.

𝗗𝗲𝗕𝗘𝗥𝗧𝗮-𝗯𝗮𝘀𝗲-𝗺𝗻𝗹𝗶 was chosen due to its high accuracy in making predictions and returning precise results.

𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁: Deployed the fine-tuned models on Hugging Face Hub for public use. Sentiment analysis pipelines were created to demonstrate the models' capabilities in real-world sentiment detection.

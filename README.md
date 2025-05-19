This notebook focuses on the challenging task of need classification. Unlike sentiment analysis, which typically categorizes text as positive or negative, need classification involves a more nuanced understanding of human psychology, as needs are often implicit, context-dependent, and semantically nuanced in nature.

For this project, we leverage the theory and the dataset provided by Alharthi et al, 2017, "A Dataset for Psychological Human Needs Detection from Social Networks". The dataset serves as the foundation for our classification task.

To address the complexities of need classification, we employ a two-stage approach:

1) Prompt Engineering with Google’s LLMs: Using Google’s language models for few-shot and zero-shot learning to experiment with need classification.

2) Neural Network Training with Embeddings: Utilizing Google’s text-embedding-004 API to generate embeddings, which are then used to train a neural network to improve need classification.

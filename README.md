# Deep learning Semantic Search Engine
Search engines powered by natural language understanding([NLU](https://en.wikipedia.org/wiki/Natural-language_understanding)) that demonstrates the potential of using KNN with Amazon Elasticsearch Service compared to the traditional  Amazon Elasticsearch Service ranking method. Amazon ES offers KNN search, which can enhance search in use cases such as product recommendations, fraud detection, and image, video, and some specific semantic scenarios like document and query similarity. With the use of [cosine similarity](https://en.wikipedia.org/wiki/Cosine_similarity), you can measure the orientation between two vectors, which makes it the ideal choice for some specific semantic search applications. With AWS architecture you are able to build enterprise-grade search engine with enhanced KNN ranking, with high availability and performance.

## How does it Work??
We take a pre-trained BERT model(distilbert-base-nli-stsb-mean-tokens) from [Sentence-Transformers](https://github.com/UKPLab/sentence-transformers) to generate feature vectors(aka. [word embeddings](https://en.wikipedia.org/wiki/Word_embedding)) of each description of book corpus and store them as a KNN index in an Amazon ES domain.

## Pre-trained model full docs
- [Sentence-Transformers](https://www.sbert.net/)

## Technology
- [pre-trained BERT model](https://www.sbert.net/docs/pretrained_models.html#choosing-the-right-model)
- [Amazon SageMaker](https://aws.amazon.com/sagemaker/)
- [AWS Lambda](https://aws.amazon.com/lambda/)
- [Amazon Elasticsearch Service-version 7.7](https://aws.amazon.com/elasticsearch-service/)
- [AWS Cloudformation](https://aws.amazon.com/cloudformation/)
- [AWS S3](https://aws.amazon.com/s3/)
- [PyTorch](https://pytorch.org/get-started/locally/)
- [Python-Python 3.6 or higher](https://www.python.org/)

## AWS Cost
- (TDB)

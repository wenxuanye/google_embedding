# Google Universal Image Embedding


Image representations are a critical building block of computer vision applications. Traditionally, research on image embedding learning has been conducted with a focus on per-domain models. Generally, papers propose generic embedding learning techniques which are applied to different domains separately, rather than developing generic embedding models which could be applied to all domains combined.

In this competition, the developed models are expected to retrieve relevant database images to a given query image (ie, the model should retrieve database images containing the same object as the query). The images in our dataset comprise a variety of object types, such as apparel, artwork, landmarks, furniture, packaged goods, among others.

## Getting Started
Run the ```google_embedding_Train.ipynb``` under Colab Tpu enviroment.
# Data collection

Since the kaggle doesn't provide any training datasets, and it just gives a description about the distribution of the testing datasets which is shown in [testimage]  Based on the distribution, some players collected the relative datasets such as the Imagenet1k, Deepfashion, Products10k, Google-landmark and Omnibenchmark and then upload them to the kaggle website publicly. Since the total dataset is so huge ($21$G), I transformed the datasets into tfrecord format file (simple format for storing a sequence of binary
![testimage](img/test_dataset.png)
<!-- show img -->
ssdadwqew
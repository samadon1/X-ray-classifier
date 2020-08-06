# X-ray-classifier
One may have pneumonia and not know it. Physicians call this walking pneumonia. Common causes include bacteria, viruses and fungi. The infection causes inflammation in the air sacs in your lungs, which are called alveoli. The alveoli fill with fluid or pus, making it difficult to breathe. A chest x ray is the best test for diagnosing pneumonia
This tutorial will expound the complete pipeline from loading data to predicting whether an x-ray scan shows presence of pneumonia.

The dataset we'll be using is made available by kaggle [here](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) .The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal). After uncompressing it, notice that there are way more images that are classified as pneumonia than normal. This shows that we have a class imbalance in our data.

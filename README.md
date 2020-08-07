# **MNIST Convolutional Neural Network (CNN)**

**Fastai Library or API**
- [Fast.ai](https://www.fast.ai/about/) is the first deep learning library to provide a single consistent interface to all the most commonly used deep learning applications for vision, text, tabular data, time series, and collaborative filtering.
- [Fast.ai](https://www.fast.ai/about/) is a deep learning library which provides practitioners with high-level components that can quickly and easily provide state-of-the-art results in standard deep learning domains, and provides researchers with low-level components that can be mixed and matched to build new approaches.

**MNIST Database**
- The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. It was created by "re-mixing" the samples from NIST's original datasets.

**Convolutional Neural Network**
- In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.

**Preparing the Model**
- I have used [Fastai](https://www.fast.ai/about/) API to train the Model. It seems quite challenging to understand the code if you have never encountered with Fast.ai API before.
One important note for anyone who has never used Fastai API before is to go through [Fastai Documentation](https://docs.fast.ai/). And if you are using Fastai in Jupyter Notebook then you can use doc(function_name) to get the documentation instantly.

**Dataset**
- Fastai has its own [Dataset](https://docs.fast.ai/datasets.html).I have used [Fastai MNIST Dataset](https://course.fast.ai/datasets) using the following lines of codes:

```javascript
untar_data(URLs.MNIST)
```

**Observing the Dataset**
- The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. It was created by "re-mixing" the samples from NIST's original datasets.

![Image](https://res.cloudinary.com/dge89aqpc/image/upload/v1596632331/MNI_syaldn.png)

**Convolutional Neural Network**
- In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.

- Simple Convolutional Neural Network used in this MNIST Poject:

![Image](https://res.cloudinary.com/dge89aqpc/image/upload/v1596632586/Conv_rh520d.png)

- Using **Fastai API** to train the Model

```javascript
Learner(data, model, loss_func=nn.CrossEntropyLoss(), metrics=accuracy)
```
**Snapshot of Accuracy Score:**
- **Fastai** is so powerful as the accuracy score in MNIST is about 99%

![Image](https://res.cloudinary.com/dge89aqpc/image/upload/v1596819121/mnis_ngdefj.png)

# BMD Deep Learning Projects
In proposed open protocol, the sensor’s raw data streams, de-identified on distributed IPFS file storage network, can be made available to community of BMD token holders and developers, who can utilize various machine learning and deep learning algorithms frameworks such as TensorFlow, PyTorch, CNTK, and MXNet to more efficiently refine accuracy not only on static, old historical data, but on constantly generated new live data.

Read more on our [whitepaper](https://www.slideshare.net/secret/4CGbQSZ5xrHU6w) page 15.

## Data Collection and Sourcing
When it comes to datasets and data source, data collection is always a challenging part especially when it comes to opens source datasets that could be scattered all over the place or lack of instructions or tools to process them. With the help of our [BMD Orion app](https://github.com/BlockMedical/Orion) for hosting, you can host your datasets right off from your desktop/laptop and register them on BlockMed. This solves one of the problem to host datasets for public access. However, this does not solve the other problems such as data cleansing or data preparation. This will require your help to provide these code sets and pipeline as part of the codesets on BlockMed, or if you would like to keep them private, you can also upload and register the processed data on BlockMed jsut for download. 

We selected the open source Imagenets as a start. In order to collect all images for Imagenet, the first hurdle users usually run into is how to download all of them from millions websites. We have leverage a tool (like a crawler) to help us fetched all of these images and consolidated them for your access. We also leverage our [BMD Orion app](https://github.com/BlockMedical/Orion) app to host them on IPFS where you can download them when you access them via BMD. This exercise showcase how users can help others to fetch the datasets, register them on BlockMed for reward, and distribute the dataset with the help of our BMD Orion app.

## Training Data and Applying Machine Learning and AI Algorithms

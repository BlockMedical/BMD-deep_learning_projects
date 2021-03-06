# BMD Deep Learning Projects
In proposed open protocol, the sensor’s raw data streams, de-identified on distributed IPFS file storage network, can be made available to community of BMD token holders and developers, who can utilize various machine learning and deep learning algorithms frameworks such as TensorFlow, PyTorch, CNTK, and MXNet to more efficiently refine accuracy not only on static, old historical data, but on constantly generated new live data.

Read more on our [whitepaper](https://www.slideshare.net/secret/4CGbQSZ5xrHU6w) page 15.

## Data Collection and Sourcing
When it comes to datasets and data source, data collection is always a challenging part especially when it comes to opens source datasets that could be scattered all over the place or lack of instructions or tools to process them. With the help of our [BMD Orion app](https://github.com/BlockMedical/Orion) for hosting, you can host your datasets right off from your desktop/laptop and register them on BlockMed. This solves one of the problem to host datasets for public access. However, this does not solve the other problems such as data cleansing or data preparation. This will require your help to provide these code sets and pipeline as part of the codesets on BlockMed, or if you would like to keep them private, you can also upload and register the processed data on BlockMed jsut for download. 

We selected the open source [Imagenets](http://image-net.org/download-imageurls) as a start. In order to collect all images for Imagenet, the first hurdle users usually run into is how to download all of them from millions websites. We have leverage a tool (like a crawler) to help us fetched all of these images and consolidated them for your access. We also leverage our [BMD Orion app](https://github.com/BlockMedical/Orion) app to host them on IPFS where you can download them when you access them via BMD. This exercise showcase how users can help others to fetch the datasets, register them on BlockMed for reward, and distribute the dataset with the help of our BMD Orion app.

## Training Data and Applying Machine Learning and AI Algorithms
For our selected example above (Imagenet), you can go to  https://ipfs.blcksync.info/file-access and search for `IMAGENET`, you should see 4 entires registered by us e.g. `95.82 GB` registered on `1/10/2019, 8:46:48 PM`.

```
[IMAGENET] [http://www.image-net.org/download-imageurls] Image collection Fall 2011 (http://image-net.org/imagenet_data/urls/imagenet_fall11_urls.tgz) ~1000 categories and ~1.2 millions of images collections downloaded and made available "as-is" for you (not just the URLs). We organized the filename for you into directories based on the WordNet ID where you can look it up on http://image-net.org/synset?wnid=[REPLACEME_WITH_WORDNET_ID] (e.g. http://image-net.org/synset?wnid=n02084071) under CC0 (https://creativecommons.org/share-your-work/public-domain/cc0/). DISCLAIMER: We do not guarantee all images are downloaded correctly and completely. We do not own the copyrights of the images even we have waived our rights under CC0 here. All images in their original resolutions may be subject to copyright from original owners, and this collection is just to assist users in the context of "non-profit, and non-commercial use” who does not know how to download all the urls to get started for their research for the "public good". We reserve the rights to take down this collection anytime due to copyright claims, and forfeit or donate our profits made by your access subtracting the cost of hosting and downloading the images.
```

If you click on `Access`, you will be prompt to use BMD to access the dataset. Once you use your BMD, you should be redirected to a page that provides you the access link and a list of files that are part of the imagenet. You will notice that the imagenet has been grouped images by categories based on `WordNet ID`(http://image-net.org/synset). With the link, it contains a `Hash` in the URL itself. If you don't use the Hash in the link, you can also just cherry-pick individual files to download. In order to bulk download all files, the `Hash` on the parent URL link (the one in the address bar in your browser) can be imported by our [BMD Orion App](https://github.com/BlockMedical/Orion) to download them for you. This may take awhile depending on your network bandwidth and other variables. Once the data is downloaded, you could access those files and apply your favorite algorithm to train and process them. Here is a screenshot on how to use the BMD Orion App to import and download these files to your local machine.


![Imagenet Download Instructions with Orion](https://github.com/BlockMedical/BMD-deep_learning_projects/raw/master/images/Orion_Manual_imgnet.png)




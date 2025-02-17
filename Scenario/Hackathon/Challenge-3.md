# Challenge 3 - Search Based on Images

### Estimated Duration: 90 Minutes

## Background Story

Now that you have a database to find potential issues faced by Woodgrove Retail, the next step is to build an AI service and add additional functionalities. The goal of the feature should be to allow 'search and find' of products available. It can be done by uploading a picture found by a potential customer to see if the same item is available.

## Technical Details

Using Vision Studio and Azure Machine Learning, you will be tagging a few dozen images and will be building a service to repurpose the images on the website potentially.  
There are the [images](https://openhackguides.blob.core.windows.net/ai-openhack/images.zip) to start with.

Your task:

* Set up Azure Vision Studio
* Train custom vision model using:
  * Product image dataset
  * Category labels
  * Product attributes
  * Implement a search endpoint

| Product | Related Image Sample |
|---------|----------------------|
|Accessories|![Accessoires](images/Accessoires.png) |
|Bedclothes|![Bedclothes](images/Bedclothes.png)|
|Coffee Mug|![Coffee Mug](images/CoffeeMug.png)|
|Gimmick|![Gimmick](images/Gimmick.png)|
|Hoodie|![Hoodie](images/Hoodie.png)|
|Rubber boots|![Rubber boots](images/Rubberboots.png)|
|Sweater|![Sweater](images/Sweater.png)|
|T-Shirt long|![T-Shirt long](images/T-Shirtlong.png)|
|T-Shirt short|![tshirt](images/T-Shirtshort.png)|

## Success Criteria

* Working image recognition model
* Successful product matching
* Integration with search functionality
* Performance metrics meeting thresholds
* Once the model is trained, you should click on the **'Try it out'** link, upload some of the sample images, and validate if the results are appropriate.

![testimages](images/testimages.png)

<!--  
<validation step="accfe7c1-5b47-4971-b0bc-d1ed77092e2e" />
-->

## Resources

- [Labeling images and text documents](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-label-data?view=azureml-api-2)
- [What is Custom Vision?](https://learn.microsoft.com/en-us/azure/ai-services/Custom-Vision-Service/overview)

## Conclusion

Completing this challenge will enable you to integrate computer vision capabilities into applications using Azure Vision Studio and Machine Learning. You will also learn how to develop AI-powered image search features and enhance user experience by allowing customers to search products based on images they upload.

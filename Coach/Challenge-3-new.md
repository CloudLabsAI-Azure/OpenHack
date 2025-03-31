# Challenge 3 - Coaches Guide

## Image Search

- **Note:** Use the free version **F0** to create the image resource.

- Start by downloading the following [images](https://openhackguides.blob.core.windows.net/ai-openhack/ArticlesOfClothing.zip)

### Create a new Custom Vision Service

1. Create a Custom Vision AI service.

   ![](images/custom-vision.png)

1. In the Basics tab, provide the necessary details.

   - **Create options** : **Both**
   - **Subscription** : Select the default subsciption
   - **Resource Group** : **openhack**
   - **Region** : Select the default region
   - **Name** : Enter a unique name
   - **Training pricing tier** : **Free F0**
   - **Prediction pricing tier** : **Free F0**
   - Click **Review + Create**
  
   ![](images/custom-vision-create-01.png)

   ![](images/custom-vision-create-02.png)

1. After successful deployment of the Custom Vision Service open the following url and **SIGN IN** using your Azure credentials.

   ```
   https://customvision.ai/
   ```

   ![](images/custom-vision-sign-in.png)

1. Agree to the Terms of Service.

   ![](images/custom-vision-agree-terms.png)

1. Click on the **NEW PROJECT** card.

   ![](images/custom-vision-new-project.png)

1. In the **Create new project** dialog enter the following and then click **Create project**:
   
   - Custom and unique name
   - Short Description
   - Resource should select the service previously created
   - Leave the **Project type** to **Classification**
   - Leave **Classification Types** to **Multiclass (Single tag per image)**
   - Leave the **Domains** to **General [A2]**
  
   ![](images/custom-vision-create-new-project.png)

   > **Note:** Might take a minute before it displays in the UI.

1. In your project, under **Training Images**, click on **Add images**.

   ![](images/custom-vision-add-images.png)

1. Select the **Accessories** folder under the **Training** folder, select all the images and click on **Open**.

   ![](images/custom-vision-add-images-accessories.png)

1. Tag the images as **Accessories** and click on **Upload 17 files**.

   ![](images/custom-vision-tag-accessories.png)

1. Click on **Done** once all the images of the Accessories folder have been uploaded.

   ![](images/custom-vision-tag-accessories-done.png)

1. Similarly, repeat for all the other folders in the **Training** folder by clicking on the **Add images** button at the upper left.

   ![](images/add-images-button.png)

1. Once all the images in the the **Training** folder have been tagged, you will see the following tags in the left menu.

   ![](images/custom-vision-all-tags.png)

1. Click the **Train** button on the top row of links.

   ![](images/custom-vision-train.png)

1. Click the next **Train** button that comes up in the dialog and leave it at **Quick Training**.

   ![](images/custom-vision-quick-training.png)

1. Once the training has completed the screen will resemble the following.

   ![](images/custom-vision-iteration.png)

   ![](images/custom-vision-performance-per-tag.png)

1. Click on the **Quick Test** button on the top row.

   ![](images/custom-vision-quick-test.png)

1. Click on **Browse local files** button.

   ![](images/custom-vision-browse-local-files.png)

1. Select one of the items in the **Test** folder and click on **Open**.

   ![](images/custom-vision-test-folder.png)

1. The cowboy hat has over 70% chance of being an **Accessories**.

   ![](images/cowboy-hat.png)

1. Coffee mug is over 99% match.

   ![](images/cofee-mug.png)

1. Rubber boots is also over 99% match.

   ![](images/rubber-boots.png)

## Resources

- [Quickstart: Build an image classification model with the Custom Vision portal](https://learn.microsoft.com/en-us/azure/ai-services/custom-vision-service/getting-started-build-a-classifier?source=recommendations)
- [Create Custom Vision](https://portal.azure.com/?microsoft_azure_marketplace_ItemHideKey=microsoft_azure_cognitiveservices_customvision#create/Microsoft.CognitiveServicesCustomVision)
- [Custom Vision web page](https://customvision.ai/)



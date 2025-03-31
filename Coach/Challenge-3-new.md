# Challenge 3 - Coaches Guide

## Image Search

- **Note:** Use the free version **F0** to create the image resource.

- Start by downloading the following [images](https://openhackguides.blob.core.windows.net/ai-openhack/ArticlesOfClothing.zip)

### Create a new Custom Vision Service

1. Create a Custom Vision AI service.

   image

1. In the Basics tab, provide the necessary details.

   - **Create options** : **Both**
   - **Subscription** : Select the default subsciption
   - **Resource Group** : **openhack**
   - **Region** : Select the default region
   - **Name** : Enter a unique name
   - **Training pricing tier** : **Free F0**
   - **Prediction pricing tier** : **Free F0**
   - Click **Review + Create**
  
   image

   image

1. After successful deployment of the Custom Vision Service open the following url and **SIGN IN** using your Azure credentials.

   ```
   https://customvision.ai/
   ```

   image

1. Agree to the Terms of Service.

   image

1. Click on the **NEW PROJECT** card.

   image

1. In the **Create new project** dialog enter the following and then click **Create project**:
   
   - Custom and unique name
   - Short Description
   - Resource should select the service previously created
   - Leave the **Project type** to **Classification**
   - Leave **Classification Types** to **Multiclass (Single tag per image)**
   - Leave the **Domains** to **General [A2]
  
   image

   > **Note:** Might take a minute before it displays in the UI.

1. In your project, under **Training Images**, click on **Add images**.

   image

1. Select the **Accessories** folder under the **Training** folder, select all the images and click on **Open**.

   image

1. Tag the images as **Accessories** and click on **Upload 17 files**.

   image

1. Click on **Done** once all the images of the Accessories folder have been uploaded.

   image

1. Similarly, repeat for all the other folders in the **Training** folder by clicking on the **Add images** button at the upper left.

   image

1. Once all the images in the the **Training** folder have been tagged, you will see the following tags in the left menu.

   image

1. Click the **Train** button on the top row of links.

   image

1. Click the next **Train** button that comes up in the dialog and leave it at **Quick Training**.

   image

1. Once the training has completed the screen will resemble the following.

   image

   image

1. Click on the **Quick Test** button on the top row.

   image

1. Click on **Browse local files** button.

   image

1. Select one of the items in the **Test** folder and click on **Open**.

   image

1. The cowboy hat has over 70% chance of being an **Accessories**.

   image

1. Coffee mug is over 99% match.

   image

1. Rubber boots is also over 99% match.

   image





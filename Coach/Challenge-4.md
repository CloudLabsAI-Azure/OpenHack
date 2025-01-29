# Challenge 4 - Coaches Guide

## RAG Pattern

## Task - 01

1. Login to the Azure AI Foundry portal at `https://ai.azure.com/`.
   
1. Click on **Create project**.

   ![newdatasource](images/create-project-1.png)

1. Under Create a project, click on **Customize**.
   
   ![](images/create-project-customize.png)

1. On the **Create a hub** window, provide the details as shown below:
   
    - Hub name : Leave as default
    - Subscription : Leave as default.
    - Resource Group : Leave as default.
    - Location : Leave default.
    - Connect Azure AI services or Azure OpenAI: Leave default.

    ![newdatasource](images/create_hub00.png)
    
1. Select **Create new AI Search**, provide a unique name and select **Create**.

1. On the **Create a hub** window, click on **Next**.

   ![](images/create_hub-next.png)

1. On the **Review and finish** tab, click on **Create**.

   ![](images/create_hub-create.png)

1. Wait for the resources to be deployed.

   ![](images/creating-hub-resources.png)

1. Under "My Assets," select **Models + Endpoints**, then click on **Deploy a Model** and choose **Deploy a Base Model**.
    
    ![newdatasource](images/model+endpoints.png)

1. Choose **gpt-4o** and click on confirm.

    ![newdatasource](images/gpt-4o.png)

1. Fill in the details as shown below:
    
   - Deployment name : Gpt-4o
   - Deployment type : Global Standard
   - Click on customize
   - Token's per Minute rate limit : 10k

   ![newdatasource](images/deploy-1.png)
     
1. Click on **Playground** and then select **Try the Chat Playground** .
     
   ![newdatasource](images/playgrounds.png)
   
1. Click on the **Add your data** tab and then click **Add new data source**  
    
   ![newdatasource](images/add-data.png)
    
1. On the **Data source** dropdown choose **Upload files**

    ![uploadfiles](images/uploadfiles-1.png)

1. From the **Upload** button click the arrow and select **Upload files**. Upload all the PDF files from `C:\LabFiles\generatedpdfs` folder.

    ![uploadfiules 2](images/uploadfiules2-1.png)
    
1. Click on the **Next** button

    ![next 1](images/pdf.png)
    
1. After deployment return back to the **Azure AI Studio**and from the dropdown select **Connect other Azure AI Search resource**

    ![other](images/connect-ai.png)
    
1. Click **Add connection**

    ![addconnection](images/add-connection.png)

1. Create a indentifiable **Index name** and click **Next**

    ![indexname](images/search.png)
    
1. Leave the default settings on the **Search settings** page. Click **Next**

    ![settings](images/search-2.png)

1. Click **Create vector index**

    ![settings](images/create-vector.png)

1. Give it some time to **Crack and chunk** the data

    ![crack](images/chunk.png)

1. Once completed change the **Search** type to **Hybrid(vector + keyword)**

    ![hyrid](images/hackvector.png)
    
1. Expand the **Advanced settings** section and max out the following:

    ![advanced](images/advanced-1.png)
    
1. Use the following prompt

    ```
    Which A_Category has the most returns?
    ```
1. Final Output
   
    ![answer 2](images/catogery.png)

  
### Hint Level 1 - Document Generation

* Check PDF generation requirements
* Verify blob storage permissions
* Review cognitive search service tier


### Hint Level 2 - Search Implementation

* Consider these enrichment skills:
  * OCR for text extraction
  * Image analysis
  * Key phrase extraction
  * Entity recognition    
    
## Bonus

- Using the System message map the A_Category to the word Category to make the prompt easier to use.

# Microsoft Azure OpenHack - Hackathon

### Overall Estimated Duration: 8 hours

## Introduction

This hackathon is designed to immerse you in the world of Azure cloud services, machine learning, AI, and data management. Throughout the hackathon, you will tackle real-world challenges faced by Woodgrove Retail, a hypothetical company, by utilizing a wide array of Azure tools and technologies. The challenges span across SQL server management, machine learning model development, AI-powered image search, document processing using the RAG pattern, and advanced data retrieval techniques.

By participating, you will gain practical experience in building AI-driven solutions, deploying machine learning models, enhancing customer interaction, and improving operational efficiency. Whether you are working with Azure's data services or integrating cutting-edge AI capabilities, this hackathon offers an excellent opportunity to refine your skills and contribute to innovative business solutions.

## Hackathon Objectives

By participating in this hackathon, you will:

- Gain practical experience with Azure Data Service and Machine Learning to restore and analyze data. You will also create machine learning pipelines to detect and address data issues.
- Integrate Azure Vision Studio and Machine Learning to build AI models for image recognition. Learn how to develop applications that allow users to search for products based on images.
- Build and transform data pipelines in Azure Machine Learning, train machine learning models, and deploy them to detect data issues, enhancing data-driven business solutions.
- Apply the Retrieval-Augmented Generation (RAG) pattern to generate and process documents and use Azure Cognitive Services to extract structured data from unstructured formats like PDFs.
- Develop advanced search capabilities using the RAG pattern. Create Node.js applications that enhance data retrieval and improve systems like inventory management.

## Hackathon Format: Challenge-Based

This hackathon adopts a challenge-based format, offering you a unique opportunity to learn while dealing with practical problems. Each challenge includes one or more self-contained tasks designed to test and enhance your skills in specific aspects of Azure OpenAI services. You will approach these challenges by:

- Analyzing the problem statement.
- Strategizing your approach to find the most effective solution.
- Leveraging the provided hackathon environment and Azure AI services.
- Collaborating with peers to refine and implement your solutions.

## Challenges Overview

- **Challenge 0 - Development Environment Configuration:** Ensure that you have the required prerequisites before diving into the challenges. The required software is already pre-installed in your hackathon environment: Visual Studio Code, SQL Server Management Studio (SSMS), Pandoc v3.5, Python v3.10.11, Node.js v18.16.1, and .NET Core v8.0.

- **Challenge 1 - Restore an SQL Server Backup and Query the Data:** Participants need to restore an SQL Server backup and query the data using SQL Server Management Studio in Azure. The objective is to analyze the data through views or custom queries, uncover insights, and solve business challenges faced by the company.

- **Challenge 2 - Use Machine Learning to Expose Data Issues:** This challenge requires participants to set up an Azure Machine Learning compute environment, create datasets, and build a pipeline to transform the data. After running the pipeline, participants will train a machine learning model, deploy it as a service, and test it to detect data issues.

- **Challenge 3 - Search Based on Images:** The goal is to create an AI service using Azure Vision Studio and Azure Machine Learning, allowing customers to upload images and find similar products in the database. This challenge focuses on image tagging and model creation to match uploaded images with available products.

- **Challenge 4 - RAG Pattern:** Participants will use the Retrieval-Augmented Generation (RAG) pattern to process data from SQL Server and images. They will generate PDFs from this data and upload them to Azure Blob Storage. Using Azure Cognitive Services, they will extract and enhance data from the PDFs, including article numbers, categories, and related images.

- **Challenge 5 - Advanced Retrieval-Augmented Generation (RAG) Pattern:** In this challenge, participants will export data from SQL Server to a CSV file and build an inventory application using Node.js. The focus is on implementing an advanced RAG pattern to enhance data retrieval and search capabilities in the application, improving overall inventory management.

## Getting Started with the Hackathon

Welcome to your Microsoft Azure OpenHack - Hackathon! We have prepared a seamless environment for you to explore and learn about Azure services. Let's begin by making the most of this experience:
 
## Accessing your Hackathon Environment
 
Once you are ready to dive in, your virtual machine and hackathon guide will be right at your fingertips within your web browser.

![](images/getting-started-openhack.png)

### Virtual Machine & Hackathon Guide
 
Your virtual machine is your workhorse throughout the workshop. The hackathon guide is your roadmap to success.
 
## Exploring your Hackathon Resources
 
To get a better understanding of your hackathon resources and credentials, navigate to the **Environment** tab.
 
![](images/env-01.png)
 
## Utilizing the Split Window Feature
 
For convenience, you can open the hackathon guide in a separate window by selecting the **Split Window** button from the top right corner.
 
![](images/split-01.png)
 
## Managing your Virtual Machine
 
Feel free to **start, stop, or restart** your virtual machine as needed from the **Resources** tab. Your experience is in your hands!

![](images/resourses.png)

## Let's get started with the Azure Portal.
 
1. On your virtual machine, click on the **Azure Portal** icon as shown below:
 
   ![](images/azure-portal-edge.png)

1. On the **Sign in to continue to Microsoft Azure** tab, you will see the login screen. In that, enter the following email/username and click on **Next**. 

   * **Email/Username**: <inject key="AzureAdUserEmail"></inject>
   
     ![](images/user-email.png "Enter Email")
     
1. Now, enter the following password and click on **Sign in**.
   
   * **Password**: <inject key="AzureAdUserPassword"></inject>
   
     ![](images/user-pass.png "Enter Password")

1. If you see the pop-up **Action Required**, click on **Ask later**.

   ![](images/asklater.png)

   >**NOTE:** Do not enable MFA. Select **Ask later**.
     
1. If you see the pop-up, **Stay signed in.** Select **No**.

1. If you see the pop-up, **You have free Azure Advisor recommendations!** Close the window to continue with the hackathon.

1. If a **Welcome to Microsoft Azure** pop-up window appears, select **Maybe Later** to skip the tour.
   
## Support Contact
 
The CloudLabs support team is available 24/7, 365 days a year, via email and live chat, assuring seamless assistance all the time. We offer dedicated support channels tailored specifically for learners and instructors, ensuring that all your needs are efficiently addressed.

Learner Support Contacts:
- Email Support: cloudlabs-support@spektrasystems.com
- Live Chat Support: https://cloudlabs.ai/labs-support

Now, click on **Next** from the lower right corner to move on to the next page.

![](images/lab-next.png)

### Happy Hacking!!

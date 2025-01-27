# Challenge 2 - Use Machine Learning to Expose Data Issues

### Estimated Duration: 120 Minutes

## Background Story

Now that you have had a chance to explore the data let's use machine learning to figure out which portion of the data is creating the underlying issues. For this type of data issue, we have chosen to use a classification model. The goal is to use Machine Learning to identify patterns in returns and predict high-risk orders.

You will be building a classification model using Designer that includes the following:

* Data preparation
* Feature engineering
* Model training
* Model evaluation
* Deploy prediction endpoint

## Technical Details

Create the following:

- Create Azure ML workspace
- Create compute
- Create a dataset
- Create a pipeline in Designer and load data to the canvas
- Add transformations
- Run the pipeline
- View the transformed data
- Add training modules
- Run the training pipeline
- Create an inference pipeline
- Deploy a service
- Test the service

## Success Criteria

* Working ML pipeline
* Deployed prediction endpoint
* Demonstration of predictions using test data
* Accuracy metrics above baseline

Demonstrate to the coach that you are able to provide a sample JSON segment, showing that it will properly predict either 0 or 1 based on the new service.

**Negative Return Prediction** 

```
{
	"Inputs": {
		"input1": [
			{
				"_KEY_OrderNo": 1028476,
				"_KEY_Supplier": 16,
				"ArticleNo": 502,
				"KEY_CustomerNo": 10752,
				"F_Discounts": 0,
				"F_VolumeDiscount": 0,
				"F_StudentDiscount": 0,
				"F_ListPrice": 33.99,
				"F_IsReturned": 0,
				"A_Category": "T-Shirt short",
				"S_Country": "USA",
				"C_MeansOfPayment": "direct debit",
				"C_Fit": "Regular",
				"F_IsDefect": 0,
				"C_City": "Berlin"
			}
		]
	},
	"GlobalParameters": {}
}
```

**Positive Return Prediction**
```
{
	"Inputs": {
		"input1": [
			{
				"_KEY_OrderNo": 477063,
				"_KEY_Supplier": 35,
				"ArticleNo": 568702,
				"KEY_CustomerNo": 805629,
				"F_Discounts": 1,
				"F_VolumeDiscount": 1,
				"F_StudentDiscount": 1,
				"F_ListPrice": 1886.79,
				"F_IsReturned": 0,
				"A_Category": "Accessoires",
				"S_Country": "France",
				"C_MeansOfPayment": "voucher",
				"C_Fit": "Fide",
				"F_IsDefect": 1,
				"C_City": "Regensburg"
			}
		]
	},
	"GlobalParameters": {}
}
```

<validation step="1865e412-e5d2-4a8b-ba5b-a83b5be4442e" />

## Resources

- https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02b-create-classification-model.html
- https://learn.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks?view=azureml-api-2
- [Explore classification with Azure Machine Learning Designer](https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02b-create-classification-model.html)

## Conclusion

This challenge will help you build and deploy machine learning models within Azure, empowering you to detect data quality issues. By the end, you will gain valuable experience in creating datasets, transforming data, and deploying models to production. Overall, this will equip you with skills for real-world AI applications in data analysis.



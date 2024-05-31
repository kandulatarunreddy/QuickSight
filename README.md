

Visualizing a Large Dataset using Amazon S3 and Amazon QuickSight
Introduction
In this project, you will learn how to create insightful visualizations from a large dataset using Amazon S3 and Amazon QuickSight. We'll be working with a dataset containing information about 50,000 best-selling products on Amazon.com.

Step 1: Download the Dataset
Navigate to the provided S3 link to download the "Amazon Bestseller Dataset" CSV file and the "manifest.json" file.
Click on "raw" and use Control+S to save both files onto your computer.
Step 2: Store the Dataset in Amazon S3
Open the Amazon S3 console.
Click on "Create Bucket."
Name your bucket (e.g., "aws-project") and keep the settings as default.
Upload the CSV file and the "manifest.json" file into the bucket.
Replace the URL in the "manifest.json" file with the S3 URL of your dataset.
Step 3: Connect S3 Bucket with Amazon QuickSight
Open the AWS management console and navigate to Amazon QuickSight.
Sign up for a free trial of the Enterprise edition if you don't have an account.
Select Amazon S3 as your data source and choose the S3 bucket you created.
Enter the link to your "manifest.json" file and connect to QuickSight.
Select "interactive sheet" to start creating visualizations.
Step 4: Create Visualizations
Drag fields into the graph to create visualizations (e.g., Most popular brands).
Sort, filter, and customize the graphs as desired.
Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.
Conclusion
By following these steps, you can effectively visualize and gain insights from large datasets using Amazon S3 and Amazon QuickSight. Experiment with various visualization techniques to uncover valuable information within your data.

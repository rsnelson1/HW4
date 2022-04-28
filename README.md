# HW4
For this project we investigated whether or not the Cloud Vision API is more accurate at identifying the "surprised" expression on a face from white or non-white images. We hypothesizes that the Machine had been trained on predominantly white faces and thus would be more accurate when assessing the "surprised" expression of white faces than non-white faces.
Below are the steps we used to execute this project for anyone interested in recreating it.
1. Indentified several faces of White and Non-white individuals that are uploaded to this Github repo.
2. Created a bucket in google cloud storage and uploaded these images.
3. Used google colab to test the Cloud Vision API. Google Colab linked here: https://colab.research.google.com/drive/12w1SOXYITcwlF8-87u1HqCnJRVhXZT6a#scrollTo=4MMuY-74QnnD. 
4. Assessed the accuracy of the API and recorded it in:https://docs.google.com/spreadsheets/d/1EiKQ7dqs0JdTV_hoCIA1ZhMOUBf9gv8mCPRpyxSGtgw/edit#gid=0.
5. Exported this data as a csv and uploaded it to BigQuery on Google Cloud.
6. Imported this data into Google Data Studio from BigQuery.
7. Created data visualization in Data Studio: https://datastudio.google.com/reporting/7b6b6827-8e65-490a-992f-ace3bd0afa50/page/YqfqC/edit.


Please contact QTM 250 Group 3 with any questions

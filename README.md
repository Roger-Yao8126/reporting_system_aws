# Antra SEP java evaluation project
yxj8126@gmail.com

## Project setup 
3 applications were run properly and TestSendMail and TestSNS were done.

## What I added for the improvment 

1.  Added delete feature; The records in database and report files are all deleted; Excel was created locally and PDF was created in AWS S3 bucket. Both are deleted according to their location.

2. Updated Sync API to use a fixedSizeThreadPool(2)  for sending request concurrently to both services.

3. Used a database instead of hashmap in the ExcelRepositoryImpl.

4. Used AWS DynamoDB for both ExcelRepository and PDFRepository;   Use of MongoDB for both Repo were also tested successfully.

## 4. Send your code to [Dawei Zhuang(dawei.zhuang@antra.com)](dawei.zhuang@antra.com) using Github/Gitlab. 
Make sure there is README.MD to indicate what did you change/add to the project.

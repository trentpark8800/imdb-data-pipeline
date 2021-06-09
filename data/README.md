# Data Directory

This location is empty on purpose as it is bad practice to store data in your code repo for both performance and securuty reasons.
  
The idea is that you should download the raw csv data locally and unzip the files to the `raw` directory. Then the `landing` directory is for the batch data to land over time. Don't worry about accidentally pushing data to the repo - all csv and .json files are ignores as specified in the .gitignore file.
  
_NOTE:_ In the future the raw and landed data should be stored somewhere accessible to all team members like an AWS S3 bucket or a Azure Blob store.

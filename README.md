# YoutubeDataAnalysis
Youtube Data Analysis using Pig

Project Description - 
--> Problem Statement 

--------->A. Find out the top 5 categories with maximum number of videos uploaded. 
--------->B. Find out the top 10 videos with maximum number of ratings. 
--------->C. Find out the most viewed videos. 


Dataset Description 

Column1: Video id of 11 characters. 
Column2: uploader of the video of string data type. 
Column3: Interval between day of establishment of Youtube and the date of uploading of the video of integer data type. 
Column4: Category of the video of String data type. 
Column5: Length of the video of integer data type. 
Column6: Number of views for the video of integer data type. 
Column7: Rating on the video of float data type. 
Column8: Number of ratings given on the video. 
Column9: Number of comments on the videos in integer data type. 
Column10: Related video ids with the uploaded video.


Solution Steps - 
1. Load data to HDFS
2. Load and clean data using pig
3. Store clean data again to HDFS
4. Load and analyze the clean data
5. Store the results back to HDFS


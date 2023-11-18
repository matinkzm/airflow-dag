# airflow-dag
This is a project from ETL and Datapipeline with shell , Airflow and Kafka course from coursera. It has two part first part i write a dag using python and airflow libraries.
After importing neccessery libraries we define a default arguements for dag default arguements. it contains owner name ,email , starting date and if it sends email on failure and retry.
Then define the dag itself with dag name , how often the dag should run(in this case every day) , description and assign the default arguements that defined before to dag's default arguements.
Continue with defining tasks: first task unzip the downloaded file from course lab , second task extract part 1,2,3,4 from csv file , third task extract part 5,6,7 from tsv file , 4th task extract data 
from fixed width file , then consolidate the extracted data and load it into a csv file.
After defining the task we should create the task pipeline.

data-ingestion-service:

1)Docker compose to install KAFKA:

Please docker-compose.yml file to a folder .And in command prompt change to the folder where you placed docker-compose.yml.
After that runn the command "docker-compose -f docker-compose.yml up -d"
This will make kafka and zookeeper up and rinning in Docker image.

2) Mongo Database connection :
If you want to check records manually in mongoDB connect to DB using MongoDBCompass IDE. Below are conenction URL
DB URL: mongodb+srv://Capstone:Capstone@capstone.itrtq.mongodb.net/Capstone?retryWrites=true&w=majority

While testing messageConsumer.py if process failes with any Certificate expire errors please follow below steps to fix it.
a)Download https://letsencrypt.org/certs/lets-encrypt-r3.pem
b)rename file .pem to .cer
c)double click and install

3)data-ingestion-service:

to execute this service please open the all code files in Pycharm make sure there are no pakage errors if required install packeges in pycharm .
Then first run messageConsumer.py and then main.py

messageConsumer.py: some times this will faile with certificate expire errors follow belwo steps to fix it.
a)Download https://letsencrypt.org/certs/lets-encrypt-r3.pem
b)rename file .pem to .cer
c)double click and install


model-training-service-V1:
1) Copy model-training-service-V1 folder.
2) open main.py and ml_utils.py in pycharm and make sure there are no package errors.
2) And run main.py 


model-prediction-service:
1) Copy model-prediction-service folder.
2) Open main.py amd ml_utils.py in pycharm and make sure there are no package errors 
3) Makesure models folder is copied correctly
3) And run main.py 
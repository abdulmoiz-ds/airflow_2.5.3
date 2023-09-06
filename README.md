
# Airflow 2.7.0

### Details:

📦 PyPI: https://pypi.org/project/apache-airflow/2.7.0/

📚 Docs: https://airflow.apache.org/docs/apache-airflow/2.7.0/


#### Airflow Webserver Details:
```
username : airflow
password : airflow

```
#### for additional information click on it:

https://medium.com/@akshay03/how-to-install-apache-airflow-with-docker-container-on-ec2-machine-52cd575c361e


## Deployment
```bash
# Download the Source code from Git by using Git Clone Command as follows:

git clone https://github.com/datainteg/airflow_2.7.0.git
mv airflow_2.7.0 airflow_main
cd airflow_main


# Firstly check the docker service active or not:

sudo systemctl status docker
sudo systemctl start docker
sudo systemctl stop docker
sudo systemctl restart docker


# After docker service is up and running then Firstly initialize airflow database by using following Command:

sudo docker-compose up airflow-init


# Once you initialized database( In this airflow setup, airflow database is postgres ) after run the following Command for start the airflow 

sudo docker-compose up -d

```

## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshaythakare3/)



## Feedback

If you have any feedback or query, please reach out to us at akshay.thakare031@gmail.com


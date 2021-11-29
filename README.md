# Telecom-Churn-Case-study - IIITB-Assignment [![](https://img.shields.io/badge/Prateek-Ralhan-brightgreen.svg?colorB=ff0000)](https://prateekralhan.github.io/)


## Problem Statement
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

In this project, we analysed customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

You can also access the Live web-app [here.](https://telecom-churn-analysis-app.herokuapp.com/)

<kbd>
<img src="https://user-images.githubusercontent.com/29462447/101314072-c6a98d00-387d-11eb-91ba-9b9051f9dba0.png" data-canonical-src="https://user-images.githubusercontent.com/29462447/101314072-c6a98d00-387d-11eb-91ba-9b9051f9dba0.png"/> 
</kbd>

<hr>

### Running the Dockerized App
1. Ensure you have Docker Installed and Setup in your OS (Windows/Mac/Linux). For detailed Instructions, please refer [this.](https://docs.docker.com/engine/install/)
2. Navigate to the folder where you have cloned this repository ( where the ***Dockerfile*** is present ).
3. Build the Docker Image (don't forget the dot!! :smile: ): 
```
docker build --tag telecom_churn_app .
```
4. Run the docker:
```
docker run --publish 8000:8080 --detach --name bb telecom_churn_app
```

This will launch the dockerized app. Navigate to ***localhost:8000*** in your browser to have a look at your application. You can check the status of your all available running dockers by:
```
docker ps
```

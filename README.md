# Flask-app-for-Bank-authentication-Note-using-Docker

## Machine learning web application using FLASK API for bank authentication note and containerizing the application using docker

## Setup:

* Install Docker: https://docs.docker.com/desktop/install/windows-install/ depending on the Operating System.

## Explanation:

* In this project, the machine learning model predicts whether the bank note is authenticated or not. The results of the model will be as follows:
If Authentication is true then 1 or if authentication is false the result is 0.**

* The machine learning model is then integrated with the FLASK Web API along with Flasgger(web framework) as a front-end application for a better user experience of viewing the results.

* This entire application is then containerized using docker, so that everyone can use the application irrespective of the underlying software or hardware configuration.

* Go to the respective working directory mentioned in the docker file and run the image to interact with the application by providing the values for variance, skewness, curtosis, and entropy for a 'GET'request. On the other hand, you can also provide the testfile.csv and check the results for a 'POST' request.
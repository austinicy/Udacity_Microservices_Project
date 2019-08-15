[![CircleCI](https://circleci.com/gh/austinicy/Udacity_Microservices_Project.svg?style=svg)](https://circleci.com/gh/austinicy/Udacity_Microservices_Project)

## Project Overview

In this project, you will apply the skills you have acquired in this course to operationalize a Machine Learning Microservice API. 

This project is part of the Udacity Cloud DevOps Engineer class project 4. In this project, a pre-trained `sklearn` model was given to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. This project containerized the machine learning microservice, push to docker hub and operationalize with kubernetes cluster.


---

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`
1. Run in Docker:  `./run_docker.sh`
2. Run in Kubernetes:  `./run_kubernetes.sh`
4. Test API:  `./make_prediction.sh`
4. Stop Kubernates Clusters:   `minikube delete`

# Versions Roadmap
Define goals and todos for the next version.

## Rough Outline
In this project I want to find a way to easily run airflow dags on AWS ECS Fargate.
The goal is to reduce the setup overhead between writing a DAG and ML Job (Kedro),
and running it on a `production-grade` infrastructure setup.

Because this is my first Airflow Project, I need to:
 - get familiar with Airflows concepts
 - run Airflow locally
 - dockerize Airflow
 - Write a first DAG (some job for future ML Job)
 - Depoy Airflow to AWS ECS Fargate
 - Iterate over ideal Deployment startegies
 - Iterate over ideal component seperation
 - Define Infrastructure as Code using AWS CodeFormation
 - Figure out how kedro fits into the deployment (iterate over deployment infrastructure,
   to make kedro fit?)
 - Write ML Job and test the setup
 - Automate all the things

## v0.1
**GOAL:** _Local Setup_
 - [ ] Setup docker-compose file
 - [ ] Push images to docker hub

**TODOs:**
 - [ ] _<...>_

_Completed Date and version tag link_

--------
## v0.2
**GOAL:** _Running first DAG_
 - [ ] _<...>_

**TODOs:**
 - [ ] _<...>_

_Completed Date and version tag link_

--------
## v0.3
**GOAL:** _Deployment to AWS ECS with Fargate_
 - [ ] _<...>_

**TODOs:**
 - [ ] _<...>_

_Completed Date and version tag link_


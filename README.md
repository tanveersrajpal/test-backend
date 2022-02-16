# Assessment

This repository contains a frontend and a backend service. These services together serve as a ToDo List App.
Read the below documentation for details about each service.

[FrontEnd Readme](Frontend/README.md)

[Backend Readme](Backend/TodoList.Api/README.md)

> ℹ️ **The task at hand is to deploy the application inside a container or on a vm (IaaS). The application is completely self contained and should not require any additional dependencies to run.**

Candidates should assume that the solution will be deployed to an empty cloud account/subscription with no existing infrastructure in place.

Candidates should use IaC to deploy the infrastructure required.

There should not be a requirement for Clearpoint to access a candidate's cloud services account to deploy this solution.

Candidates should provide documentation on their solution, including:

* Pre requisites for your deployment solution.
* High level architectural overview of your deployment.
* Process instructions for provisioning your solution.

## Bringing up the app using docker-compose

Running `docker-compose up` from the root directory of this project will build the images and spin up containers for `frontend` and `backend` and the app will be accessible at http://localhost:3000

## Assessment Grading Criteria

##### Key Criteria

The submission should the following criteria:

* Must be able to start from a cloned git repo.
* Must document any pre-requisites clearly.
* Must deploy infrastructure using code.

##### Grading

Candidates will be assessed across the following categories:

##### General Approach

* Clarity of code
* Comments where relevant
* Consistency of Coding

#### Security

* Least Privilege
* Network segmentation (if applicable to the implementation)
* Secret storage (if applicable)
* Platform security features

#### Simplicity

* Do not overengineer the solution

#### Resiliency

* Infrastructure should support Auto scaling and the application should be highly available

#### Bonus points

* Deploy via an automated CICD process.
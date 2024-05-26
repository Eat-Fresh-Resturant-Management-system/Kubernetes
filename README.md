# Kubernetes Cluster Setup

This repository contains the necessary files to setup a kubernetes cluster on a local machine using minikube. The cluster is setup with 3 microservices, each running in a separate pod. The microservices are written in typescript/C# and use mongodb/sql as the database.

## Kubernetes Cluster Setup




## Microservices

### 1. TableBookingService: 
Important things to note about this service:
* It is a RESTful/grapghql service.
* It is written in typescript.
* It uses appollo server and express.js as the web framework.
* It uses mongodb as the database.

*do explain some yaml implementations here


#### Yaml files for deployment and service creation:
#### Ports 

#### Anything else



### 2. MenuManagementService:

*do explain some yaml implementations here


#### Yaml files for deployment and service creation:
#### Ports 

#### Anything else


### 3. OrderProcessingService:


*do explain some yaml implementations here


#### Yaml files for deployment and service creation:
#### Ports 

#### Anything else

## API Endpoints and Port Numbers

### Endpoints
| TableBooking     | Path            |
|------------------|-----------------|
| Create a Table   | /CreateTable    |

### Port Numbers
| Service         | Container port Number |
|-----------------|-----------------|
| Table booking   | 3146            |
| Menu            | 3000, 5136      |
| Order           | 7000, 5126      |
| API Gateway     | ~5660~ (WIP)    |
| BMQ             | 5672            |
| Mongo           | 27017 / 8081    |
| SQL             | 1443            |

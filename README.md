# Swisscom SminGate Coding Challenge CI/CD

## Background
The "Hello World" application is running in Kubernetes and requires additional parameters from an external data source, which can be retrieved via an API. The API requires an authentication request, providing a token, authorizing subsequent query requests. 

The objective of this task is to create an automation, which authenticates against the API of the external data source, retrieves the parameters, and deploys the "Hello World" application including the retrieved data to Kubernetes.

## Tasks
Part 1 involves creating the automation given specific presets. Part 2 involves critacally questioning the presets.

### 1.
a) Create a Bash script which retrieves the token for the external data source API, then retrieves PARAMETER1 and PARAMETER2. Create a docker container, ready to run this bash script.
b) Extend the Bash script to generate a plain kubernetes deployment yaml. The provided deployment must result in the container outputting "HELLO WORD , <parmater1> - <parmater1>" on startup, with the retrieved values of PARAMETER1 and PARAMETER2.

### 2.
Please come up with an alternative way to deploy the "Hello World" application with the same end result as with part 1, then briefly debate the pros and cons of both solutions.
Please note: it is not required to create a demonstration of the alternative solution.

> **Important:** To ensure your privacy, please **download** the Github repository and submit your work in your own Github repository. Once finished, kindly send us the link to the repository for review.

## Resources
### Hello World app: https://hub.docker.com/_/hello-world
### external data source: 
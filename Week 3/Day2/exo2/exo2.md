## Guided Exercise1: Contrasting Kubernetes Distributions

- virtual box is installed.

![alt text](images2/1.png)


- verifying the installation

![alt text](images2/-1.png)

## Guided Exercise 2: Connecting kubectl to Your Cluster

- Installing kubectl in Windows

![alt text](images2/2.png)

- Downloading the DO100-apps repository using Git

![alt text](images2/3.png)

-  Connecting kubectl to the Kubernetes cluster

#### PROBLEM !

- The problem happens when running the script DO100 setup. Even though I changed the username from "ASUS" to another one and also tried using username.ToLower() in the script, it still doesn't work during execution.

![alt text](images2/4.png)

- if u have this probleme try to lowercase ur name by changing the first line of setup.ps1 to `$USERNAME = $env:USERNAME.ToLower()`

![alt text](images2/pr.png)

## Running and Interacting with Your First Application
 - pod created

 ![alt text](images2/p.png)

 - Deployement created

![alt text](images2/de.png)

## Executing Commands Within an Existing Pod

![alt text](images2/exx.png)

## Deploying Managed Applications
- create a deployement

![alt text](images2/de.png)

- this command contains run time information about the deployment

![alt text](images2/d1.png)

### Networking in k8s

- create a service "svc" and expose the port :

![alt text](images2/svc.png)
#### mouving k8s into usr/bin/

![alt text](images2/i1-1.png)

- accessible from our home 

![alt text](images2/i1-2.png)

#### For clean directory, Remove the unecessary.

![alt text](images2/i1-3.png)

#### manifest for kubelet

![alt text](images2/i1-4.png)

#### check the logs for kubelet (running the kubelet in a standalone mode)

- Reminder : Running kubelet in a standalone mode allows for the deployment and management of Kubernetes nodes that are not part of a larger cluster.


![alt text](images2/i1-5.png)

#### Kubernetes pod : kuberlet-test

![alt text](images2/I1-6.png)

- we cannot call the pod with kubctl because we don't have an API server setup for the moment 

![alt text](images2/i1-7.png)

- So we go to docker & check the running containers

![alt text](images2/i1-8.png)

- the pod is doinng its job by "echo-ing" supergiant every 15 

![alt text](images2/i1-9.png)


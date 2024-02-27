### Scheduler
 - we need the scheduler in order to assign the pods to the nodes based on ressources.

- the scheduler is created

![alt text](images2/i5-1.png)

- no unexpected errors

 ![alt text](images2/i5-2.png)

 - the pod now is running 
because of the installation of the scheduler

![alt text](images2/i5-3.png)

- this is the new pod inside a replica-test file

![alt text](images2/I5-4.png)

- created

![alt text](images2/i5-5.png)

- we create a controller manager 
 #### Reminder: 
 the Kubernetes Controller Manager is responsible for managing various controllers within the Kubernetes cluster, and always checks if the actual state is equal to the desired state.

![alt text](images2/i5-6.png)

- setup the controller manager 
- the pods is running

![alt text](images2/i5-7.png)
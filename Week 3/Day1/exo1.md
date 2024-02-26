# Creating a jail from OCI image

## Chroot
![alt text](images/image.png)

## Skopeo & Umoci
 ###### Skopeo (downold OCI image) & Umoci (unpack the image)
![alt text](images/image1.png)

![alt text](images/i2.png)

 ###### we can now chroot via :

![alt text](images/ii.png)

### Network
 ![alt text](images/i3.png)

 -- Processes inside the chroot environment were able to interact with processes and network devices outside the jail. No isolation --
 
 
## Namespace

![alt text](images/i4.png)

![alt text](images/i5.png)

![alt text](images/i6.png)


-UTS-
nothing has changed because the changes made within the user namespace do not propagate to the parent namespace or the system level--

![alt text](images/n.png)

pid namespace

![alt text](images/pid.png)

network namespace

![alt text](images/net.png)


new network namespace called mynet using ip

![alt text](images/net1.png)

Upping the network

![alt text](images/net2.png)

-- create a veth pair which should allow communication --

![alt text](images/c.png)

veth0 & veth1 are associated automatially , now we're linking them to our namespace

![alt text](images/lin1.png)

-Giving addresses-

![alt text](images/ad.png)

![alt text](images/ad1.png)

-- Communicating in both directions --

![alt text](images/ping.png)

#####  userIdù

![alt text](images/nobady.png)

## Demo 

![alt text](images/demo.png)
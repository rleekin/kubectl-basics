We a have two node Kubernetes cluster deployed and ready. So let’s look at the the Kubernetes cluster information. 

Let’s look at the Kubernetes version running the cluster.

`kubectl version`{{execute}}

You’ll see the not just the Kubernetes version but the Build Date and the GoVersion. Notice that the Kubernetes version might not always match.

You might need to gather information about the endpoints of master and services in the cluster.The will come in handy if you have to troubleshoot your cluster.


`kubectl cluster-info`{{execute}}
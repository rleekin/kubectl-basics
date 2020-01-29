Look at the pods in the Kube-System Namespace.

`kubectl get pods -n kube-system`{{execute}}

You will see the pods in the Kube-System namespace.

If you want to see the pods in all the namespaces use this command:

`kubectl get pods -A`{{execute}}
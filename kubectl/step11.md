Now let's take a look at the different output formats you can get from Kubectl. We have been looking at the output in a tabular format. We can look at the information in Json format.

`kubectl get pod -o json `{{execute}}

With this Json format, you can perform advanced queries against the information such as the metadata like labels.

Or if you want to get additional information on the pods you can use this command:

`kubectl get pod -o wide `{{execute}}
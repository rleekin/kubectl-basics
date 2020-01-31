Here are some more quick tips to help you be more efficient at Kubectl
- Get the documentation for Kubernetes resources such as pods or services
`kubectl explain deployment`{{execute}}
This will show you details about a deployment resource type

- View all the supported resources types
`kubectl api-resources`{{execute}}

- View all the resources deployed to the cluster in the Default Namespace
`kubectl get all`{{execute}}
**start minikube**

``minikube start --driver=docker``

**check status**

``minikube status``

**check current node**

``kubectl get node``

**convert to base64 encoded value**

``[Convert]::ToBase64String([Text.Encoding]::UTF8.GetBytes("myuser"))``

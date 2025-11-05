## commands use in deployment

**start minikube**

``minikube start --driver=docker``

**check status**

``minikube status``

**check current node**

``kubectl get node``

**convert to base64 encoded value**

``[Convert]::ToBase64String([Text.Encoding]::UTF8.GetBytes("myuser"))``

**check current resources**

``kubectl get pod``

**create new resource in cluster**

``kubectl apply -f your_file_name.yml``

**get all details of current resources**

``kubectl get all``

**get *configmap* file**

``kubectl get configmap``

**get *secrets* file**

``kubectl get secrets``

**get pods**

``kubectl get pod``

**get *pod* details**

``kubectl describe pod your_pod_name``

**get logs details of pod**

``kubectl logs webapp-deployment-7f96756549-7s6xp -f``

**get service details that deploy on cluster**

``kubectl get svc``

**get *minikube* IP**

``minikube ip``




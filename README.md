# Assessment
Setup instructions:
    - minikube start --cpus=2 --memory=4096 --addons=ingress,metrics-server : to start minikube --cni calico
    - I have added command in commands.txt file to start minio
Explanation of the security incident & how you fixed it :
    - As part of security compliance , I have configured SA for only data-service to access minio and implemented Network-Policy to allow auth-service to only communicate with data-service .
Any assumptions or known issues:
    - None






# postgres-kubernetes

Steps to run:

1) kubectl create -f <file_name>.yaml
2) Repeat step 1 for all files
3) Find the url of the cluster using command: minikube service postgres-service --url
4) Atlast execute the command: psql -h <cluster_url> -U amazinguser --password -p 31885 awesomedb

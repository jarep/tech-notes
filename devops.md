
# Useful commands for Dev Ops

## Docker:

	> docker version
	> docker run

	> docker run --name my-postgres -p 5432:5432 -e POSTGRES_PASSWORD=password -d postgres

## Minikube:
	
	> export CHANGE_MINIKUBE_NONE_USER=true; sudo -E minikube start --kubernetes-version v1.13.0 --vm-driver none

	> helm install --name my-postgresql --set postgresDatabase=mydb --set postgresUser=mydb --set postgresPassword=mydb --version 0.18.1 stable/postgresql
# Install Apicurio Registry  

docker run --name apicurio-registry -it -p 8040:8080 apicurio/apicurio-registry-mem:latest -d. 

UI: http://localhost:8040/ui/artifacts. 

REST API:  

https://www.apicur.io/registry/docs/apicurio-registry/2.1.x/assets-attachments/registry-rest-api.htm   


# Install Postgres (required) 

docker run --name postgres -e POSTGRES_PASSWORD=merlin -d postgres. 

Connect as postgres / merlin (port 5432).  

# Install Backstage

Instructions are available here:  
https://backstage.io/docs/getting-started/. 





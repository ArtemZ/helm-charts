# HPA NGINX INGRESS

### Current Nginx Ingress : 
<a href="https://github.com/helm/charts/tree/master/stable/nginx-ingress">nginx-ingress</a> is an Ingress controller that uses ConfigMap to store the nginx configuration. 

### HPA Nginx Ingress
It providing all property of existing nginx ingress by additional feature you can seperate your all nginx controller according to your availability zones .

## Installing the Chart

    helm install kloia/nginx-ingress --name=test-ingress -f values.yaml
    
 * Example values.yaml file 

```
   availabilityZones:
     - eu-central-1a
     - eu-central-1b
```

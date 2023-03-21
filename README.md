# Juice-Shop
To Install ingress nginx controller:

  kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.6.4/deploy/static/provider/cloud/deploy.yaml

To deploy Deployment for juice-shop 

  kubectl apply -f juice-shop.yaml
  
To check the deployment creation

  kubectl get deployment -n juice-shop
  
To deploy the service for juice-shop

  kubectl apply -f juice-shop-svc.yaml

To check the service for juice-shop

  kubectl get svc -n juice-shop
  
 To deploy the ingress
 
  kubectl apply -f juice-shop-ingress.yaml
  
 To check the ingress
 
  kubectl get ingress  -n juice-shop
  
 Check the App by
 
  curl http://juice-shop.com

  

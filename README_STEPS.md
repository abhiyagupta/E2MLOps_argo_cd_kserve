1. changes in repo before running:
- argo-apps/model.yaml: change url line no 9
- fastapi-helm/template/model-server-1 : storageURI line 23 edit bucket name and path 
- fastapi-helm/template/model-server-1 : image name line 26  
- fastapi-helm/template/model-server-2 : storageURI line 23 edit bucket name and path 
- fastapi-helm/template/model-server-2 : image name line 26
- fastapi-helm/template/values.yaml : change line 17, 27,33
- fastapi-helm/model-server.cm.yml: line 11 and 12- check load balancer and point to your for local testing (not re for git actiosn)
- 

2. aws console- create three ecr repo all private (check E2EMLOP readme_kubernetes.md)
- a18/ui-server 
- a18/web-server
- model-onnx-server 

3. Readme E2EMLOps - deployment01 
- 

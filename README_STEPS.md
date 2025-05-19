1. changes in repo before running:
- argo-apps/model.yaml: change url line no 9
- fastapi-helm/model-server-1 : storageURI line 23 edit bucket name and path 
- fastapi-helm/model-server-1 : image name line 26  
- fastapi-helm/model-server-2 : storageURI line 23 edit bucket name and path 
- fastapi-helm/model-server-2 : image name line 26 

2. aws console- create three ecr repo all private (check E2EMLOP readme_kubernetes.md)
- a18/ui-server 
- a18/web-server
- model-onnx-server 

3. Readme E2EMLOps - deployment01 
- 
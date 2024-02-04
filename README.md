# kubernetes_manifests
'manifests' directory consists manifests files in 'yaml' format. 
You can use the kubectl create command to create this pod in Kubernetes. Once it is created, you can check its status with kubectl get pods. The output is omitted to save space: 
'''
$ kubectl create -f simple.yaml 
$ kubectl get pods 
$ kubectl get pod firstpod -o yaml 
$ kubectl get pod firstpod -o json
'''
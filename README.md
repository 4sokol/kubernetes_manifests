# kubernetes_manifests
'manifests' directory consists manifests files in 'yaml' format. 
Manifest files run in a non-default namespace 'test-project', you need to create this namespace before you run the pods:
```
kubectl create ns test-project
```
You can use the kubectl create command to create this pod in Kubernetes. Once it is created, you can check its status with kubectl get pods. The output is omitted to save space: 
```
$ kubectl create -f <manifest_file>.yaml 
$ kubectl get pods 
$ kubectl get pod firstpod -o yaml 
```

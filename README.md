# Minio
Mino Object Storage: offer S3 bucket as persistent volume claim to Kubernetes pods

### Instructions to install 
#### `kubectl create -f minio-pvc.yml`
#### `kubectl create -f minio-deployment.yml`
#### `kubectl create -f minio-service.yml`
#### `kubectl port-forward minio-6c84967cd5-bc72w 7000:9000`
#### `kubectl create -f nginx.yml`
#### `kubectl expose deploy nginx-deploy --port 80 --type NodePort`


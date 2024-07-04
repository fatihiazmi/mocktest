# MockTest

### Question 1:
1. `nano storageClass.yaml`
2. `kubectl apply -f storageClass.yaml`

### Question 2:
1. `kubectl create namespace qq3`
2. `nano pv.yaml`
3. `nano pvc.yaml`
4. `kubectl apply -f pv.yaml`
5. `kubectl apply -f pvc.yaml`

### Question 3:
1. `kubectl create namespace qq2`
2. `nano podpv.yaml`
3. `kubectl apply -f podpv.yaml`
4. `nano podpvc.yaml`
5. `kubectl apply -f podpvc.yaml`
6. `nano pod.yaml`
7. `kubectl apply -f pod.yaml`

### Question 4:
1. `kubectl describe nodes controlplane`

   1. `kubectl get pods -n kube-system | grep kube-scheduler`
   2. `kubectl logs -n kube-system kube-scheduler-controlplane`

### Question 5:
1. `nano nginx.yaml`
2. `kubectl apply -f nginx.yaml`

### Question 6:
1. `nano alpine.yaml`
2. `kubectl apply -f alpine.yaml`
3. `kubectl logs -n qq2 -f alpine`

minikube start
docdker login 
token 50e4fa21-d584-4db7-8df0-a965f653a07f


kubectl get deployments 
kubectl delete deployments my-test-app

kubectl get services
kubectl delete services my-app-back-end

docker build -t mattlaw75/my-story-app 
docker push mattlaw75/my-story-app

kubectl apply -f=deployment.yaml -f=service.yaml


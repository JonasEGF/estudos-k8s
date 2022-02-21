Iniciar o kubernetes
minikube start 

Aplicar as configs
cd k8s 
kubectl apply -f . (ou oq for mudar)

Logar no docker
docker login

Gerar imagem docker
docker build -t jonasegf/hello-go:vx.x
docker push mesma coisa 
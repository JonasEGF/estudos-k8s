
### Iniciar o kubernetes

    minikube start 
    
Aplicar as configs

    cd k8s 
    kubectl apply -f . 

#### Gerar imagem docker

    docker build -t jonasegf/hello-go:vx.x
    
    docker push jonasegf/hello-go:vx.x

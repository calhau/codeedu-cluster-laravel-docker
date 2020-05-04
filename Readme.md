## Modulo DevOPS CI/CD

No primeiro commit eu apenas coloquei os arquivos do container Laravel em Docker
e criei as Pasta *K8* com suas respectivas subpastas:  
1.app  
2.mysql  
3.redis  
4.nginx  

No segundo commit apenas adicionei esse arquivo Readme  

## Passo a Passo

1. Executei comando para gerar o MYSQL  
*Necessario criar o secret pass*
- kubectl create secret generic mysql-pass --from-literal=password='a1s2d3f4'  
**Necessario conectar o GCLOUD**

2. Criei o arquivo de deployment do Redis, nele foi incluso a parte de Service tbm  
**Rodar comando para executar deployment do Redis**
- kubectl apply -f . (dentro do diretorio k8s/redis)  










Infra
•	Criar um bucket no armazenamento em nuvem que será usado como armazenamento de artefatos
•	Criar um banco de dados PostreSQL em nuvem SQL que será usado como banco de dados backend mlflow
•	Registrar um contêiner no Artifact Registry, ele hospedará a imagem mlflow definida em mlflow_server/Dockerfile
•	Conta de serviço (e chave json) com acesso aos serviços necessários
•	Criar um cluster kubernetes no GKE
•	Inserir a chave a ser utilizada pelo servidor do MLflow dentro do cluster do kubernetes. 

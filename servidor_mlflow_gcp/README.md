![Infra servidor MLflow]([URL_da_imagem](https://github.com/pedromateusalmeida/using-mlflow-to-deployment-model/blob/main/servidor_mlflow_gcp/servidor_infra.png )
 <br>
Infra <br>
•	Criar um bucket no armazenamento em nuvem que será usado como armazenamento de artefatos <br>
•	Criar um banco de dados PostreSQL em nuvem SQL que será usado como banco de dados backend mlflow <br>
•	Registrar um contêiner no Artifact Registry, ele hospedará a imagem mlflow definida em mlflow_server/Dockerfile <br>
•	Conta de serviço (e chave json) com acesso aos serviços necessários
•	Criar um cluster kubernetes no GKE <br>
•	Inserir a chave a ser utilizada pelo servidor do MLflow dentro do cluster do kubernetes.  <br>
 <br>
Exemplo 2
 ![exemplo 2]([URL_da_imagem]([https://github.com/pedromateusalmeida/using-mlflow-to-deployment-model/blob/main/servidor_mlflow_gcp/servidor_infra.png](https://github.com/pedromateusalmeida/using-mlflow-to-deployment-model/blob/main/servidor_mlflow_gcp/servidor_infra_funcionamento.png )

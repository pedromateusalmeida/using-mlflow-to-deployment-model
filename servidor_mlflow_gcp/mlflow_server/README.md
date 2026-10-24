### mlflow server

- Create a container that is running the mlflow server.
  ```shell
  docker build -t imscientist/mlflow:0.1 .
  ```

- Test:
  ```shell
  docker run -it --rm --name mlflow_test -p 8080:5000 \
    imscientist/mlflow:0.1 /bin/bash -c "mlflow server --host 0.0.0.0"
  ```

  - Criar o conteiner no Artifact Registry:
  ```shell
  docker run -it --rm --name mlflow_test -p 8080:5000 imscientist/mlflow:0.1 /bin/bash -c "mlflow server --host 0.0.0.0"

  gcloud builds submit --tag gcr.io/[PROJETO-NAME]/mlflow:0.1

  or 

  docker push gcr.io/[PROJETO-NAME]/mlflow:0.1
  ```




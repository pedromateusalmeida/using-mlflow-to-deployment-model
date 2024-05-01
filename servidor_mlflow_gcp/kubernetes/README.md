### mlflow server

- Credentials on kubernetes.
  ```shell
  kubectl create secret generic gcloud-credentials --from-file=key.json=.\mlflow_credentials\gcloud-credentials.json
  
  kubectl get secrets

  kubectl describe secret gcloud-credentials
  
  
  ```

- Deploy o pod.
  ```
  kubectl apply -f <nome-do-arquivo>.yaml

  ```


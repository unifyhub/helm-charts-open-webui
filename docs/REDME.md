1. Create secret, het `<YOUR_API_KEY>`  from password manager
```bash
kubectl create secret generic openai-api-key --from-literal=api-key=<YOUR_API_KEY> -n open-webui
```

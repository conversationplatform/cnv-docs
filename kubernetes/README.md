# Deploy it on your kubernetes server 

Here is a kustomize "package" to help you test TinyME on your kubernetes infrastructure. 

We use kustomize as a suggestion to help you, but its on you to manually change and deploy.

⚠️ **make sure to**: update the ingress configurations!

```bash
cd kubernetes && kubectl apply -k .
```


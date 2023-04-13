# kyverno-guide

Add kyverno helm repo:
```bash
helm repo add kyverno https://kyverno.github.io/kyverno/
helm repo update
```

Install kyverno:
```bash
helm upgrade -i kyverno kyverno/kyverno \
  --create-namespace \
  --namespace kyverno \
  --version 3.0.0-alpha.1
```

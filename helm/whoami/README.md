```
helm repo add cowboysysop https://cowboysysop.github.io/charts/
helm upgrade --install whoami cowboysysop/whoami -f override.yaml  --version 2.5.1  --namespace whoami  --create-namespace
```

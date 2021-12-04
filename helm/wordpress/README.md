# README
## Use the whole values.yaml , make changes into this file and apply
```
helm upgrade --install wp bitnami/wordpress -f values.yaml --set wordpressPassword=xxx --version 12.1.24
```
## Use default values and override only some values using override.yaml
```
helm upgrade --install wordpress bitnami/wordpress -f override.yaml --set wordpressPassword=xxx --version 12.1.24  --namespace wordpress  --create-namespace
```

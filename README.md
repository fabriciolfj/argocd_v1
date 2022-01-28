# Argocd
- Ferramenta de entrega em um ambiente kubernetes
- argocd faz parte do cluster kubernetes, e em vez de enviar os dados ele puxa as alterações para aplicar.
- argocd pega as alerações de um repositório git
- pode gerenciar vários clusters kubernetes a partir de um cluster master
- faz uso da api cluster do kubernetes, para realizar tal gerenciamento
- da suporte ao helm
- obs: para o control plane dos clusters, precisamos instalar cni plugin e o calico (script encontra-se no projeto)

### Exportando configuração
```
kind export kubeconfig --name nome do cluster
``
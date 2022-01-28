# Argocd
- Ferramenta de entrega de pacotes em um ambiente kubernetes
- pode gerenciar vários clusters kubernetes a partir de um cluster master
- faz uso da api cluster do kubernetes, para realizar tal gerenciamento
- faz entrega de pacotes/manifestos que encontram-se em um repositório git
- da suporte ao helm
- obs: para o control plane dos clusters, precisamos instalar cni plugin e o calico (script encontra-se no projeto)

### Exportando configuração
```
kind export kubeconfig --name nome do cluster
``
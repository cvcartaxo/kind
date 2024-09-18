# Kind (Kubernetes in Docker)

Este repositório contém informações e exemplos para utilizar o **Kind** (Kubernetes in Docker).

## Pré-requisitos

Antes de começar, você precisa ter o seguinte instalado em sua máquina:

- [Docker](https://docs.docker.com/get-docker/)
- [Kind](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)

## Instalação do Kind

Para instalar o **Kind**, basta seguir os comandos abaixo:

### Linux/

```bash
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.20.0/kind-linux-amd64
chmod +x ./kind
mv ./kind /usr/local/bin/kind
```

### Mac/
```bash
brew install kind
```



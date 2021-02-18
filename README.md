# Demo app on Kubernetes (AWS EKS)

## Setup EKS

Install [eksctl](https://github.com/weaveworks/eksctl)

```
curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp

sudo mv /tmp/eksctl /usr/local/bin
```

Create a cluster

```
eksctl create cluster -f cluster.yaml
```

Delete cluster

```
eksctl delete cluster -f cluster.yaml
```

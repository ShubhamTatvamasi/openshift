# openshift

Install openshift client:
```bash
brew install openshift-cli
```

Download openshift installer:
```bash
oc adm release extract --tools quay.io/openshift/okd:4.15.0-0.okd-2024-03-10-010116
```

https://quay.io/repository/openshift/okd?tab=tags&tag=latest

Create new cluster:
```bash
openshift-install create cluster
```

Pull Secret:
```
{"auths":{"fake":{"auth":"aWQ6cGFzcwo="}}}
```

Delete cluster:
```bash
openshift-install destroy cluster
```

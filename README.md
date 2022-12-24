# openshift

Install openshift client:
```bash
brew install openshift-cli
```

Download openshift installer:
```bash
oc adm release extract --tools quay.io/openshift/okd:4.11.0-0.okd-2022-12-02-145640
```

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

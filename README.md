#Prometheus

Documentation

https://docs.vmware.com/en/VMware-Tanzu-Kubernetes-Grid/1.4/vmware-tanzu-kubernetes-grid-14/GUID-packages-prometheus.html#config-table

About 20% down the page you will find this sample yaml in a code block

```
ingress:
  enabled: true
  virtual_host_fqdn: "prometheus.corp.tanzu"
  prometheus_prefix: "/"
  alertmanager_prefix: "/alertmanager/"
  prometheusServicePort: 80
  alertmanagerServicePort: 80
prometheus:
  pvc:
    storageClassName: STORAGE-CLASS
alertmanager:
  pvc:
    storageClassName: STORAGE-CLASS
```

Some samples I found and have added a personal repo.

https://gist.github.com/mehmetcakmaz

test
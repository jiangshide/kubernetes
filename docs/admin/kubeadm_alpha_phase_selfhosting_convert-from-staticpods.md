
Converts a Static Pod-hosted control plane into a self-hosted one.

### Synopsis


Converts a Static Pod-hosted control plane into a self-hosted one.

```
kubeadm alpha phase selfhosting convert-from-staticpods
```

### Options

```
      --cert-dir string        The path where certificates are stored. (default "/etc/kubernetes/pki")
      --config string          Path to a kubeadm config file. WARNING: Usage of a configuration file is experimental!
      --feature-gates string   A set of key=value pairs that describe feature gates for various features.Options are:
CoreDNS=true|false (ALPHA - default=false)
HighAvailability=true|false (ALPHA - default=false)
SelfHosting=true|false (BETA - default=false)
StoreCertsInSecrets=true|false (ALPHA - default=false)
SupportIPVSProxyMode=true|false (ALPHA - default=false)
      --kubeconfig string      The KubeConfig file to use when talking to the cluster. (default "/etc/kubernetes/admin.conf")
```

## anbox-cloud-appliance enable

Enable individual features of the Anbox Cloud Appliance

### Synopsis

Enable individual features of the Anbox Cloud Appliance

Not all features the Anbox Cloud Appliance provides are enabled by
default or you may have chosen to not enable them during the initial
setup. Some features can be enabled after the initial setup with this
command. The following features are currently supported:

* metrics: An authenticated and HTTPS secured Prometheus client endpoint
  to allow external tools to collect metrics from Anbox Cloud

To enable a specific feature you can run

  $ sudo anbox-cloud-appliance enable metrics

This will enable the feature and return once the operation has been
completed.

Please note that enabling certain features may require some internal
services of the Anbox Cloud Appliance to be restarted and causing
operations to be interrupted until they are back running.


```
anbox-cloud-appliance enable [flags]
```

### Examples

```
$ sudo anbox-cloud-appliance enable metrics
```

### Options

```
  -h, --help   help for enable
```

### SEE ALSO

* [anbox-cloud-appliance](anbox-cloud-appliance.md)	 - Anbox Cloud Appliance, bringing Android at scale to any cloud


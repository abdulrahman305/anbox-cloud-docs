## anbox-cloud-appliance disable

Disable individual features of the Anbox Cloud Appliance

### Synopsis

Disable individual features of the Anbox Cloud Appliance

Individual features of the Anbox Cloud Appliance can be disabled if
they have been enabled either during initialization or manually
afterwards. The following features can be disabled:

* metrics: An authenticated and HTTPS secured Prometheus client endpoint
  to allow external tools to collect metrics from Anbox Cloud

To disable a specific feature you can run

  $ sudo anbox-cloud-appliance disable metrics

This will disable the feature and return once the operation has been
completed.

Please note that disabling certain features may require some internal
services of the Anbox Cloud Appliance to be restarted and causing
operations to be interrupted until they are back running.


```
anbox-cloud-appliance disable [flags]
```

### Examples

```
$ sudo anbox-cloud-appliance disable metrics
```

### Options

```
  -h, --help   help for disable
```

### SEE ALSO

* [anbox-cloud-appliance](anbox-cloud-appliance.md)	 - Anbox Cloud Appliance, bringing Android at scale to any cloud


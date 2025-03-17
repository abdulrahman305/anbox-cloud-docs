## ams.amc monitor

Listen for events generated in AMS

### Synopsis

Monitor AMS for events

By default the monitor will listen to all message types.

```
ams.amc monitor [flags]
```

### Options

```
      --format string   Output format - 'json' or 'yaml' (default "yaml")
  -h, --help            help for monitor
  -t, --type string     Comma-separated filters for events types - 'lifecycle', 'logging', 'operations' or 'all' (default "all")
```

### SEE ALSO

* [ams.amc](ams.amc.md)	 - Anbox Management Client


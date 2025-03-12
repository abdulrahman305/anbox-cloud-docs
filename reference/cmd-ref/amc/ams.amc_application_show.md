## ams.amc application show

Show information about a specific application

### Synopsis

Show information about a specific application.

Formatting can be controlled with the '--format' flag.
Valid formats are 'json' and 'yaml'.

```
ams.amc application show <id> [flags]
```

### Examples

```
$ amc application show foo
id: bkmtdm9hpuo01q954fng
name: foo
status: ready
published: true
immutable: false
vm: false
inhibit-auto-updates: false
parent-image: jammy:android13:amd64
parent-image-variant: android
tags: []
config:
  instance-type: a2.3
  boot-package: com.android.foo
versions:
  0:
    image: bkkbiaphpuo3mh78ain0 (version 0)
    manifest-version: 0.1
    published: true
    status: active
    extra-data: {}

```

### Options

```
      --format string   Output format - 'json' or 'yaml' (default "yaml")
  -h, --help            help for show
```

### SEE ALSO

* [ams.amc application](ams.amc_application.md)	 - Manage applications


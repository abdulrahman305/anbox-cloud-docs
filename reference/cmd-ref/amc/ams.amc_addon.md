## ams.amc addon

Manage addons

### Synopsis

Manage addons.

Addons are a way of customising the images that are used as the base for containers.

Basically, an addon is a tarball that provides several hooks and additional metadata.
An example for an addon is one that enables the SSH service inside a container, to
provide access from the outside for any kind of automation of the container.

See https://documentation.ubuntu.com/anbox-cloud/en/latest/explanation/addons/ for more information.

### Options

```
  -h, --help   help for addon
```

### SEE ALSO

* [ams.amc](ams.amc.md)	 - Anbox Management Client
* [ams.amc addon add](ams.amc_addon_add.md)	 - Add an addon
* [ams.amc addon delete](ams.amc_addon_delete.md)	 - Delete an existing addon
* [ams.amc addon list](ams.amc_addon_list.md)	 - List available addons
* [ams.amc addon show](ams.amc_addon_show.md)	 - Show more information about a specific addon
* [ams.amc addon update](ams.amc_addon_update.md)	 - Update an existing addon


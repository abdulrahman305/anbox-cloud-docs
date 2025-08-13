## ams.amc auth identity list

List identities

### Synopsis

List identities.

Formatting can be controlled with the '--format' flag.
Valid formats are 'table' (see example), 'json' and 'csv'.

You can apply filters to narrow down the list of instances.
They are of the following form:

	--filter attribute=value

'attribute' can be one of the following:

	+--------+---------------------------------+
	|  Name     |      Argument type           |
	+--------+---------------------------------+
	| id        | string (identity id)         |
	| auth_type | string (tls or oidc)         |
	+--------+---------------------------------+ 

```
ams.amc auth identity list [flags]
```

### Examples

```
$ amc auth identity ls

	+----------------------+------------------------+
	|          ID          | AUTHENTICATION TYPE 	|
	+----------------------+------------------------+
	| bknj0n9hpuo01q954fq0 | oidc                   |
	+----------------------+------------------------+

$ amc auth identity list --filter auth_type=oidc
```

### Options

```
  -f, --filter stringArray   Filter the output based on conditions (for example, 'status=running')
      --format string        Output format -'table', 'json' or 'csv' (default "table")
  -h, --help                 help for list
```

### SEE ALSO

* [ams.amc auth identity](ams.amc_auth_identity.md)	 - Manage authentiation & authorization


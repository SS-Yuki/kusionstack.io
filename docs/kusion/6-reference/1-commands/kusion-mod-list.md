## kusion mod list

List kusion modules in a workspace 

```
kusion mod list [--workspace WORKSPACE] [flags]
```

### Examples

```
  # List kusion modules in the current workspace
  kusion mod list
  
  # List modules in a specified workspace
  kusion mod list --workspace=dev
```

### Options

```
      --backend string     The backend to use, supports 'local', 'oss' and 's3'.
  -h, --help               help for list
  -w, --workdir string     The work directory to run Kusion CLI.
      --workspace string   The name of target workspace to operate in.
```

### Options inherited from parent commands

```
      --profile string          Name of profile to capture. One of (none|cpu|heap|goroutine|threadcreate|block|mutex) (default "none")
      --profile-output string   Name of the file to write the profile to (default "profile.pprof")
```

### SEE ALSO

* [kusion mod](kusion-mod.md)	 - Manage Kusion modules

###### Auto generated by spf13/cobra on 12-Jun-2024
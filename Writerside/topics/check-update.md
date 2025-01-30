# check-update

`check-update` checks for any updates to NativePHP. It verifies the version you have installed against
the version that is available. If there is a newer version available, it will let you know.

This command will not perform an update.

## Command

Syntax:

```shell
nativecli check-update [OPTIONS]
```

## Options

Describe what each option is used for:

-f, --format
: By default, update status is output in `text`. For progrmatic use, `json` is also a valid option:

: ```nativecli check-update --format json```

<seealso>
    <a href="update.md" />
</seealso>
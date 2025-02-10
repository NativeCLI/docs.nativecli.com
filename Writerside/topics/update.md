# update

This command will perform any available updates to NativePHP on your behalf.
After checking for updates, you;ll be prompted to confirm you want to go ahead.

<warning>If you use the --non-interactive flag, you will not be prompted. The update will be completed immediately.</warning>

## Command

Syntax:

```shell
nativecli update [OPTIONS]
```

## Options

-n, --non-interactive
: Provides a non-interactive experience, suitable for CI. Updates are processed immediately to the
latest available version.

<seealso>
    <a href="check-update.md" />
</seealso>
# self-update

This command provides an easy way to ensure that NativeCLI is always kept up to date.

<tip>
This command is only available in NativeCLI version 1.0.0-release.1 and later.
</tip>

## Command

Syntax:

```shell
nativecli self-update [VERSION]
```

## Options

<tip>All options are only available since v1.0.1-release.1</tip>

-f, --format
: By default, update status is output in `text`. For programmatic use, `json` is also a valid option:

: ```nativecli self-update --format json```

--check
: Check for updates without updating.

## Examples

Update to the latest stable version:

```shell
nativecli self-update
```

Update to a specific version:

```shell
nativecli self-update 1.0.0-beta.2
```

<seealso>
    <!--Provide links to related how-to guides, overviews, and tutorials.-->
</seealso>
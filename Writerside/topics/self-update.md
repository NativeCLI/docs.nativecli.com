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

Describe what each option is used for:

Version
: No flag required. If a version is specified, NativeCLI will attempt to update to that version. If no version is specified, NativeCLI will update to the latest stable version.

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
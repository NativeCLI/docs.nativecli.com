# Configuration

<tip>
Configuration is available from version 1.0.3.
</tip>

NativeCLI provides a way to configure certain behaviours within the application.

You are able to configure both a global configuration and a local, project-specific configuration.

## Global Configuration

## Command

Syntax:

```shell
nativecli config --global [KEY] [VALUE]
```

## Local Configuration

Syntax:

```shell
nativecli config [KEY] [VALUE]
```

<tip>
Note the only difference is the `--global` flag.
</tip>

## Options

Describe what each option is used for:

-g, --global
: Sets a global configuration option. This will affect all projects where a local configuration has not overridden it.

## Available Configuration Options
updates.check
: This option controls whether NativeCLI will check for updates when it is run. The default is `true`.

updates.auto
: This option controls whether NativeCLI will automatically update itself when a new version is available. The default is `false`.

## Examples

Set the global configuration option `updates.check` to `false`:

```shell
nativecli config --global updates.check false
```
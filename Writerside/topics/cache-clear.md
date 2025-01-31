# cache:clear

NativeCLI uses some files to cache data that does not need to be retrieved on every invocation.
Sometimes, it may be preferable to clear these caches to ensure that the latest data is used.

<tip>
This command is only available in NativeCLI version 1.0.0-rc.1 and later.
</tip>

## Command

Syntax:

```shell
nativecli cache:clear [OPTIONS]
```

## Options

Describe what each option is used for:

-c, --cache
: Select a specific cache to clear. If not specified, all caches will be cleared.

-n, --non-interactive
: Clears the specified caches without prompting for confirmation.

## Available Caches

A cache is only considered "available" once it has data within. If the cache doesn't yet exist, you'll receive a
message indicating that the cache is empty.

version
: The latest versions of NativeCLI and NativePHP that are available. This cache expires hourly.
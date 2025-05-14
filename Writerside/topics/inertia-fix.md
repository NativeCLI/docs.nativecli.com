# inertia:fix

<warning>
This command was temporarily added whilst awaiting a blocking change to be merged into the InertiaJS repository.

This command was added in version 1.1.2 and was subsequently removed in version 1.2.0.
</warning>

This command is provided to assist those using [NativePHP for Mobile](https://nativephp.com/mobile) to fix the ongoing InertiaJS issue with the `nativecli` command.

This command will remove the `@inertiajs/*` package from your project and then re-install it from a [patch provided by Marcel Pociot](https://github.com/inertiajs/inertia/pull/2329).

## Command

Syntax:

```shell
nativecli inertia:fix
```

## Options

There are no options provided for this command.

<seealso>
    <category ref="external">
       <a href="https://github.com/inertiajs/inertia/pull/2329">"Allow custom URL protocols" PR by Marcel Pociot</a>
   </category>
</seealso>
# New

The `new` command is probably the first one you'll ever use.

This command will install Laravel into the provided directory name and then install NativePHP, ready to go for you.

## Command

Syntax:

```bash
nativecli new <directory-name>
```

## Options

--ios
: Indicates whether the project should be set up for iOS development, instead of Desktop.

--dev
: Installs the latest "development" release.

--git
: Initialize a Git repository.

--branch
: The branch that should be created for a new repository (default: main).

--github
: Create a new repository on GitHub.

--organization
: The GitHub organization to create the new repository for.

--database
: The database driver your application will use.

--react
: Install the React Starter Kit

--vue
: Install the Vue Starter Kit

--livewire
: Install the Livewire Starter Kit

--livewire-class-components
: Generate stand-alone Livewire class components

--workos
: Use WorkOS for authentication

--pest
: Installs the Pest testing framework.

--phpunit
: Installs the PHPUnit testing framework.

--npm
: Install and build NPM dependencies

--using
: Install a custom starter kit from a community maintained package

--force, -f
: Forces install even if the directory already exists.
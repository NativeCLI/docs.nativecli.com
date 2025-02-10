# New

The `new` command is probably the first one you'll ever use.

This command will install Laravel into the provided directory name and then install NativePHP, ready to go for you.

## Command

Syntax:

```bash
nativecli new <directory-name>
```

## Options

<tip>The options below are only available from version 1.0.1-release.1 and later.</tip>

--ios
: Indicates whether the project should be set up for iOS development, instead of Desktop.

<tip>The options below are available since the first version.</tip>

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

--stack
: The Breeze / Jetstream stack that should be installed.

--breeze
: Installs the Laravel Breeze scaffolding.

--jet
: Installs the Laravel Jetstream scaffolding.

--dark
: Indicate whether Breeze or Jetstream should be scaffolded with dark mode support.

--typescript
: Indicate whether Breeze should be scaffolded with TypeScript support.

--eslint
: Indicate whether Breeze should be scaffolded with ESLint and Prettier support.

--ssr
: Indicate whether Breeze or Jetstream should be scaffolded with Inertia SSR support.

--api
: Indicates whether Jetstream should be scaffolded with API support.

--teams
: Indicates whether Jetstream should be scaffolded with team support.

--verification
: Indicates whether Jetstream should be scaffolded with email verification support.

--pest
: Installs the Pest testing framework.

--phpunit
: Installs the PHPUnit testing framework.

--force, -f
: Forces install even if the directory already exists.
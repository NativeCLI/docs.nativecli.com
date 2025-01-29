# Start a New NativePHP Project

This tutorial assumes that you have already followed the [Installation](Installation.md) guide.

## Before you start

Make sure that:
- NativeCLI has been [installed](Installation.md). 
- NativeCLI is in your path and available for use:
  ```bash
  nativecli --version 
  Output: NativePHP CLI Tool 1.0.0-alpha.1
  ```

## Starting a new NativePHP Project

At this time, NativePHP only supports Laravel. For this reason, so does NativeCLI.

NativeCLI utilises Laravels Installer library. This means that any arguments available within that is also available within NativeCLI.

<tip>
    This tutorial assumes that you will be creating your project in a ~/Code directory in your user home.
</tip>

1. Execute the following command in the terminal:

   ```bash
   cd ~/Code
   nativecli new MyFirstProject
   ```
   
   <img src="new_command.png" alt="New Command Example" />

2. You'll be prompted to select some options from the Laravel installer. Choose your favourites!

   ![laravel_prompt.png](laravel_prompt.png)

3. That's it! you'll find a new folder with your project name. It includes everything you need to get started.

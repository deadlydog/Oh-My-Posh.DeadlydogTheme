# Deadlydog Oh My Posh Theme

## Description

This is a custom theme for [Oh My Posh](https://ohmyposh.dev), called `deadlydog`.

## Why this exists

I wasn't quite happy with [the out-of-the-box themes](https://ohmyposh.dev/docs/themes), so I created this one.

## Quick start

To use this theme:

1. [Install Oh My Posh](https://ohmyposh.dev/docs/windows) if you haven't already.
1. Download the [deadlydog.omp.json theme file](src/deadlydog.omp.json) to your computer.
1. [Set the theme in Oh My Posh](https://ohmyposh.dev/docs/windows#replace-your-existing-prompt).

   - The command will vary depending on which shell you are in.
   - You will need to change the file path to where you saved the `deadlydog.omp.json` file on your computer.
   - In PowerShell it would look something like:

   ```powershell
   oh-my-posh --init --shell pwsh --config $env:POSH_THEMES_PATH/deadlydog.omp.json | Invoke-Expression
   ```

   Or if you have installed the PowerShell module using `Install-Module oh-my-posh`, you can use the command:

   ```powershell
   Set-PoshPrompt -Theme $env:POSH_THEMES_PATH/deadlydog.omp.json
   ```

## Changelog

See what's changed in the application over time by viewing [the changelog](Changelog.md).

## Donate

Buy me a donut for providing this theme open source and for free :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/deadlydogDan/5USD)

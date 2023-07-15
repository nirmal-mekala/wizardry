# Wizardry 🧙🏾‍♂️

> A great and powerful ~~script~~ **spell** for configuring macOS. Forked from [formation](https://github.com/minamarkham/formation).

<div align="center">
    <img src="assets/oz.jpg" alt="The Wizard of Oz"/>
</div>

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages based on what is already installed on the machine.

## Customization

> Because there’s no place like `~`.

This script is designed to be _customized_. As is, `customizations` clones and configure _my_ [dotfiles](https://github.com/ndmekala/dotfiles) _my_ macOS preferences—including setting a [seasonal desktop background](https://github.com/ndmekala/bgs).

## What It Installs

This script installs my favorite GUI and CLI utilities, apps, text editors, IDEs, fonts as a front-end SWE. Browse through the `installs` directory to see what it includes.

## Running

Read through the scripts before running so you know what’s going on.

If you’re feeling lucky, you can simply run:

```sh
./imperio
```
Or, to run and save output:

```sh
./imperio 2>&1 | tee ~/imperio.log
```

## Known Issues

Cask does not recognize applications installed outside of Homebrew Cask – in the case that the script fails, you can either remove the application from the install list or uninstall the application causing the failure and try again.

## Acknowledgements

This script is a fork of [formation](https://github.com/minamarkham/formation). It also draws from…
- [Mathias Bynens'](https://github.com/mathiasbynens) [dotfiles](https://github.com/mathiasbynens/dotfiles) (particularly with `macos`)
- thoughtbot's [laptop](https://github.com/thoughtbot/laptop/)

Also, wizards of all stripes…
<div align="center">
    <img src="assets/patil-twins.jpeg" alt="The Patil twins from the Harry Potter films"/><br/><br/>
    <img src="assets/gandalf-and-radagast.jpg" alt="Gandalf and Radagast from Lord of the Rings"/><br/><br/>
    <img src="assets/mj.jpeg" alt="Michael Jordan on the Washington Wizards"/>
</div>


## Automate

Set up a developer Arch Linux laptop in 40 minutes or less without any manual input. This repo uses ansible to set up my custom Arch Linux environment. You can easily tweak it for your distro with some research.

You can either use this repo as inspiration or use it outright. You can change the ssh variables and use your own dotfiles, or mine through HTTPS.

## What I use

You can go [here](https://github.com/cmpi66/dotfiles) to get a preview of what I use. Basically, I use a window manager (DWM) and almost exclusively terminal-based applications. Everything is keyboard-driven and if it can be scripted or automated it will be. I use a lot of the same tools [Luke Smith](https://github.com/lukesmithxyz) and [ThePrimeagen](https://github.com/ThePrimeagen) use. I took heavy inspiration from both into creating my own ansible set up. Luke has a bash [script](https://larbs.xyz/) and Primeagen has [ansible](https://github.com/ThePrimeagen/ansible).

After asnible is done, the computer is ready to use. It has all the tools a developer would need for their workflow. If you do use my dotfiles, then be mindful my Neovim config is BROKEN, I use Lunarvim, so you would have to install that yourself, it can't be automated with ansible. The nvim command is also aliased to lvim.

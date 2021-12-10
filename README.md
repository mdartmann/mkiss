# mkiss

> A KISS Linux repository for daily driving

## What is this?

This is a repository for the KISS Linux packaging system. It provides scripts
for reproducible compilation of open-source packages.

## Why create your own if other repositories exist?

I personally need certain software for my work that most other repositories
either can't provide at all or only to a limited extent. I also have a few
non-standard preferences in my scripts.

## Directory structure

This repository includes three folders:

- `core` for core system utilities, such as compilers, the libc and coreutils
- `extra` for extra utilities useful in daily use
- `gui` for graphical applications, such as the Sway window manager, and their back-end

## Contributions

Contributions are welcome, as long as they:

- aren't a very niche edge case
- follow a similar programming style as my scripts
- are reproducible with the flags found in my [mkissconfig repository](https://github.com/mdartmann/mkissconfig)

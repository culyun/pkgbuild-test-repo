# Test repository for hosting PKGBUILD packages

## Background

The Arch Linux development community use pacman and friends for managing package deployment and installation.

Pacman is orthoganal to Arch Linux, which means that it can be used in other contexts.
For instance, pacman is used as the package manager on MSYS2, which isn't even Linux.

The intention of this repository is experimentation.

In the first instance I want to try adding the repository to a running Arch Linux system.
My plan is to add a dummy package to the repository, install it, and learn how the system can manage it.

My hope is that I can use this approach to augment any Linux (or Unix-like) system to support the installation of proprietry packages.

The reason for selecting pacman is:
 (a) low system requirements,
 (b) ongoing and extensive upstream development,
 (c) the fact that it can exist orthoganal to other package managers

Well, these are the claims.

Let's see how it goes.

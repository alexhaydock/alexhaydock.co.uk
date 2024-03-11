### Hi, I’m Alex. 👋

I currently work as a Security Engineer in the UK energy sector.

Here you'll find a few of my interesting projects. _Please_ don't rely on them for anything mission critical, but do feel free to look around! 😄

#### [pinewall](https://github.com/alexhaydock/pinewall)
This is my custom Alpine Linux router spin. I've been running this in production as my core (home!) internet gateway since mid-2021. It runs entirely from RAM on a Raspberry Pi 4 using images entirely built within GitLab CI, and leverages Alpine's [LBU](https://wiki.alpinelinux.org/wiki/Alpine_local_backup) functionality to overlay configs.

#### [goldenblue](https://github.com/alexhaydock/goldenblue)
This is my personal "golden image" spin of the immutable [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/). It's also built entirely within GitLab CI, and is heavily inspired by the [Universal Blue](https://universal-blue.org/) project. I've been running this as my "daily driver" since Fedora 38 and it's been working very well for that purpose.

#### [install-gentoo](https://github.com/alexhaydock/install-gentoo)
Okay, this one is... not so serious. This is my attempt at building an end-to-end build process for a (mostly) entirely hands-free Stage 3 tarball install of Gentoo Linux using an Ansible playbook. Shockingly it does actually work.

#### [zfs-on-wsl](https://github.com/alexhaydock/zfs-on-wsl)
The default WSL kernel from Microsoft doesn't support ZFS, so this is a hacky set of poorly-updated shell scripts to build a custom kernel with the right modules enabled. I don't use Windows all that often so this doesn't get a lot of attention. Maybe one day I'll rework this as an actual Debian package.

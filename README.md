# distrib-dl

Download and keep up-to-date Linux distribution ISO images/installers.  
Downloads will be verified against checksums and GPG keys.  
Useful to maintain a local ISO image repository.  

## Installation

`git clone https://github.com/nodiscc/distrib-dl`

## Requirements

 * bash
 * wget
 * gnupg

## Usage

```
./distrib-dl DISTRIBUTION1 [DISTRIBUTION2 DISTRIBUTION3 ...]
Available distributions: debian centos tails kali proxmox pfsense
```

* [Debian GNU/Linux](https://www.debian.org/)
* [CentOS](https://www.centos.org/)
* [Tails](https://tails.boum.org/)
* [Kali](https://www.kali.org/)
* [Proxmox VE](https://pve.proxmox.com/wiki/Main_Page)
* [pfSense](https://www.pfsense.org/download/)


## Configuration

Architectures and distribution versions are configurable in the script itself.

## Contributing/testing/support

 * Patches and pull requests welcome.
 * File bugs or possible improvements at https://github.com/nodiscc/distrib-dl/issues
 * Run `shellcheck` against the script to check for errors/styling issues.

## TODO

* add support for bittorrent downloads (transmission-cli?)
* automatically check for new versions of distributions (RSS feeds?)
* support other distros (arch/ubuntu/mint/zorin/alpine/android-x86/fedora/dban/gentoo...)
* support downloading via bittorrent/transmission-cli
* centos: do not hardcode mirror, let centos.org take us to the closest download
* add support for android-x86
* add support for Debian Live
* add support for [Arch Linux](https://www.archlinux.org/)
* add support for [GuixSD](https://www.gnu.org/software/guix/)
* add support for [NixOS Linux](https://nixos.org/)
* add support for [Gentoo Linux](https://www.gentoo.org/)
* add support for [Fedora](https://getfedora.org/)
* add support for [Ubuntu](https://www.ubuntu.com/)
* add support for [FreeBSD](https://www.freebsd.org/)
* add support for [OpenBSD](https://www.openbsd.org/)
* add support for [Lakka](https://www.lakka.tv/)
* add GPG/checksum verifications for proxmox
* add support for windows 10
* Integrate with https://github.com/thias/glim
* add support for debian netinstall to glim
* add support for tails and centos in main glim grub configuration
* add support for debian live including non-free firmware https://cdimage.debian.org/images/unofficial/non-free/images-including-firmware/current-live/

## License

[MIT](https://opensource.org/licenses/MIT)
PLEASE CONTRIBUTE BACK TO THE ORIGINAL PROJECT , THIS IS A MODIFIED VERSION. :)

 * File bugs or possible improvements at https://github.com/nodiscc/distrib-dl/issues

# distrib-dl

Download and keep up-to-date Linux/BSD distribution ISO images/installers.  
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


Available distributions: 
                         debian
                         freebsd
                         slackware_current
                         archlinux
                         opensuse_tumbleweed
                         ubuntu
                         voidlinux
                         nixos
                         fedora
                         solus
                         clearlinux



## Configuration

Architectures and distribution versions are configurable in the script itself.


## License

[MIT](https://opensource.org/licenses/MIT)
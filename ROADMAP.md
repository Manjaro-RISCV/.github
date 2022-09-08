# Porting Status

- OK
- WIP: Work in progress
- ARCH: From Arch Linux / Arch Linux RISC-V
- FAIL

Most packages following Arch Linux are not shown here.

## Core

| Name                  | Status | Notes                                   |
| :-------------------- | :----- | :-------------------------------------- |
| linux                 |        | Need specific kernel for specific board |
| base                  | OK     |                                         |
| filesystem            | OK     |                                         |
| gcc                   | ARCH   |                                         |
| glibc                 | ARCH   |                                         |
| bash                  | OK     |                                         |
| bash-completion       | ARCH   | in Archlinx/Extra                       |
| pacman                | OK     |                                         |
| pacman-mirrorlists    | OK     | to be replaced by `pacman-mirrors`      |
| systemd               | OK     |                                         |
| lsb-release           | OK     |                                         |
| manjaro-riscv-keyring | OK     |                                         |
| manjaro-release       | OK     |                                         |
| manjaro-system        | WIP    |                                         |

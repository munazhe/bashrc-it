# bashrc-it
~/.bashrc snippets for Pi lovers, CLI monks and cypher punks...enjoy!

## Dependencies:
* rsync >= 3.2.3
* sshfs >= 3.7.1
* fuse >= 3.10.1

## Tested on:
  * **Distro**: Headless arch-based linux (NO GUI)
  * **Kernel**: `5.10.10-zen1-1-zen` **arch** `x86_64`


## Install

### For linux
1. `git clone https://github.com/munazhe/bashrc-it && cd bashrc-it && cat bashrc-it > ~/.bashrc-it`
2. `echo "source ~/.bashrc-it" >> ~/.bashrc`



#### Commands() list
* `plug` ==> Mount network drives to localally (sshfs)
* `maskon` ==> Spoof NIC MAC address on the fly (bypass fingerprinting)
* `reload` ==> A `source ~/.bashrc` for the lazy
* `sync` ==> Synchronize folders and network drives while skipping duplicates
* `link` ==> Quick alias for  ssh-ing into remote server


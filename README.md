# bashrc-it
~/.bashrc snippets for Pi lovers, CLI monks and cypher punks...enjoy!

## Dependencies:
* rsync >= 3.2.3
* sshfs >= 3.7.1
* fuse >= 3.10.1



## Install

### For linux
1. `git clone https://github.com/munazhe/bashrc-it`
2. `cd bashrc-it`
3. `bash install`


### For Mac
**coming soon...**


#### Commands() list

* `net`
* `plug`
* `maskon`
* `power`
* `reload`
* `sync`
* `netup`
* `nowite`
* `link` 



#### `fcp` 

**Seach and copy files with `find`**

 By default the `fcp` command
 will only search within the
 folder you're current in
 for instance, to search dog photo
 with the extention '.jpg'
 you'd type:
 fcp "*dog*.jpg" /home/user/pics


#### `sch`

**Seach files and return their location**

  By default `sch` will only serach 
  within your current `dir` 
  otherwise you can specify a 
  different `dir` from the default
  like this: 
  `sch 'search term' ./custom_dir`

  or the default: 
  `sch 'serch term'`

  NOTE: the spaces in your `$sch_term`
        will all be replaced with wild
        card patterns to match the 
        the keywords more accuratly

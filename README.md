# mktree, print a tree of dependencies from GNU make

'mktree' assembles the dependency tree from make's debugging information, and prints it. It runs 'make' in dry-run mode, and all the parameters after 'mktree --'.

## Installation
```
wget https://raw.githubusercontent.com/daimh/mktree/master/mktree
chmod +x mktree
mv mktree ~/bin/ # or any directory in PATH
```

## Try out
```
wget https://raw.githubusercontent.com/daimh/mktree/master/Makefile
mktree
touch tc
mktree
mktree -a
mktree -a -- -B
mktree -- t1 t2
```

## Help
```
mktree -h
```

## Contribute

Contributions are always welcome!

## Copyright

Developed by Manhong Dai

Copyright © 2021 University of Michigan

License [GPLv3](https://gnu.org/licenses/gpl.html): GNU GPL version 3

This is free software: you are free to change and redistribute it.

There is NO WARRANTY, to the extent permitted by law.

## Acknowledgment

Ruth Freedman, MPH, former administrator of MNI, UMICH

Fan Meng, Ph.D., Research Associate Professor, Psychiatry, UMICH

Huda Akil, Ph.D., Director of MNI, UMICH

Stanley J. Watson, M.D., Ph.D., Director of MNI, UMICH

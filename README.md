# maketree, print a tree of dependencies from GNU make

maketree calls 'make' in dry-run mode, assmebles a tree structure from make's debugging information, and prints it

## Try out
```
git clone https://github.com/daimh/maketree.git
cd maketree
./maketree -f TestMakefile
./maketree -f TestMakefile t1 t2
./maketree -f TestMakefile t2 t1
```

## Help
```
maketree -h
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

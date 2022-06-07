# My suckless utilities configuration 

## How to patch?
```bash
make && sudo make clean install
make clean && rm -f config.h
patch -p1 < 0001-whatever.patch
make && sudo make clean install
make clean && rm -f config.h
```
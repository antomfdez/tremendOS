# tremendOS

tremendOS kernel i made for learning osdev.

### Compile
```
# docker daemon
sudo dockerd

# building environment
sudo docker build buildenv -t OS-build

# run
sudo docker run --rm -it -v .:/root/env OS-build

# recompile inside docker
make build-x86_64
```
### Iso in: 
```dist/x86_64/kernel.iso``` (already compiled)

### Write the iso in a usb: 
```dd if=dist/x86_64/kernel.iso of=/dev/<usb>```


## Screenshots

![App Screenshot](https://github.com/antomfdez/tremendOS/blob/main/os.png)

# CMU 15-213 ICS

Follow CMU 15-213 courses and complete the labs. alias CSAPP.

## Environments

Globally, I use `vagrant` to start a Ubuntu 16.04 virtual machine on Mac OS X. To start the vm, you need

- vagrant
- virtualbox

and

```
git clone https://github.com/JasonQSY/CMU-15-213-ICS.git && cd CMU-15-213-ICS
vagrant up
vagrant ssh
```

in the virtual machine

```
sudo apt update
sudo apt install build-essential

# For lab2 - bomb lab
sudo apt install binutils
sudo apt install gdb
```

## Progress

- [x] Lab 1 - Data Lab
- [x] Lab 2 - Bomb Lab
- [ ] Lab 3 - Attack Lab
- [ ] Lab 4 - Cache Lab
- [x] Lab 5 - Shell Lab
- [ ] Lab 6 - Malloc Lab
- [ ] Lab 7 - Proxy Lab

## Reference

- [CSAPP Lab Assignments](http://csapp.cs.cmu.edu/3e/labs.html)
- [15-213/18-213/15-513: Introduction to Computer Systems (ICS)](http://www.cs.cmu.edu/~./213/)

# Bomb Lab

Since I do the lab on OS X, my solution is to use a vagrant vm. To start it, you need a `vagrant`. After that

```
vagrant up
vagrant ssh
```

wait for `ubuntu/xenial64` to start. And to initialize the env,

```
sudo apt install build-essential
sudo apt install binutils
sudo apt install gdb
```

Now just type

```
cd /vagrant
./bomb psol.txt
```

to start the lab.

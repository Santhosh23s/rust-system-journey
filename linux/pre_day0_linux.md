# Linux Command to Pratice Day 0
- ls -al
```bash
santhosh@sandev:~/Documents/rust-systems-journey$ ls -al
total 36
drwxrwxr-x 6 santhosh santhosh 4096 Dec 19 22:17 .
drwxr-xr-x 4 santhosh santhosh 4096 Dec 19 21:22 ..
-rw-rw-r-- 1 santhosh santhosh  164 Dec 19 21:25 Cargo.lock
-rw-rw-r-- 1 santhosh santhosh   91 Dec 19 21:25 Cargo.toml
drwxrwxr-x 8 santhosh santhosh 4096 Dec 19 22:30 .git
-rw-rw-r-- 1 santhosh santhosh    8 Dec 19 21:25 .gitignore
drwxrwxr-x 2 santhosh santhosh 4096 Dec 19 22:37 linux
drwxrwxr-x 3 santhosh santhosh 4096 Dec 19 21:25 src
drwxrwxr-x 4 santhosh santhosh 4096 Dec 19 21:25 target 
```
- pwd
```bash 
pwd
/home/santhosh/Documents/rust-systems-journey
```
- ps aux | head
```bash
santhosh@sandev:~/Documents/rust-systems-journey$ ps aux | head
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.1  23168 14212 ?        Ss   08:27   0:05 /usr/lib/systemd/systemd --system --deserialize=58 splash
root           2  0.0  0.0      0     0 ?        S    08:27   0:00 [kthreadd]
```
- grep -R "rust" /usr
``` bash
grep -R "linux" linux
linux/pre_day0_linux.md:drwxrwxr-x 2 santhosh santhosh 4096 Dec 19 22:37 linux
```
### developing mtx operating system on qemu-i386 in ubuntu16.04
sudo apt-get install qemu

run first booter program on ssh terminal mode

qemu-system-i386 -fda mtx.raw -boot a -no-fd-bootchk -display curses

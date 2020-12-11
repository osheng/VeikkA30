### Linux Installation instructions for Veikk A30 driver

Find the latest version of the driver with
```
git clone https://github.com/jlam55555/veikk-linux-driver
```
Then in the cloned repo do the following commands. Note that 
`sudo modprobe veikk` requires Secure Boot to be disabled.

```
make
sudo depmod
sudo modprobe veikk
sudo make all install clean
```
#### For more see
https://www.youtube.com/watch?v=8ahR8RGj7xA
https://github.com/jlam55555/veikk-linux-driver/issues/16

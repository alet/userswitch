# UserSwitch
Switch from any windom manager to GDM login page
## Installing
Compile and copy to somewere in path:
```sh
sudo apt install libgdm-dev
gcc -Wall -o userswitch `pkg-config --cflags --libs glib-2.0` userswitch.c -lgdm -lglib-2.0 -lgio-2.0
cp userswitch ~/bin/
```

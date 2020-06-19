Jupyter-loader
==============
A shortcut using which you can load your conda environments in any directory with minimal GUI support


### Steps for Ubuntu

- Changing permissions, owner and group of the script

```bash
sudo su
chmod 755 jupyter-script
chown root:root jupyter-script
cp jupyter-script /usr/bin/jupyter-script
```

- Add shortcut key in `Settings > Devices > Keyboard` to execute following command

```bash
gnome-terminal -e /usr/bin/jupyter-script
```
I have used F6 key

<img src="https://github.com/samhilmw/Jupyter-loader/blob/master/Shortcut.png?raw=true" height=250px width=400px>

and you are good to go..!!

Now you can use this key to quickly use jupyter 

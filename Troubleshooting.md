### Cleaning unused packages:
using apt is okay `apt autoremove`
`pkg remove --autoremove` will also work


### Completely removing a package:
The main difference is that
`apt remove` deletes the package binaries but leaves the configuration files behind, while `dpkg purge` (or apt purge) removes everything, including the configuration files

* very useful for dealing with occasional termux package bugs

```sh
sudo dpkg --purge <package_name>
# or the shorthand
sudo dpkg -P <package_name>
```


### Fix broken hw (update the shell engine):
First update the shell script by running `setup-termux-desktop` then do the `setup-termux-desktop --change hw`

for best performance for snapdragon 8 gen 2
    - Option 1 -> 6 (Mesa Zink Native) for Native Termux Desktop & Turnip for  proot

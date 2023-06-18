<img src="https://media.discordapp.net/attachments/1120037318611439670/1120073329064300544/aanjaOS_Banner_I_want_to_copy_HentaiOS_and_Evolution_X_at_the_same.png?width=993&height=559">

# aanjaOS

 Getting Started
---------------
To get started with the aanjaOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

bash
repo init -u https://github.com/aanjaOS/manifest.git -b 13.1 --git-lfs

Then sync up:

bash
repo sync

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

``` bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

``` bash
lunch aanja_devicecodename-buildtype
```

Start compilation

````bash
m otapackage
```

OR

``` bash
m bacon
```

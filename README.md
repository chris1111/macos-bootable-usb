# macos-bootable-usb

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](LICENSE.md)

Combination of some codes and applications to create macOS installation media outside Mac app store.\
Thanks me later :3

## Motivation

Honestly, the main reason is I've limited Internet. I can't download the whole 8GB, 12GB at one stroke. So, I've to download multiple times and MAS doesn't support it. Moreover, I want to save downloaded installer so that I can use them next time. That's why I made this script.

## How to Use

#### Clone the repository
```bash
git clone https://github.com/htmm/macos-bootable-usb.git
cd $HOME/macos-bootable-usb
chmod +x ./creator.command
chmod +x ./Create_Install_Media.command
```

#### Downloading Install macOS from apple server
```bash

cd $HOME/macos-bootable-usb
./creator.command
```

#### Creating Create Install Media bootable drive
```bash

cd $HOME/macos-bootable-usb
./Create_Install_Media.command
```



it's still in beta. Simply just run the script, answer the question and go!

## View Spoiler Choice 1: ⬇︎
<details> 
  <summary>Spoiler Choice 1</summary>

![Screenshot](screenshots/Screenshot-1.png)

![Screenshot](screenshots/Screenshot-1-2.png)

</details>


## View Spoiler Choice 24: ⬇︎
<details> 
  <summary>Spoiler Choice 24</summary>

![Screenshot](screenshots/Screenshot.png)

![Screenshot](screenshots/Screenshot2.png)

</details>


`DISK SELECTION` information can be found in `diskutil` > `table` > `Device`. In this example `disk3`. So, `TARGET_DISK` become `/dev/disk3`.


## View Spoiler diskutil: ⬇︎
<details> 
  <summary>Spoiler diskutil</summary>

![diskutil](screenshots/diskutil.png)

</details>


## Thanks

Thanks to -

* <https://github.com/myspaghetti/macos-virtualbox>
* <https://github.com/kholia/OSX-KVM>

## License

This work is licensed under GPLv3. See [License](LICENSE.md) for more information.

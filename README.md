# Luma3DS
*放菜鸟 (新)3DS "自制系统"*

## 这是什么？
**Luma3DS** 是一个把3DS软件补的应用程式, 可以加特点（例如用别的语言在特别的游戏和排错能力如果你是电脑业者）和去任天堂的约束（例如锁区）。它也让你用擅自（自制程序）的内容。如果你要用它, 你需要有一个可以用自制程序在"arm9"处理器的3DS。我们建议你用[Plailect的教程](https://3ds.guide/) 所以你知道怎么办。

---

## Compiling

First you need to clone the repository recursively with: `git clone --recursive https://github.com/AuroraWright/Luma3DS.git`  
To compile, you'll need [armips](https://github.com/Kingcom/armips) and a build of a recent commit of [makerom](https://github.com/profi200/Project_CTR) added to your PATH.  
For now, you'll also need to update your [libctru](https://github.com/smealum/ctrulib) install, building from the latest commit.  
For your convenience, here are [Windows](http://www91.zippyshare.com/v/ePGpjk9r/file.html) and [Linux](https://mega.nz/#!uQ1T1IAD!Q91O0e12LXKiaXh_YjXD3D5m8_W3FuMI-hEa6KVMRDQ) builds of armips (thanks to who compiled them!).  
Finally just run `make` and everything should work!  
You can find the compiled files in the `out` folder.

---

## Setup / Usage / Features

参观 https://github.com/AuroraWright/Luma3DS/wiki

---

## Credits

参观 https://github.com/AuroraWright/Luma3DS/wiki/Credits

---

## Licensing

This software is licensed under the terms of the GPLv3.   
You can find a copy of the license in the LICENSE.txt file.

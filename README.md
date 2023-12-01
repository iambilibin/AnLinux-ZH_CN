这里是主程序使用的库。如果你在找程序中使用的图片或脚本，请点击[这里](https://github.com/EXALAB/AnLinux-Resources)（原版库，未翻译）

# AnLinux
AnLinux可以让您在没有Root安卓系统的情况下通过Termux安装Linux。感谢[Termux](https://github.com/termux/termux-app)和[PRoot](https://github.com/proot-me/PRoot)！是它们让这些设想成为了可以使用的成品。

注意：软件还在翻译中，下面的链接是原版的下载链接。

在Github上下载apk

[<img src="https://user-images.githubusercontent.com/663460/26973090-f8fdc986-4d14-11e7-995a-e7c5e79ed925.png" alt="Download APK from GitHub" height="100">](https://github.com/iambilibin/AnLinux-ZH_CN/releases/latest) 

注意：使用该软件需要连接到raw.github.com并下载文件。从Github上下载安装并不意味着你不需要梯子或其他手段就可以正常使用该软件。



## 它的工作原理？

用脚本从网上下载系统镜像，然后解压并用[PRoot](https://github.com/proot-me/PRoot)挂载它。



## 支持的桌面环境

我们目前支持5种桌面环境，只有部分系统可用。

支持的桌面环境：

1. [Xfce4](https://xfce.org)
2. [Mate](https://mate-desktop.org)
3. [LXQt](https://lxqt.org)
4. [LXDE](https://lxde.org)
5. [KDE](https://kde.org)



## 窗口管理器

我们目前支持2种窗口管理器，而且只有[Ubuntu](https://www.ubuntu.com/)、[Debian](https://www.debian.org/)、[Kali](https://www.kali.org/)、[Parrot Security OS](https://www.parrotsec.org/)、[Fedora](https://getfedora.org/)受支持。

支持的窗口管理器：

1. [Awesome](https://awesomewm.org)
2. [IceWM](https://ice-wm.org/)



## 未来的目标：

1. KDE和GNOME的系统环境支持(也许还会测试其他不可用的桌面)。
2. 音频支持。
3. 修复PRoot的错误。
4. 可能考虑BSD发行版的支持。



如果你有任何改进方法，建议，推荐，请在Github上发一个issue。



## 注意

1. 这个应用需要[Termux](https://github.com/termux/termux-app)的支持，你可以[F-Droid](https://f-droid.org)下载它。

2. 设备需求：

   安卓5或以上

   系统架构：armv7, arm64, x86, x86_64

3. 目前支持的发行版：

   [Ubuntu](https://www.ubuntu.com/)         [Debian](https://www.debian.org/)         [Kali](https://www.kali.org/)                 [Kali Nethunter](https://www.kali.org/kali-linux-nethunter/), [Parrot Security OS](https://www.parrotsec.org/)             [BackBox](https://www.backbox.org/)       [Fedora](https://getfedora.org/)    [CentOS](https://www.centos.org/)      [openSUSE Leap](https://www.opensuse.org/) [openSUSE Tumbleweed](https://www.opensuse.org/)                 [Arch Linux](https://www.archlinux.org/)        [BlackArch](https://blackarch.org/)    [Alpine](https://alpinelinux.org/)     [Void](https://voidlinux.org/)

4. 如有关于软件BUG的反馈或建议，请在[原版软件](https://github.com/EXALAB/AnLinux-App)的Github上发issue。

5. 由于找不到/dev/tty0的错误，窗口管理器已经被移除。



## 其他许可

应用图标的作者是[Alpár-Etele Méder](https://www.iconfinder.com/pocike)

程序中用到的Ashmem库：[android-shmem](https://github.com/pelya/android-shmem)



## 参考

1. [GNURootDebian](https://github.com/corbinlc/GNURootDebian)
2. [debian-noroot](https://github.com/pelya/debian-noroot)
3. [termux-ubuntu](https://github.com/Neo-Oli/termux-ubuntu)

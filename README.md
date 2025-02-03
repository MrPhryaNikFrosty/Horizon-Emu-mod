<p align="center">
English
&nbsp;&nbsp;| &nbsp;&nbsp;
<a href="https://github.com/HorizonEmuTeam/Horizon-Emu/blob/main/README-RUS.md">Русский</a>
&nbsp;&nbsp;
</p>

<p align="center">
	<img src="ProjectLogo.png" width="256" height="246" />  
</p>

<p align="center">
<b>Horizon-Emu-mod by Frost (discontinued)</b> is an application that allows you to run Windows x86_64 applications on your Android device.
</p>

![GitHub Downloads](https://img.shields.io/github/downloads/HorizonEmuTeam/Horizon-Emu/total?logo=github&label=Total%20Downloads)

# Information

This mod has been discontinued due to newly updated of Horizon Emu that add the download-able content feature make it impossible to use it by using my obb because if you use my obb maybe you won't get the my prefix. So I decided to discontinue this mod, we're sorry about that. Please follow my github for more emulation mod project. Thank you for your cooperation

# Installation 

1. Go to [Releases tab](https://github.com/MrPhryaNikFrosty/Horizon-Emu-mod/releases/), open latest release, download an Apk file and horizonemumodobb.tar file and install it.
2. Open an application called `Horizon Emu` and grant all request permissions. After that, go to 'Settings' tab and terminal shell. Copy and paste the `tar -xf /sdcard/Download/horizonemumodobb.tar -C /data/data/com.antutu.ABenchMark/` and wait for a few seconds until the containers appeared.
3. Open `Containers` tab, click on `Create a new container`, select name for your container, press `Confirm`, then select settings that you need and click `Done`.
4. After that update the wine 9.5 and download the scripts in 'Download' tab
5. Now, run the container. It might take a few minutes to load for the first time
6. For on-screen controls use application called InputBridge. To use it, download and install [InputBridge_v0.1.9.9.apk](https://raw.githubusercontent.com/HorizonEmuTeam/Horizon-Emu/main/InputBridge_v0.1.9.9.apk), open an application called `InputBridge` and provide all requested permissions, then press `Import` and select file of your controls profile (in .ibp format).
In container, InputBridge will be launched automatically.

That's all!

# Configuration
### Settings For X11
In the X11 settings tab you will be greeted with settings transferred from Termux-X11 Preferences.

Recommend settings: 

* Screen resolution mode: exact
* Screen resolution: 800x600 or 1280x720

Then everything is at the discretion of the user.

----

### Dynarec and other emulator's settings
Moved to environment configuration, works in manual format.

----

### Launch script output
You can check the operation of the container, and so on.

----

### Terminal
Android console emulator, can use commands like cd, tar, etc.

----

## System Requirements

* Minimum Required Android Version:` Android 9.
* Minimum GPU and CPU:
Adreno 610, and any other GPU that supports Turnip. CPU with aarch64.
* Root:
Root is not required.

# Issues in 1.0
* VirGL not available yet

>When deleting a container using the delete container button, the directory of drive D is also deleted, that is, in our case, the download folder. At the same time, the data of the application itself is cleared. ([Normal way to delete a container](https://t.me/HorizonEmuOfficial/434)).

# Our main goals

- [ ] Implement VirGL support.
- [ ] Fix container deletion option.
- [ ] Add built-in controls (Maybe).

# Special thanks 
<b>Jotaros</b>

<b>DragoPayras</b> - creation of GitHub and GitLab, testing of versions, fix errors.

<b>Alexoqool</b> - idea of ​​how you can add files and edit Apk.

<b>Snap</b> - adding a lot of DXVK and Turnips, adding Wine selection.

<b>MTK Top Proc</b> - idea of how you can add files.

## Telegram Channels to find out information about the development

[Snap's Channel (one of the main developers)](https://t.me/MoboxWinlatorExagear)

[Horizon Emu (first information and tests)](https://t.me/HorizonEmuOfficial)

[DragoPayras' Channel](https://t.me/DragOS_Channel)

[Alexoqool's Channel](https://t.me/WinlatorRus)

## Third party applications

[Wine](https://wiki.winehq.org/Licensing)

[Box86](https://github.com/ptitSeb/box86)

[Box64](https://github.com/ptitSeb/box64)

[glibc-packages](https://github.com/termux-pacman/glibc-packages)

[Mobox](https://github.com/olegos2/mobox)

[DXVK](https://github.com/doitsujin/dxvk)

[DXVK-ASYNC](https://github.com/Sporif/dxvk-async)

[DXVK-GPLASYNC](https://gitlab.com/Ph42oN/dxvk-gplasync)

[VKD3D](https://github.com/lutris/vkd3d)

[D8VK](https://github.com/AlpyneDreams/d8vk)

[Termux](https://github.com/termux/termux-app)

[Termux-X11](https://github.com/termux/termux-x11)

[Mesa](https://docs.mesa3d.org/license.html)

[mesa-zink-11.06.22](https://github.com/alexvorxx/mesa-zink-11.06.22)

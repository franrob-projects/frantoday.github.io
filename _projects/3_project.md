---
layout: page
title: VMware Fusion
description: VMware Fusion is a virtualization software program for Mac runs other operating systems, such as Windows or Linux as a virtual machine.
img: assets/img/vmware.jpg
# redirect: https://unsplash.com
importance: 3
category: install
---

Here are the steps to install VMware Fusion on a Mac using Terminal:

1. Download the VMware Fusion disk image file (ending in `.dmg`) from the VMware website to your Downloads folder.

2. Open Terminal by going to Applications > Utilities > Terminal.

3. In Terminal, navigate to your Downloads folder by entering the following command:

    ```
    cd ~/Downloads
    ```
4. Mount the VMware Fusion disk image by entering the following command:
    ```
    hdiutil mount VMware-Fusion-xxx.dmg
    ```
Replace `xxx` with the version number of the VMware Fusion disk image you downloaded.

5. In the mounted disk image, double-click the `VMware Fusion.app` file to launch the VMware Fusion installer.

6. Follow the prompts in the installer to agree to the license agreement, choose the installation location, and enter your administrator password.

7. After the installation completes, unmount the VMware Fusion disk image by entering the following command:

    ```
    hdiutil unmount /Volumes/VMware\ Fusion/
    ```
Replace `VMware\ Fusion` with the name of the mounted disk image as it appears in the Finder.

8. Launch VMware Fusion from the Applications folder.

Once you have installed VMware Fusion, you can create a new virtual machine and install the operating system of your choice.
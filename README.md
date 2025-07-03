# [Testing Needed] Dual Boot macOS 13.7 and Linux Mint 22.1 Installation Guide 

Hello, I have successfully installed Linux Mint 22.1 alongside macOS Ventura 13.7.6 on a MacBookPro14,1 (2017 MacBook Pro):

![mint-fastfetch](https://raw.githubusercontent.com/osalbahr/macos-linux-mint-guide/refs/heads/main/mint-fastfetch.png)

I would like to write an installation guide and add it to https://linuxmint-installation-guide.readthedocs.io by PR'ing it to https://github.com/linuxmint/doc-installation-guide.

If you have an Intel-based MacBook or Mac, I would like to request your help editing or testing the installation guide. It roughly goes as follows:

1. Following https://fedoraproject.org/wiki/QA:Testcase_dualboot_with_macOS, use Disk Utility on macOS to add a partition to install Linux Mint in.

2. Boot into the installation medium. You should see the following screen at some point. Select "Something else".

![something-else](https://raw.githubusercontent.com/osalbahr/macos-linux-mint-guide/refs/heads/main/something-else.png)

3. You should see the newly created partition at the bottom. Select it and click "Change...".

![change](https://raw.githubusercontent.com/osalbahr/macos-linux-mint-guide/refs/heads/main/change.png)

4. Select "Use as: Ext4" and the mount point as "/".

![mount-point](https://raw.githubusercontent.com/osalbahr/macos-linux-mint-guide/refs/heads/main/mount-point.png)

5. Select the EFI partition for the boot loader installation:

![efi](https://raw.githubusercontent.com/osalbahr/macos-linux-mint-guide/refs/heads/main/efi.png)

6. Click "Install now".

---

Also posted in:

https://forums.linuxmint.com/viewtopic.php?p=2646631

https://gist.github.com/osalbahr/c0430a9ad8536c01a86447fce8d2b431

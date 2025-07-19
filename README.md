# General kernel image instructions kernel

> **Please read the instructions carefully and use it under Google's guidance**

**【Kernel name】**

    Common name: Common kernel image
    English name: Generic Kernel Image
    Chinese Pinyin: Tongyong Neihe Yingxiang

**【Element】**

    https://kernel.org/
    https://kernelsu.org/

**【Traits】**

    This product is a compressed package within a compressed package file. For SHA256 detection, see the note next to it when downloading.

**【Adapted to models】**

    GKI compatible mobile phones.

**【Adverse reactions】** 

    Common: Fever. Occasionally: crash. Uncommon: Black Brick. 

**【Notes】**

This kernel security patch level comes from the latest settings of the KernelSU workflow. Before installing the kernel of this project, please       start the official or 5ec1cff KernelSU. After entering the system, open the KernelSU manager, enter settings, and **turn off global umount**. This is to prevent susfs' application processing of umount from causing system application problems. Possible phenomena include but are not limited to: 
  
- Black screen after startup (SystemUI cannot be loaded) 
- Wi-Fi is not accessible
- Baseband-related communications cannot be accessed

**【Nuclear Generation Dynamics】**

A study of generation dynamics of a universal kernel image was conducted on Pixel 8. can be started.
> **Software Interaction**
>
> Texture cleaning: When susFS is used in combination with texture cleaning, there is an interaction between the nuclear generation dynamics and nuclear efficiency of the two. After SUSFS was launched, it was reported that users who used texture cleanup reported that the umount app displayed 0B of remaining space. In addition, the knock-on effects of this incident include the inability to launch the WeChat applet.

**【Storage】**

    Any conditions.

**【Packaging】**

    Compressed package file.

# Coldflame Ecosystem Developer Guide

## Introduction
This Guide describes how to work on the Ignite OS. If you want to help IgniteOS and looking for detailed instructions you are at the right place.

## Contents
- [Introduction](#introduction)
    - [Target Audience](#target-audience)
- [Prequistes](#prequistes)
    - [Development Tools](#development-tools)
    - [Deployment Tools](#deployment-tools)
    - [Configure Git](#configure-git)
    - [Double Check you are on 64-bit machine](#double-check-you-are-on-64-bit-machine)

### Target Audience
The target audience of this guide are those who want to obtain, build or contribute to the IgniteOS. This includes new developers who are interested in the project and who simply want to browse code and want to see how things are working. And it also aims to those who are working for the IgniteOS for the long time.

## Prequistes
You must have a Linux distribution to develop IgniteOS. Any recent Linux distributions may work. We can't support every Linux distribution, as they are so many out there. So, please don't expect us to figure out for your Linux distribution
- [Arch Linux](https://archlinux.org)
<br>Not because you can say `you use arch`. Just because of the rolling release nature of the operating system. And with AUR you can done things quickly without hassle. 
- A x86_64-bit system for performing the builds
- An account with `sudo` access.
<br>You need `sudo` access to get into the chroot and some other tasks.

You will have a good time if you have
- A machine with a lot of memory and a good processor
<br>The faster the machine, faster code compilation. A 4-core processor is 4x faster than a single core processor
- Good Internet connection
<br>You need to download alot of stuff. And to do that quickly and without hassle of corruptions. You may need a good internet connection

### Development Tools
> **Note**
> This section isn't written yet

### Deployment Tools
> **Note**
> Deployment Tools are under development. And not available yet now.

### Configure Git
If you want to contribute to the Project. You may setup your Git. You may run into errors/issues later. Replace `you@example.com` with your mail and `Your Name` with your full name.
```bash
$ git config --global user.email "you@example.com"
$ git config --global user.name "Your Name"
```

### Double-check you are on 64-bit machine
Run the following command:
```bash
$ uname -m
```
If you see result `x86_64` you are good to go. If you see something else (like `i686`, it means you are either on a 32-bit machine or you are running a 32-bit operating system on 64-bit machine) then you won't be able to build IgniteOS.
# State of Linux on Mobile in July 2021

As a developer of Linux mobile OS ports and apps, I'd like to give an overview of the state of Linux on mobile platforms today. 

Development is rather quick and this article may be outdated by the time you read this. However, I hope most of this information will apply for some time.

## A note on Android

Many say that "Android is Linux" since it uses a Linux kernel. However, it has a drastically different userspace and philosophy to it. It also uses a heavily
modified Linux kernel which is not mainlined. Many manufacturers violate the GPL by not making their forks open source. This article will only be discussing
the new Linux mobile platforms which have a more traditional unix/linux userspace. 

## Why run Linux on your phone?

Here is an incomplete list of reasons why you should try Linux on your phone:

* If you like tinkering with technology
* If you want an OS that does not have the influence of monoploies such as Apple and Google
* If you want an OS that behaves more like a desktop OS
* If you want to run powerful desktop appliccations
* If you want a more lightweight OS
* If you want to try out different user interfaces
* If you want "convergence" - plugging in your device into a monitor to use it as a desktop computer

## Why NOT run Linux on your phone?

Linux mobile devices are not for everyone. Here are some reasons why you might not want to use one:

* You expect a stable platform that doesn't crash a lot
* You want to use many apps that are not open source
* You expect support for the software
* You don't like tinkering and patching things
* You don't want to type a lot of commands
* You're not OK with purchasing hardware that's relatively expensive compared to mainstream phones

## Hardware

There are now more hardware than ever that can run traditional Linux environments. For a phone or tablet to be able to run traditional Linux, it is 
important that the kernel and firmware are open source so they can be adapted. Some phones are designed to run Linux while others are shipped with Android
and are "ported" to run other platforms. It is mandatory that the phone have an unlockable bootloader. 

### Designed to run Linux

There are some phones which mostly emerged in the past 2-3 years that are designed to run open source mobile platforms. The main options are the Pine64 PinePhone and the Purism Librem 5. These phones are not very performant and are designed to be developer devices. The software for these devices is still a work-in-progress, and they should not be expected to function well as daily driver devices. However, due to the open nature of these devices, it is relatively easy to write
operating systems for them, making them good for development purposes. They run relatively close-to-mainline kernels, unlike Android devices. Both the PinePhone and the Librem 5 have HDMI output support in their USB-C slots, allowing for convergence. However, convergence requires software support. More on that below. 

It's now quite easy to obtain a PinePhone. Pine64 usually has them in stock and ships them in batches ([see availablity](https://www.pine64.org/availability-and-shipping-status/)] and [Ameridroid](https://ameridroid.com/products/pinephone) often has them in stock too.

It's harder to obtain a Librem 5 today. They are only available from Purism and there have been many delays. There are two versions: the regular Librem 5 and the Librem 5 USA. The USA version is at quite a high price and I honestly don't see why I should buy a low powered device at that cost. The regular Librem 5 is also rather expensive (about three times the price of the PinePhone) but it's slightly faster with a faster CPU and GPU.

### Designed to run Android

Many people have ported Linux-based OSes to phones designed to run Android. There are numerous options available, however the amount of operating systems available are limited due to the greater difficulty of porting to these devices. However, these operating systems are usually rather stable compared since they mostly use the kernel and firmware provided by the device manufacturer in their Android images. You can determine if an Android phone can run a Linux distribution using a search engine. You may need to look at each distribution's websites individually to determine this. 

You can also port the OS of your choice to an Android device of your choice if you want to tinker with low level things.




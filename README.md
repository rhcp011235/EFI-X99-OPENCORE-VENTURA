This was originally from Koush who put togther this wonderful guide + hardware (https://github.com/koush/EFI-X99)

He apparanty was unable to get this to work with OpenCore + Newer MacOS. I had to pay to get this done. If you find this helpful? Please donate (I will do my best to update donations)

I paid $120 dollars to get this done. People will say I paid for free open source software but, the truth? I dont have the time to play with this stuff anymore.

You can donate from: https://social.rhcp011235.me/johnhale

# My Hackintosh This repository is the EFI directory (basically, a boot drive) that can boot a macOS 13.0.1) installation. Think of the EFI as the isolated magic boot image that will let you start macOS on unofficial 
hardware. Ideally, all your system compatibility changes are in this boot partition, away from macOS itself. You don't 
want a macOS update accidentally breaking your system. This EFI will only work with my specific setup, but may work with 
similar ones via tweaking. 
![imacpro6_1_-_geekbench_browser]( # INSERT IMAGE TO BENCHMARK HERE) 
## Why Github? This is the easiest way to make and track changes to improve support and manage OS updates (as needed). Not 
having your EFI in revision control is bad. Eventually you will end up breaking something and not remember what you did. 
Additionally, someone using this repository can stay up to date with my changes by simply pulling down the latest files 
through Github on their boot partition. ## Installation ### My Hackintosh Hardware Total Cost: ~$3500 ($500 more if using 
a PCIe flash drive). A maxed out Mac Pro, for reference, is around ~$10,000, and is dated in comparison. You need to have 
mostly the same hardware for this to work. Parts that can not be swapped easily will be noted. * [Corsair Carbide Clear 
400C Compact Mid-Tower Case ](http://a.co/6L2qEmn) * [Corsair RMx Series, RM750x, 750W, Fully Modular Power 
Supply](http://amzn.to/2gmcFOR) * [Gigabyte X99P-SLI Motherboard](http://amzn.to/2hobBKe) <sup>[1]</sup> * [4 x Corsair 
Vengeance LPX 32GB DDR4 3200](http://amzn.to/2gjWgWs) * [Intel Core i7-6950X Processor](http://amzn.to/2hfZgoz) 
<sup>[2]</sup> * [MasterAir Pro 3 CPU Air Cooler](http://amzn.to/2h7dpGK) * [NVidia Titan 
Xp](https://www.nvidia.com/en-us/geforce/products/10series/titan-xp/) <sup>[3]</sup> * [BCM94360CD Wireless and Bluetooth 
Card](http://amzn.to/2ho63zs) <sup>[4]</sup> * [Samsung 960 EVO Series - 1TB PCIe NVMe - M.2 Internal 
SSD](http://amzn.to/2jaw6uR) <sup>[5]</sup> 


#### Notes 1. This motherboard is a little wonky, so while other Gigabyte or 
Asus X99 motherboards may work, my EFI repository may not work with it. Change at your own risk. See Motherboard and 
Graphics Card Notes below. 
6. Motherboard on F01 (Retail Bios) - Will NOT boot a CPU newer than 5820K 
and you need a 5820K to flash the latest BIOS to boot any CPU other than this. So
  * Make sure its flashed to F22+ (ask your reseller, like NewEgg) * Have access to a CPU which works on F01. [See list of 
  supported CPUs](https://goo.gl/LFIjGn).

[Full List of Hardware](http://a.co/7V7E9QI) 


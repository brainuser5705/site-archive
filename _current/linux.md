---
name: transitioning to linux
description: making linux my main os for good
focus: linux
time: 2024-03
---

# What's the deal?

I want to have Linux be my main operating system. Currently I use Windows 11,
and develop on WSL if I need a Linux environment.

I do have a history with Linux. I have installed Linux multiple times before 
on my systems, but ended up switching back to Windows because of some 
proprietary software I needed for school. And also that one time when my
laptop's motherboard fried up and I needed to replace Linux with Windows on my
spare laptop otherwise I couldn't do any schoolwork...I digress. I did try dual 
booting once, but a lot of the hardware on my old laptop didn't have drivers so 
using Linux was a pain.

But now that I have Thinkpad that is compatible with Linux, my dreams can
finally come into fruition and I don't need to look back ever again :) ... I
hope.

## Why the switch?

It's not that I don't like Windows, I mean it's been my main OS for my entire
life and I'm used to its interfaces and such. But bloatware has been kind of
irritating. Like no, I don't want to make Microsoft Edge my main browser.

I also want to get into operating systems one day, and being in a Linux
environment is sort of like a primer for me. From the videos I've seen about why
you should switch over to Linux, you have more control of the system, it's
customizable and open source. So yea, why not.

## What distro?

Probably keep it simple and go with Ubuntu. Or Pop OS. Or I could distro hop.
The main point is, contrary to Windows, I get to explore with Linux.

# Part 1 - Buying another drive

I still need Windows on my system, so I need to buy another drive for Linux. I
could install it on the same drive but my drive space is only 512 GB. And plus
my laptop has a second M.2 slot so might as well just use another drive. All
I need to do is find what drive to get. Thing is I suck at consumerism - too 
much choices and all of them are expensive. I tried to find a spare drive from 
my dead/spare laptops (none found) and I can't steal the one from the family's 
MacBook, so the only option I really have is to get a new one. Or maybe 
secondhand on Ebay, but I'm a bit wary.

I did some [bare-minimum research on all the terminology and acronymns](https://www.crucial.com/articles/about-ssd/m2-with-pcie-or-sata). What I
need is a PCle NVME M.2 drive. Specific to my laptop, it looks like a thermal
pad is also be needed. I could also get a heat shield, but that's more of an
accessory than necessity. Other [factors to consider](https://www.tomshardware.com/reviews/ssd-buying-guide,5602.html) are cost (*lower the better*) and storage size (*500 GB - 1 TB seem reasonable*). I ended up choosing the [Western Digital SN850X Gen4 PCle 1TB M.2 SSD](https://www.amazon.com/gp/product/B0B7CPSN2K/ref=ox_sc_act_title_2?smid=ATVPDKIKX0DER&th=1) with the heatsink and bought a 2.0 mm height thermal pad. There were some cheaper alternatives the [buyer's guide](https://www.tomshardware.com/reviews/best-ssds,3891.html) recommended, but they had some cons such as the specific drive type (QLC, DRAM-less), no Gen4 PCle support, or that the price is pretty close (give $20-30) to the WD SSD. So might as well cash a few more dollars for the better top-rated one. Plus I get a heat sink.

Now in all honesty, I have no idea what QLC, TLC, DRAM vs DRAM-less actually mean. They appeared in the article...but the article did say the average consumer shouldn't worry abou them. From what I've gathered in the Reddit posts is that TLC and DRAM are better. That's good enough for me.

# Part 2 - Installation
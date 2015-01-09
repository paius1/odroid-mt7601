# odroid-mt701
Kernel Module for Odroid C-1 Linux Kernel 3.10.42

Source cloned from https://github.com/Securityhuns/mt7601.git

Compiled on:

  Linux odroid-wheezy 3.10.43 #10 SMP PREEMPT Sat Dec 27 18:20:28 CET 2014 armv7l GNU/Linux

Just: 
     1.  Copy mt7601Usta.ko to /lib/modules/3.10.25/kernel/drivers/net/wireless

     2.  Copy RT2870STA.dat to /etc/Wireless/RT2870STA directory

     3. Run sudo depmod -a
     
Credits Source code: (c) Copyright 2002-2013, MediaTek Inc. (released under GPLv2)

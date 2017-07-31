# EvilSploit
Evilsploit - a universal hardware hacking toolkit.  

First of all, we all know about hardware hacking, and how messy to start a hardware hacking You need to study the hardware, to find a way to get the software, and hack it
When we mention to get the software means majority of the hardware are run by software

There are quite some misunderstanding from software oriented hacker to assume hardware hacking is all about to hack firmware or software
However, it is more than that. A hardware can also run by itself with its own digital logic
For both of the senarions, the hardware will usually come with the provisioning port, except those extra-small-form-factor things such as smart card
By making use with the provisioning port, a hardware hacker can control and do everything to the hardware in different ways such as to dump the firmware, to write new firmware, or to debug the hardware

Well, by making a simple assumption that majority of hardware having provisioning port, then it is crucial for most hardware hacker to find it out
As mentioned earlier, most hardware are run by software, and once the provisioning port is identified, then a hardware hacker can harness it from identifying bugs to developing reliable exploit to the hardware

However, since majority of hardware hackers are software oriented peoples, it is a little bit unfriendly to deal with multi-meter, oscilloscope, datasheet, and pcb board layout
to search for provisioning port.

In fact, it is really prone to human error to memorize which pin come with what feature, which pin number should connect to which another, and which color of cable represent which pin number.

Please ask yourself, how often you made such a simple mistake while doing hardware hacking in daily basis ?

On the other hand, most hardware hacking literatures are still demanding or assuming a reader to understand what are Tx, Rx, Gnd, or even TMS, TDI, TDO, TCK
Yes, it is really unfriendly
So, the question now is, is it compulsory to understand those nasty things in order to hack a hardware ?

Try to imagine, if a special cable, which one end is connecting to your computer's USB port and another end connecting to the target hardware with a special connector
then from minicom, putty, urjtag, or openocd point of view, is it still compulsory to understand those complicated things ? At least I dun think so

The issue is just like we never need to understand how the ECU works to drive a car, and that's why the car hacking issues get into the place

So, the intension of our Evilsploit is the special cable that I mentioned earlier to allow everybody who interested to hack a hardware can have the most beautiful experience in the first try

Forget about Tx, Rx, TMS, TDI and TDO things, forget about pin number, forget about which color of jumper cable should connect to which pin
Now, simply build the connection to those suspected pins that you believe is provisioning port, the Evilsploit will do all the rest of the nasty and complicated things
After that, fire up the minicom or openocd, the target hardware is ready for you, and here you go

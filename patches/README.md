You can use System_Patches packages and set these to *Auto Apply* with *Path Strip Count = 0*
so that the patches are applied across upgrades. 

Contrary to [allegations of Electric Sheep Fencing (dba Netgate)](https://github.com/github/dmca/blob/master/2018/2018-04-30-pfSense.md), the ```kill-uniqueid.diff``` patch does *NOT* remove or alter any copyright management information, this patch *disables usage of an unique ID produced by a closed source blob*.
Such IDs may be used as a personally identifiable information for tracking users/devices without user's knowledge and/or consent and without any legitimate purpose.
Indeed, you don't need any Netgate Unique ID unless you are using their [paid support](https://www.netgate.com/docs/pfsense/solutions/reference/support-subscription-signup.html). In such case, simply revert or do NOT apply this patch.
Otherwise, you might prefer to not be tracked by a closed source blob.

More info about the gnid blob at [/r/PFSENSE](https://www.reddit.com/r/PFSENSE/comments/6gq84t/closed_source_for_netgate_unique_id_generator/) - gonzo & Co. at their best once again.

***
![Where's the source code comedy yet again..](https://github.com/doktornotor/pfsense-still-closedsource/blob/master/img/Netgate%20Unique%20ID%20gnid%20blob%2001.png)
![Where's the source code comedy yet again..](https://github.com/doktornotor/pfsense-still-closedsource/blob/master/img/Netgate%20Unique%20ID%20gnid%20blob%2002.png)
***

## DMCA takedown note
The ```kill-copynotice-spam-243.diff``` and ```kill-copynotice-spam.diff``` patches (consisting of commenting out a single line with PHP include in ```index.php```) have been removed due to [DMCA request](https://github.com/github/dmca/blob/master/2018/2018-04-30-pfSense.md). Considering that simply reloading the page in browser makes the stupid copyright spam vanish without forcing users to actually accept the terms, the money spent on lawyers must have been well worth it. ROFLMAO @gonzo.

## Addendum # 1

So you say the GUI is slower than molasses when your WAN cannot connect to Internet? Well of course, it's because [our copyright notice needs to phone home daily](https://redmine.pfsense.org/issues/8987)! It is very important, you know, one can never be sure when gonzo decides to change the license once again.

***
![Copyright needs to phone home daily...](https://github.com/doktornotor/pfsense-still-closedsource/blob/master/img/Screenshot_pfSense_copynotice_slow_GUI_01.png)
![Copyright needs to phone home daily...](https://github.com/doktornotor/pfsense-still-closedsource/blob/master/img/Screenshot_pfSense_copynotice_slow_GUI_02.png)
***

I would say you should just remove the idiotic snooping calls instead of creating ```haveWorkingDns()```, but then again, I'd get another DMCA takedown request after that, as you can see above.

And remember, we'll also spam you with copyright notices [when we screw up and accidentally delete and restore a file on our webserver](https://www.reddit.com/r/PFSENSE/comments/bgvf79/copyright_notice_on_login/). Nevermind that nothing changed. There can never be too much copyright. Better to be 300% sure and check the timestamps also, not just checksums.

***
![Copyright needs to phone home also when we screw up...](https://github.com/doktornotor/pfsense-still-closedsource/blob/master/img/Screenshot_pfSense_copynotice.png)
***

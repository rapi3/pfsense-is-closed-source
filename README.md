# pfsense-closedsource
The only purpose of this repository is to document the false advertising of the so-called "open-source" pfSense®™ project. Brought to you courtesy of Netgate/Rubicon Communications LLC/ Electric Sheep Fencing LLC.

In case someone naively thinks that https://github.com/pfsense/FreeBSD-src contains the pfSense®™ source code - that is not the case. You cannot build pfSense®™ 2.4.x from source code. No, not even with the [official tools](https://github.com/pfsense/pfsense/tree/master/tools) - those will just sabotage you. The repository claimed to be "FreeBSD src with pfSense changes" does not contain the source code of the kernel shipped with pfSense®™ 2.4.x, and other changes done to FreeBSD code are also being selectively ommited from that repository.

Of course, such details cannot stop Netgate from plastering their websites and every single piece of their marketing material with "open source":
***
![False advertising](https://github.com/rapi3/pfsense-is-closed-source/blob/master/screenshot_pfsense_org_website_01.png)
***

Open-source labeling of course helps even when you are in business of [selling overpriced networking gear](https://store.netgate.com/):
***
![False advertising helps to sell overpriced gear, too..](https://github.com/rapi3/pfsense-is-closed-source/blob/master/screenshot_netgate_store_oss.png)
***


Not providing the source code for the actual product naturally cannot stop Netgate from falsely advertising that ["those who wish to review the source code in full detail, the changes are all publicly available on GitHub"](https://www.netgate.com/blog/pfsense-2-4-1-release-now-available.html) in their release notes either:
***
![BS release notes](https://github.com/rapi3/pfsense-is-closed-source/blob/master/screenshot_relnotes_241.png)
***

__No, you cannot review the source code in full__. But of course when you put enough open-source claims on your website, [there is no need to provide the source code](https://forum.pfsense.org/index.php?topic=138822.msg759561#msg759561), so do not bother with requesting it.

If you don't follow the above advice, Netgate's CEO will eventually [accuse you](https://forum.pfsense.org/index.php?topic=137636.msg754001#msg754001) of being [OPNsense](https://opnsense.org/)/[Franco's](https://github.com/fichtner) agent. Even [if you have nothing in common](https://forum.pfsense.org/index.php?topic=138822.msg758739#msg758739) with [OPNsense project](https://github.com/opnsense) in fact contributed thousands of commits to pfSense®™, even if you are not competing with pfSense®™/Netgate at all, even if you are not in business of selling routers/firewalls, you still are the prime suspect, being accused of trying to [gain advantage](https://forum.pfsense.org/index.php?topic=138804.msg759343#msg759343). __Paranoia is a serious mental disorder.__

If you think it's not a big deal, think again. Here, we have an unlucky user experiencing a bug that's basically a showstopper for his chosen workflow:

***
![Hey mighty gurus, I beg you for private kernel source code copy...](https://github.com/rapi3/pfsense-is-closed-source/blob/master/secret_pfsense_bugs_user_begging_for_private_kernel.png)
***

Notice how this allegedly open-source solution is in fact no better than any of the tons of proprietary alternatives out there. You cannot fix the bug yourself, you cannot have it fixed by someone you hire either, you cannot update, you are stuck. The (still) open configuration web GUI and the backend code mean nothing. It all falls apart and gets useless without access to the sources of the underlying customized FreeBSD operating system. It just won't work. Useless.

Is this a fair competition? No, of course not. Netgate are gaining an illegitimate advantage from the deceptive open-source advertising. Are these lies harming users as well? Apparently, as you can see above. The truth is so uncomfortable that it needs to be hidden by all means. The access to the above ticket [has been promptly locked](https://redmine.pfsense.org/issues/8025) - and is still locked at the time of writing this (Nov. 26, 2017). The forum thread linked there vanished as well. Why? Simply because it reveals the sad truth. *The Emperor Wears No Clothes.* Users begging for access to the kernel sources of a project that keeps babbling about open-source just about everywhere - cannot get much more absurd really.

And here's another example - [Bug #8155](https://redmine.pfsense.org/issues/8155) ("shockingly", the access got locked within minutes after making the screenshot).

***
![Build your own kernel? Certainly NOT with pfSense closed source...](https://github.com/rapi3/pfsense-is-closed-source/blob/master/screenshot_bug8155_rebuilding_pfsense_kernel.png)
***

Sorry, Sir, you have been lied to and mislead by Netgate. And, as predicted, they *will* hide the bug from public view when their lies get inconveniently exposed. And no, locking that bug was absolutely no accident, and your refiled [Bug #8215](https://redmine.pfsense.org/issues/8215) will not last for long either...

***
![Closed by accident? ROTFLMAO!](https://github.com/rapi3/pfsense-is-closed-source/blob/master/screenshot_bug8215_accidentally_closed_lulz.png)
***

While Mr. Thompson is soooo full of his pfSense®™ intellectual property and trademarks that he does not hesitate to claim any usage of "pf" or "sense" in combination with whatever else to be infringing - see [Can I sell pfSense](https://doc.pfsense.org/index.php/Can_I_sell_pfSense) [(PDF)](https://github.com/rapi3/pfsense-is-closed-source/blob/master/Can%20I%20sell%20pfSense%20-%20PFSenseDocs.pdf) - or trying to teach people how to use English - see [pfSense Trademark Usage Guidelines](https://www.pfsense.org/trademarks.html) [(PDF)](https://github.com/rapi3/pfsense-is-closed-source/blob/master/pfSense%20Trademark%20Usage%20Guidelines.pdf) - this is his take on other people's IP:

***
![Lets recycle the LEGO idea...](https://github.com/rapi3/pfsense-is-closed-source/blob/master/Gonzo%20(a.k.a.%20SmallWorks)%20recycles%20the%20LEGO%20idea%2001.png)
***

Shockingly, LEGO decided to [sue gonzo's ass](https://dockets.justia.com/docket/connecticut/ctdce/3:2015cv00823/108470) (also see [PDF1](https://github.com/rapi3/pfsense-is-closed-source/blob/master/Lego%20vs.%20Rubicon%20Communications%20-%2001.pdf), [PDF2](https://github.com/rapi3/pfsense-is-closed-source/blob/master/Lego%20vs.%20Rubicon%20Communications%20-%2002.pdf)). Ooops...

Infringing on other companies' trademarks apparently was not an isolated incident for Netgate. In another stunt, they've [registered opnsense.com domain](https://github.com/rapi3/pfsense-is-closed-source/blob/master/opnsense/README.md) and created a website there to discredit the [OPNsense](https://opnsense.org/) competition. Getting caught, they tried parody as defence. Shockingly, WIPO [did not buy into that nonsense](http://www.wipo.int/amc/en/domains/search/text.jsp?case=D2017-1828).


### The older I get, the less patience for bullshit I have. Dear [@Jim Thompson](https://twitter.com/gonzopancho):
***
![Message for Jim...](https://github.com/rapi3/pfsense-is-closed-source/blob/master/allergic-to-your-bullshit.png)
***

I have closed all my remaining [pull](https://github.com/pfsense/FreeBSD-ports/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aclosed%20author%3Adoktornotor%20) [requests](https://github.com/pfsense/pfsense/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aclosed%20author%3Adoktornotor%20) - definitely to gain the advantage of no longer contributing to a project that keeps lying to its users and customers. Oh, and thanks for locking my [issue tracker](https://redmine.pfsense.org/projects/pfsense/) account. I only reported couple hundreds of issues, many of them with PRs to fix the bugs. Not a big deal either.

P.S. A final advise, Jim. Reading [the FTC's advertising guideliness](https://www.ftc.gov/tips-advice/business-center/guidance/advertising-faqs-guide-small-business) and actually following them might spare you quite a bit of trouble in future. [False/misleading advertising is illegal.](https://www.ftc.gov/news-events/media-resources/truth-advertising)

In case people still decide to buy products from Netgate - kindly do yourself a favor and download the factory firmware image within the first year and keep it somewhere safe. If you need to reinstall the firmware, their "unencumbered by traditional annual contracts" claims won't exactly help you with that task:

***
![No annual licensing fees...](https://github.com/rapi3/pfsense-is-closed-source/blob/master/screenshot_no_annual_licensing_fees.png)
![... except if you need to reinstall.](https://github.com/rapi3/pfsense-is-closed-source/blob/master/screenshot_no_annual_licensing_fees_orly.png)
***

pfSense CE 2.8 has a [faster PPPoE module](https://www.netgate.com/blog/optimizing-pppoe-performance-in-pfsense-software).

The problem is, it's [closed source](https://github.com/pfsense/FreeBSD-ports/blob/e1f53a584010533df93e01ff15cc7dff5f6d8a83/net/if_pppoe-kmod/Makefile). The Ports `Makefile` references the `gitlab.netgate.com` hostname which resolves to `172.27.25.39`. Based on the `CNAME` records it seems to be inside Netgate's Austin intranet, presumably because Netgate doesn't want OPNsense to win.

So you have a "community edition" version with a closed source module. Not cool.


Say what you want about Rocky Linux and CIQ, they at least fought to keep "open source" open.

***
![Not impressed...](https://media.vanityfair.com/photos/5789244c814b54392dde94e6/master/w_1440,h_960,c_limit/mckayla-maroney-olympics-face.jpg)
***

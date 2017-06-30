---
title: Newsletter 6
date: 2017-06-02 13:37 UTC
tags: newsletter
image: "/images/newsletter.png"
---


Welcome to the sixth newsletter from **Security Without Borders**. This is a somewhat regular newsletter covering recent cyber security issues, tools and events relevant for activists, dissidents, journalists and civil society at large.

> **Security Tip** Do you want to use the **Tor Browser** but are based in a country or region where web (and VPN) traffic is heavily monitored or blocked? Download Tor via email via the [GetTor Robot](https://www.torproject.org/projects/gettor): send an email to [mailto:gettor@torproject.org](gettor@torproject.org) with your operating system (***windows***, ***linux*** or ***os x***) in the email body and you get sent a download link for the Tor browser on a popular (and thuse unlikely blocked) cloud service.

## New website!

Today, we launched our new [website](https://www.securitywithoutborders.org/). On it you find how to help, learn about our [missions](https://www.securitywithoutborders.org/missions.html) and find our [blog](https://www.securitywithoutborders.org/blog.html) which includes past newsletters and transmissions. Speaking of which, we just published our [Third Transmission](https://medium.com/security-without-borders/transmission-3-92b3a94bf93f)!

## Security alerts

- As a Linux user, it is just as important to patch vulnerabilities as it is for users of other operating systems. A good recent example of a serious vulnerability that was patched was [CVE-2017-7494](https://arstechnica.com/security/2017/05/a-wormable-code-execution-bug-has-lurked-in-samba-for-7-years-patch-now/), a **vulnerability in Samba**, Linux's implementation of Microsoft's SMB protocol. And like an SMB vulnerability was exploited to spread the WannaCry ransomware, this vulnerabiltiy could make it easy for an attacker to take over a vulnerable system.

- At the beginning of May, a German mobile phone provider [confirmed](https://www.theregister.co.uk/2017/05/03/hackers_fire_up_ss7_flaw/) that the SS7 protocol was exploited to intercept some of their customers' SMS messages, which were then used in combination with malware targeting the user to steal money from their (online) banking accounts. The weaknesses of SMS as a second authentication factor have long been known: last year NIST [warned](https://pages.nist.gov/800-63-3/sp800-63b.html) against its use and, as if to illustrate that point, around the same time Telegram accounts in Iran were hacked through ISPs intercepting SMS messages. The fact that ordinary cybercriminals have now been seen to do this shows that SMS really shouldn't be used to protect sensitive accounts and one should look for alternatives such as authenticator apps. If these aren't available for the service you need to use, at least make sure that SMS on its own doesn't give someone access to the account.

- Researchers from CCC in Germany published a [video](https://media.ccc.de/v/biometrie-s8-iris-en#video&t=51) in which they showed how they managed to **bypass the irisscanner** of the Samsung Galaxy S8 phone, a few years after the same group managed to [bypass](https://www.ccc.de/en/updates/2013/ccc-breaks-apple-touchid) Apple's TouchID fingerprint-based authentication. These attacks should serve as a reminder that, like other authentication methods, biometric-based authentication isn't 100% secure and when one is concerned about a device being taken by a powerful adversary, one should always use a second authentication factor, such as a (strong) password. For 'ordinary' use and protection against opportunistic attackers like pickpockets, biometric authentication, despite its flaws, is likely to provide ample security.

## Informative reading

- Hackers leaking stolen information to discredit targets for political reasons has become a widely discussed phenomenon, with the "DNC hacks" probably the best known example. Unsurprisingly, civil society is also targeted in such threats and a new [report](https://citizenlab.org/2017/05/tainted-leaks-disinformation-phish/) by Citizen Lab shows how hackers linked to the Russian government go a step further: they **manipulate some of the stolen documents** before "leaking" them in an attempt to further discredit targets. When such "tainted" documents are found among genuinely leaked files, it is not hard to see why an uninformed observer might see them as real.
In the long report, Citizen Lab writes how academics, activists, journalists, and NGO representatives have been targeted by such attachs, which share a modus operandi with the widely-publicised hacks and hack attempts of the Hillary Clinton and Emmanuel Macron election campaigns. Other than the fact that members of civil society often aren't too small for such prominent attacks, the use of phishing as an initial infection vector is, once again, a reminder to be extremely cautious when it comes to links, even (and perhaps especially) when they appear to come from services you regularly use.

- Russian state-sponsored hackers aren't the only ones targeting both foreign governments and local activists. Security firm FireEye writes about a **Vietnamese threat actor** "aligned with Vietnamese government interests" that has been targeting foreign governments as well as local activists and dissidents. This group also uses email as an infection vector, but rather than asked to click a link the target is tricked into opening an attachment and enabling macros in Microsoft Word or Excel. Opening email attachments should only be done when one is certain of the legitimacy of the sender. There is rarely, if ever, a reason for enabling macros: this is why SWB's [Hardentools](https://github.com/securitywithoutborders/hardentools) hardens your Windows installation by permanently disabling macros on your computer.
(For those interested in this particular threat and its focus on journalists, activists, dissidents, and bloggers: in 2014 the Electronic Frontier Foundation wrote about the [same group](https://www.eff.org/deeplinks/2014/01/vietnamese-malware-gets-personal).)

- The Open Observatory of Network Interference (OONI) and the Sinar Project published a detailed [report](https://ooni.torproject.org/post/indonesia-internet-censorship/) on the state of **online censorship in Indonesia**, in which it not only looked at which websites are blocked, but also considered the legal and technical nature of the blocking. The latter aspect makes this an interesting read for those fighting online censorship in other countries, or those developing tools aimed at bypassing this kind censorship, which sadly takes place in many countries.

- At SWB, we are working on a number of projects related to '**Stalkerware**': mobile spyware that, even if not explicitly marketed for that purpose, is used by people in abusive relationships to spy on (ex-)partners. As part of a [series](https://motherboard.vice.com/en_us/topic/when-spies-come-home) on the subject, Vice Motherboard published an interesting article by activist, writer and OPSEC expert Elle Armageddon, which not only provides a good introduction into the subject, it also comes with some basic practical advice.

- As you are reading this newsletter, it is likely that you have been converted already, but you may still want to [read](http://limn.it/what-is-to-be-hacked/) the **open letter to hackers** from SWB's Claudio, in which he calls for hackers to come and help civil society. If you know someone who is interested in doing good with their hacking skills, why not send them to Security Without Borders? Find out how to help on our [website](https://www.securitywithoutborders.org/volunteer.html).

- Finally, for those of you who read German: Wired Germany [published](https://www.wired.de/collection/life/redhack-nex-security-without-borders-turkey-blocks-hacker-aktivisten) an **interview with Claudio** in which he discusses Security Without Borders.

## Upcoming Events

- 15-18 June: [Allied Media Conference](https://www.alliedmedia.org/amc), Detroit, MI, USA
CVE-2020-15227
==============

DISCLAIMER! I take no responsibility of using it in wild life environment so please do NOT do it. This thingy is just to demonstrate and for test things for sysadmins

I made this exploit according to publishing a CVE of David Grudl (The founder of Nette foundation)
as he did not solved the issue pretty much fast, not giving documentation (way to exploit)
to security guys to inspect possible compromisation and hiding it. Ok, here we go man. 

As a security researcher I developed a little monster (for educational and demonstrational purposes of course)

The security vulnerability exploits callback parameter in nette.micro. We have no idea why the crap that exists (possible backdoor feature?)

Exploit is trying to get reverse shell from the victim server. The URL is hardcoded here so no stress about exploit edits.

PRs are welcomed!

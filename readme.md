#KyGP

## Release 0.4.0

Version v0.4.0! Yet another large step in KyGP’s functionality
Two of the things that have been fathomed recently, is the method to apply settings that use strings (REG_SZ) and the method to apply multiple (REG_SZ and (REG_DWORD) keys at the same time.

An example of applying multiple keys is the Prevent Java AutoUpdater policy we had.

Instead of having two separate policies or 32-bit Operating Systems and 64-bit Operating Systems, they have now been rolled into one; The benefit of doing this is that it minifies our lines somewhat, reduces the amount of policies we have on show and let’s face it, it looks tidier. :+1:

We have also expanded further into managing settings in Microsoft Office, namely PowerPoint and also more complex items such as Search Engines in Internet Explorer (Edge will be looked into and other browsers may follow)

And that’s that for v0.4.0!

We have big plans for v0.5.0 and hopefully we won’t have a v0.4.1 ;-) We take our quality control seriously and test each policy in a mixed client domain, with a Windows Server 2016 Preview Domain Controller and 7 to 10 Clients, sometimes for a laugh we do boot up an XP machine.

For a reference of the Group Policies, please check out the readme.docx

If you have any questions or suggestions; contact me on Twitter @[kylehulton](https://www.twitter.com/kylehulton) or via email at kyle.hulton@kyit.co.uk
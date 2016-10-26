---
title: "Frequent Questions"
slug: "faq"
menu:
    docs:
        parent: "other"
---

Here are answers to the most frequently asked questions that I receive from
email support and social media.


## General Questions

**What platforms does Insomnia run on?**<br>
Insomnia has desktop apps for 64-bit versions of Mac, Windows, and Linux. 

**Does Insomnia provide 32-bit binaries?**<br>
At this time, Insomnia is 64-bit only.

**Can I use Insomnia for commercial use?**<br>
Yes, of course!

**How can I support Insomnia?**<br>
First of all, thank you! Since Insomnia is just starting out, the best thing you
can do is help spread the word! You can also submit bug reports, let me know
how you use Insomnia, or sign up for a [paid plan](/pricing).


## Technical Questions

**How can I set an environment variable from a request?**<br>
At this time, that is not possible, but it's coming soon.

**Why do I get `ECONNREFUSED` when trying to connect to `localhost`?**<br>
This is currently a bug caused by Insomnia preferring IPv4 addresses over IPv6. 
Try changing `localhost` with `[::1]` as a temporary workaround.

**Why don't I see anything after importing a backup?**<br>
The import/export feature acts similarly to copying files in a filesystem. If
the import contains data that originated from your application, data will be
overwritten. However, if the import contains data that did not originate from 
your application, new data (including workspaces) may have be created.<br>
 _Hint: You can check for newly created Workspaces in the main (top-left) 
 dropdown._


## Random Questions

**What technologies is Insomnia build with?**<br>
Insomnia is built using [Electron](http://electron.atom.io/), 
[ReactJS](https://facebook.github.io/react/), and 
[NeDB](https://github.com/louischatriot/nedb).

**How many people work on Insomnia?**<br>
Just [me](http://schier.co/) :)

**Where is Insomnia based?**<br>
Victoria, BC, Canada!
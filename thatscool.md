# Cool Things

## February 2025

[Tmuxp](https://tmuxp.git-pull.com/) is a session manager for tmux. Freeze a tmux session to a file and recreate it simply, edit the file to tweak it, etc. 

[Culprit](https://github.com/creachadair/culprit) is a tool that will do a binary search over a set of git commits, execute an arbitrary command which should probe the source tree for some bad thing (brokenness) and track down the commit that introduced the break.

In 2004 one of my responsibilities at my very banal sysadmin job for a ~100 person org was care and feeding of a very banal mailserver, specifically trying to keep spam and viruses out of it. I stumbled across pg's essay [a plan for spam](https://www.paulgraham.com/spam.html) which introduced my to bayesian inference. I had no idea what I was looking at, and deeply failed to understand it, but I was absolutely certain that what I was reading was important. I printed out a hard copy of the essay and kept it close by, I would idly flip through it and roll the ideas around in my head. Today is not the first time that I stumbled across [this article about Prodspec and Annealing](https://www.usenix.org/publications/loginonline/prodspec-and-annealing-intent-based-actuation-google-production), the components that drive production orchestration at Google. But every time I stumble across it I feel that same feeling I felt when I read that pg essay. There are important ideas in here.

Artem Kirsanov is a phenomenal communicator of complex topics. He recently published a stunning three part series on [dynamical systems](https://www.youtube.com/watch?v=vTTlzmCRwU4), the [mathematics of nueronal modeling](https://www.youtube.com/watch?v=zOmhHE2xctw), and the [geometry of neuronal computation](https://www.youtube.com/watch?v=gLtGVEhMFN4).

ESP32-BlueJammer is an [open source 2.4ghz jamming device](https://github.com/EmenstaNougat/ESP32-BlueJammer). Because fuck your bluetooth speaker, but also plz don't kill any insulin pump users or anything like that.

## January 2025

[Streamlink](https://streamlink.github.io/) is a a CLI for playing web videos in VLC.

Cyberpunk IRL - [restofworld.org](https://restofworld.org) is a tech publication that covers everything outside of Western countries. Their [2025 photo contest winners](https://restofworld.org/2025/tech-photography-contest-winners/) has big ["the street finds its own uses for things"](https://www.goodreads.com/quotes/682-the-street-finds-its-own-uses-for-things) energy.

The person who created the Caddy webserver seems to have created Timelinize as an all purpose self hosted [personal timeline tool](https://github.com/timelinize/timelinize). You export your data from any number of services (google location history, icloud, strava) and overlay it all onto a contiguous timeline.

Not sure I completely understand the use case, devops involves lots of Go, Python, and Bash already, but [the risor scripting language](https://risor.io/) definitely rings the "this seems useful" bell in the back of my head. Somebody made a [tool](https://github.com/risor-io/risor/discussions/259) that allows you to package a risor script as an executable.

  * note: after playing with this more I think I am actually the perfect target user for this; somebody who isn't a very capable Go programmer who nonetheless wants to hack stuff together quickly and ship it as a single binary.

Schem.io is a [diagramming tool](https://schem.io/) purpose built for interactive technical systems. It's hard to explain but if you're an SRE you will probably find this exciting. [This video](https://youtu.be/idUW5sYV2oE?si=YfoB1JeRMB71l0oF) helps.

History of the Universe [is my new favourite youtube channel](https://www.youtube.com/@HistoryoftheUniverse). Hardcore physics and cosmology with stunning visuals and compelling narative. It's like if [PBS Space Time](https://www.youtube.com/channel/UC7_gcs09iThXybpVgjHZ_7g) was a glossy story book.

QRFrame is a [stylish, programmable, and open source](https://qrframe.kylezhe.ng/) QR code generator.

ebook2audiobook does what it says, it's an [app](https://github.com/DrewThomasson/ebook2audiobook) to turn an ebook into an audiobook, supports voice cloning.

WirelessAndroidAutoDongle is an [open source project](https://github.com/nisargjhaveri/WirelessAndroidAutoDongle) that turns a raspberry pi into a wireless android auto adapter. I paid $100 bucks for a commercial one like a _sucker_.

dnscontrol is a [DSL from StackExchange](https://github.com/StackExchange/dnscontrol) for generating DNS configurations. Not sure why one would use this over something like terraform or external-dns but it does seem cool.

Tile38 is a [geofencing event service](https://tile38.com/). Get notified by mqtt, sqs, NATS, etc. when things enter / exit a geofence.

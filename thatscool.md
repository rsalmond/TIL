# Cool Things

## May 2025

A while ago I stumbled across [ErsatzTV](https://github.com/ErsatzTV/ErsatzTV) which lets you create your own "TV channels" out of your media collection. Today I discovered [Fieldstation42](https://github.com/shane-mason/FieldStation42) which is a similar project but built to run on a raspberry pi, simulating a set top box experience.

[Pepr](https://pepr.dev/) is a bit more NodeJS than I would normally prefer, but as a K8s admission controller it looks a hell of a lot more useful and readable than OPA's Rego.

## April 2025

Matterport is a company that hosts 3d scans of places (usually homes for sale / rent) supporting virtual tours. [Matterport-DL](https://github.com/rebane2001/matterport-dl) lets you download those scans.

[Synthesia](https://www.synthesiagame.com/) is nearly twenty years old so it counts only as "new to me" but this "guitar hero for piano" thing sure looks cool!

[inscribed.app](https://github.com/chunrapeepat/inscribed) combines excalidraw with a slideshow / presentation workflow and looks great!

A couple years ago some phycists at MIT worked with visual animators to produce an "as accurate as it can be" visualization of a proton and created [a short documentary](https://youtu.be/e2FrALuacZ4) which shows the evolution of the project.

## March 2025

[Gokrazy](https://gokrazy.org/) is not _quite_ a Go microkernel, but it rhymes. Build your Go program into a bootable image, trim much fat.

Every now and then I stumble across something from the telco world that sorta kinda overlaps with my day to day K8s work, and more often than not it feels like witnessing a traffic accident. I'm horrified, but I simply cannot look away. I hope I never actually try it, but there is a masochistic part of me that wants to [run my own LTE tower](https://open5gs.org/open5gs/docs/tutorial/01-your-first-lte/) with a [custom operator](https://github.com/Gradiant/open5gs-operator) which is of course, a statement dreamed up by the utterly deranged.

A research paper called [Differentiable Logic Cellular Autonoma](https://google-research.github.io/self-organising-systems/difflogic-ca/) can be safely placed in the pile of papers labeled "this feels immensely important but hard to understand". It's basically a method for growing a purpose built CA to achieve some specific goal as opposed to tinkering with the rules of a CA and then studying what falls out of it. Also bonus points for introducing me to [differentiable logic gates](https://arxiv.org/abs/2210.08277) (code [here](https://github.com/Felix-Petersen/difflogic) brief video summary updated with convolutions [here](https://youtu.be/FKQfMwFZvIE)) which is absolutely mind blowing. This method can achieve "beyond a million images of MNIST per second on a single CPU core"!

[PeerAuth](https://ksze.github.io/PeerAuth/) provides cryptographic verification of human beings. Use google authenticator to confirm that you are who you say you are for other people as opposed to just for software.

[This music sampling breakdown](https://youtu.be/FpaoCUEhZJM) is one of the coolest things I've ever seen. It recreates classic tunes from their constituent parts in a fun hip shaking way!

## February 2025

[GonzoPi](https://gonzopi.org/) is a DIY 3d printed hackable video camera with a custom storyteller-centric firmware that shoots and edits video, captures story structure and organizes shots into scenes and scenes into films. This is some true hacker shit.

The venerable [Soldier of Fortran](https://infosec.exchange/@mainframed767) whose work I've been following since the early days of my career when I hacked on z/OS for a living has [created](https://github.com/mainframed/Hackers-Plymouth) some pretty authentic looking [plymouth bootsplash](https://wiki.archlinux.org/title/Plymouth) screens based on the [customized laptops in Hackers](https://www.youtube.com/watch?v=qiQlZU5oWTQ).

[AncientJames](https://mastodon.social/@ancientjames) hacked up a [DIY volumetric display](https://github.com/AncientJames/multivox) and [played GTA on it](https://www.youtube.com/watch?v=9XWmm2OU4LU).

[kubeletctl](https://github.com/cyberark/kubeletctl/tree/master) is a CLI for interacting with the [undocumented kubelet api](https://github.com/kubernetes/community/issues/6016). Useful for doing diabolical k8s security shit.

A while back I worked at a company that worked extensively with satellite imagery and during that time I heard a lot about synthetic aperture radar, and though I learned a lot while working there I never really learned how SAR worked. Today on HN [this amazing blog post detailing a DIY SAR drone](https://hforsten.com/homemade-polarimetric-synthetic-aperture-radar-drone.html) showed up and broke it down for me. The author also has [an older post](https://hforsten.com/synthetic-aperture-radar-imaging.html) which details the basics.

Gem5 is certainly not new, but it's new to me and blowing my mind. It's some kind of [arbitrary hardware simulator that let's you emulate random architectures](https://www.gem5.org/) using Python no less. You can do things like pile any number of caches between a CPU of your choosing and RAM and see how performance is impacted. It seems like one of those things that everyone in a small field is well aware of and _nobody_ outside of it has ever heard of.

(Very alpha) dynamic module support for Envoy proxy has [materialized](https://github.com/envoyproxy/dynamic-modules-examples).

TProxy is [a nice looking text based L7 proxy for debugging](https://github.com/kevwan/tproxy). Kinda looks like [tshark](https://tshark.dev) with a few bells and whistles.

One of the first things I did with LLM's when they hit the scene was ask one to provide an interactive fiction / choose your own adventure style text game. It produced a pretty faithful if somewhat banal rendition for me. I suspect LLM's will make NPCs will become a lot more interesting in the near future, games being one of those places where everything is a hallucination anyway so accuracy is less important. In the meantime somebody is experimenting with having an LLM [play through a text adventure game](https://github.com/s-macke/AdventureAI) instead, which tbf falls firmly into [let AI do the dishes](https://xcancel.com/AuthorJMac/status/1773679197631701238) territory but it's interesting. 

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

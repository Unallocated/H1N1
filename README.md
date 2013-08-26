H1N1
====

H1N1 is a project that is meant to integrate the PRADS Passive Operating System Detection with Snort, the popular Intrusion Detection System package. The end goal is a system where Passive OS fingerprinting and IDS both work off one another to present a bigger picture:

-	Snort benefits would benefit from Passive OS fingerprinting by having the Passive OS fingerprinting software inform it as to what operating systems are in its HOME_NET, and use that information to build Preprocessor policies, specifically frag3 and stream5 reassembly policies, that control how snort handles reassembling traffic for those hosts. Eventually this gathered information could be used to make snort rule recommendations based on hosts, client service banners observed in the HOME_NET as well.

-	PRADS would (eventually…) benefit from snort, by existing as a preprocessor in the “stack”, benefitting from snort’s native ability to reassemble fragmented packets and reassemble TCP streams for both Operating System identification and Client/Server banner grabbing from the wire.

-	Users would be able to review information for assets in their HOME_NET detected off the wire, alone with their intrusion events, offering greater network intelligence and a bigger picture.

There are those of us in this project who have no idea what they are doing when it comes to development projects beyond simple scripting.. The key to completing this project lies in the Unallocated space motto: Teach, Learn, Build.

We'll teach one another something, We will learn in order to fill in the gaps of knowledge we may lack in making this project a reality, and the end goal will be to Build something awesome.

There's no hard,fast timelines here; this project is intended for anyone who wants to learn development, or a particular language that would lend itself to the goals of this project to be welcome in joining in at any time. Most everyone here that wants to be involved in this project probably has something they know, but something they want to learn as well, so in order to make milestones in this project a reality, learning is something that's going to have to happen, and something that will take time before we can deliver on milestones.

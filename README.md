# Week-9-Project-Honeypot
Submission for week 9 assignment.


# Which Honeypot(s) you deployed

I deployed the Dionaea honeypot from Modern Honey Network.


# Any issues you encountered

The first issue that I encountered was downloading the SDK. When I first installed it, my console outputted an error. I did not understand the error message and was confused for a bit. After researching online and finding no solution, I attempted to retry installing the SDK. This time, I gave a new directory when the console asked for a directory. Fortunately, this time it actually worked. I was able to install the SDK along with the other Google Cloud commands. Afterwards, I tried initializing google cloud on my computer. My attempt worked until I tried setting up a firewall. I realized that I needed to create an account with Google Cloud and set up my billing. After doing so, I started following the rest of the instructions. Thanks to the instructions found in the QA forum, I didn't run into too much trouble afterwards. Finding the deploy button was difficult though.

# A summary of the data collected: number of attacks, number of malware samples, etc.

After deploying the honeypot, I was able to get some attacks. Surprisenly, I got a lot of attacks! The total number of attacks I was able to get, which was about a 2 hour duration, was 682. All attacks were to the Dionaea honeypot. Both the source and destination ports varied. The protocol for all was PCAP.

# Any unresolved questions raised by the data collected

I don't think so.

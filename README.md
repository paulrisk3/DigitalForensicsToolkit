# Digital Forensics Toolkit

A compliation of tools that I have used or might use for digital forensics purposes, sorted by function.

## Network tools

### [Wireshark](https://www.wireshark.org/)

Wireshark is one of the first names you'll hear in network forensics. This tool is used for network packet capture and analysis. I first used this tool in my junior year at BYU on Windows for a networking class. The GUI is simple to use and provides a great introduction to internet traffic to the uninitiated. One of its main features, the packet filter, took me a month or two of occasional use to begin to understand, but that was more due to my lack of experience with network terminology than anything else.

This tool is heavily used across the network and forensics industry. To know what data is moving across your network, you can't go wrong by checking out Wireshark.

### [Netcat](http://netcat.sourceforge.net/)

If a GUI is too easy for you, then check out Netcat! I've used Netcat on Kali Linux to reaed network packets that match certain filter parameters. One function that Netcat offers above Wireshark is the ability to actually create and send packets of your own. That might be less useful in a forensic scenario, but it's still neat! I haven't used Netcat for much else, since I've found Wireshark to be so effective.

### [tcpdump](https://www.tcpdump.org/)

I actually haven't used tcpdump, but it's on the list of popular network forensics tools. Based on the docs, tcpdump is an even more basic packet analyzer than Netcat and Wireshark. I assume that this tool has its uses even in the crowded world of network forensics tools, but I do not readily know where I would use it over Wireshark and Netcat.

### [Snort](https://www.snort.org/)

Snort is "an open source intrustion prevenetion system capable of real-time traffic analysis and packet logging," according to their website. In our digital forensics class, we used it to analyze packets from a previous capture. If I were needing to set up my own network security. Snort is one of the first tools I would grab. In order to prevent network intrusion, it "sniffs" each packet coming into a network and checks their contents against a database of known malicious packet contents. This tool can be used in conjuntion with a "dumb" firewall, which only blocks based on ports and IP addresses.

## Volatile Memory Tools

### [Volatility](https://www.volatilityfoundation.org/)

Volatility was one of the first widely-used tools used to examine and save the data in a computer's live memory, as well as analyzing saved captures. In our forensics class, we used this command-line tool to discover what software was running on a computer at time of acquisition (before it was shut down).

### [LiME](https://github.com/504ensicsLabs/LiME)

This is the Linux memory analyzer tool. I have not used it yet, but I'm keeping it in the tool kit for when the need arises. One advantage of this tool is that in can be used on a machine across a network.

## Operating System Tools

### [Linux dd](https://www.linuxnix.com/what-you-should-know-about-linux-dd-command/)

Linux dd (data duplicator) is used for copying and converting data. According to professional writers, it can backup and restore hard disks and partitions, back up the master boot record, and even convert magnetic tape format - that's not something you read every day. I haven't had to use this tool yet, but it definitely seems worth keeping in the digital forensics toolkit.

### [WinPrefetch View](https://www.nirsoft.net/utils/win_prefetch_view.html)

Windows systems are fairly easy to work on with many of the tools below. One useful tool that stands apart from full software suites is the WinPreftech View. This tool allows users to view the Prefetch files created by Windows when programs are run. On the long list of evidence that a forensic investigator should want to collect, recently run applications is near the top of the list. 

## Software Suites

### [Autopsy (and Sleuth Kit)](https://www.sleuthkit.org/autopsy/)

I have spent more time with this tool in my digital forensics class than any of the other tools on this list. Autopsy is a GUI for a command-line tool called Sleuth Kit - I have not used Sleuth Kit by itself, but I assume it's pretty powerful. Autopsy is a free tool that allows you to conveniently browse the file system of a captured system. 

### [FTK Imager](https://accessdata.com/products-services/forensic-toolkit-ftk)

FTK just seems like an expensive, slightly more complicated version of Autopsy. We used it in class, but I found Autopsy to be more useful for my own use cases. I believe one of FTK's distinguishing factors is that it's built to support collaboration. In a real digital forensics environment, multiple people will work on one case. FTK is designed to store its information in a central location for all team members to access. FTK also felt more professional, generally, than Autopsy. I think it might be more useful to large teams that have a lot of cases concurrently.

### [EnCase](https://www.guidancesoftware.com/encase-forensic)

## Frameworks

### [FIR (Fast Incident Response)](https://github.com/certsocietegenerale/FIR)

### [ELK (Security Information and Event Management)](https://www.elastic.co/elk-stack)

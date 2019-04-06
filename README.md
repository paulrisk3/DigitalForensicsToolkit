# Digital Forensics Toolkit

A compliation of tools that I have used or might use for digital forensics purposes, sorted by function.

## Network tools

### [Wireshark](https://www.wireshark.org/)

Wireshark is one of the first names you'll hear in network forensics. This tool is used for network packet capture and analysis. I first used this tool in my junior year at BYU on Windows for a networking class. The GUI is simple to use and provides a great introduction to internet traffic to the uninitiated. One of its main features, the packet filter, took me a month or two of occasional use to begin to understand, but that was more due to my lack of experience with network terminology than anything else.

This tool is heavily used across the network and forensics industry. To know what data is moving across your network, you can't go wrong by checking out Wireshark.

### [Netcat](http://netcat.sourceforge.net/)

If a GUI is too easy for you, then check out Netcat! I've used Netcat on Kali Linux to reaed network packets that match certain filter parameters. One function that Netcat offers above Wireshark is the ability to actually create and send packets of your own. That might be less useful in a forensic scenario, but it's still neat! I haven't used Netcat for much else, since I've found Wireshark to be so effective.

### [Snort](https://www.snort.org/)

Snort is "an open source intrustion prevenetion system capable of real-time traffic analysis and packet logging," according to their website. In our digital forensics class, we used it to analyze packets from a previous capture. If I were needing to set up my own network security. Snort is one of the first tools I would grab. In order to prevent network intrusion, it "sniffs" each packet coming into a network and checks their contents against a database of known malicious packet contents.

### [tcpdump](https://www.tcpdump.org/)

## Volatile Memory Tools

### [Volatility](https://www.volatilityfoundation.org/)

### [LiME](https://github.com/504ensicsLabs/LiME)

## Operating System Tools

### [Linux dd](https://www.linuxnix.com/what-you-should-know-about-linux-dd-command/)

### [WinPrefetch View](https://www.nirsoft.net/utils/win_prefetch_view.html)

## Software Suites

### [Autopsy (and Sleuth Kit)](https://www.sleuthkit.org/autopsy/)

### [FTK Imager](https://accessdata.com/products-services/forensic-toolkit-ftk)

### [EnCase](https://www.guidancesoftware.com/encase-forensic)

## Frameworks

### [FIR (Fast Incident Response)](https://github.com/certsocietegenerale/FIR)

### [ELK (Security Information and Event Management)](https://www.elastic.co/elk-stack)

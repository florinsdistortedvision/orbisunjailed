---
title: "Alternative Method of Jailbreaking - Self hosting"
mathjax: true
layout: post
categories:
  - info

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "home.md", title: "Home"}
  - {file: "about-general-knowledge.md", title: "About & General Knowledge"}
  - {file: "Jailbreak.md", title: "Jailbreak"}
  - {file: "gaming.md", title: "Games, Updates & DLC"}
  - {file: "hacks-homebrew.md", title: "Hacks & Homebrew"}
---

## For who is this method?

 * This method will allow you to completely stay offline and create your own host website for your jailbroken PS4.


### Self-hosting

 * Self-hosting involves cloning a website then running it locally using your PC as the server.
 * **If you have DNS ISP problem this most likely wont work.**
 * First, find a host you want to clone. Examples:
     * <a href="https://github.com/KAR0218/KAR0218.github.io"> Karo's 9.00 and lower JB host </a>
 * Download and install/unarchive:
    * <a href="https://www.apachefriends.org/ro/download.html"> XAMPP </a>
    * <a href="https://www.python.org/ftp/python/2.7.14/python-2.7.14.msi"> Python </a>
    * <a href="https://github.com/Crypt0s/FakeDns/archive/refs/heads/master.zip"> FakeDNS script </a>
 * Run XAMPP and open its control panel. Select Start so that Apache can turn green.
 * Open a cmd and run: ipconfig to find your IP Address (IPv4 Address). Take note of it.
 * Put fakedns.py to the folder C:/Python27/
 * In the same folder create a .txt file and write:
   * A manuals.playstation.net IPADDRESS   - replace IPADDRESS with your IP Address you took note of.
 * Save the file and rename it to dns.conf. **Make sure its a .conf and NOT a .txt file**
 * Back to cmd, run the command: fakedns.py -c dns.conf . This will start a fake server.
 * On the PS4, navigate to Settings > Network > Check Connect to the Internet, then Set Up Internet Connection and:

<pre>
<strong>Connection: Wi-Fi or LAN cable
Set Up: Custom
IP Address: Automatic
DHCP Host Name: Do Not Specify
DNS Settings: Manual
Primary DNS: YOUR IP ADDRESS           - Explanation: This DNS will redirect you to the host.
Secondary DNS: 0.0.0.0
MTU Settings: Automatic
Proxy Server: Do Not Use</strong>
</pre>

 * On your PS4, navigate to Settings > User's Guide/Helpful Info > User Guide. Take note of the address it tries to load. It should appear like this:
    * http://manuals.playstation.net/document/region/ps4/index.html - Take note of the region code. Could be "Ca" or "en", "eu" etc.
 * Back to the PS4, go to C:/XAMPP/htdocs/. Create folders that will copy the website structure before noted. It should look like this.
    * C:/XAMPP/htdocs/document/region/ps4/  - again replace region with your own region code.
 * In the final PS4 folder copy and paste the host cloned before (no archive).
 * Back to the PS4, navigate to Settings > User's Guide/Helpful Info > User Guide and the new host should now load.
 * Select firwmare and jailbreak using GoldHEN.
 * Done.

## Final notes
 
 * Your PC must be running first time including the XAMPP Apache start and fakedns.py script. For hosts with caching, you need to do this only once.

## Congrats, you have now jailbroken your PS4!

 * Now that you have successfully jailbroken your PS4, why not take look at what you can further do, such as <a href="https://florinsdistortedvision.github.io/orbisunjailed/gaming/"> Games, Updates and DLC </a> and <a href="https://florinsdistortedvision.github.io/orbisunjailed/hacks-homebrew/"> Hacks and Homebrew </a> .

---
title: "No Reset & Jailbreaking"
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

## 1. Determining your firmware

<ul>
	<li>As stated before, jailbreaking can only be achieved on a firmware lower than latest.</li>
	<li>To determine your firmware navigate on your PS4 to <strong>Settings > System > System Information</strong>.</li>
	<li>Take note of your firmware. <strong>If you're on 9.00 or anything lower you can continue.</strong></li>
</ul>

## 2. What firmware is the best and what should I do

To keep it short, different firmwares will need different exploits, thus can lead to various levels of stability and success rates. Please do keep in mind that they can be updated in the future. If you are on:

<ul>
	<li><5.05 - either keep it for archiving purposes or update to 5.05 or greater.</li>
	<li>5.05 - it's considered the gold firmware because of its stability and success rate. Either stay on it or update to 9.00 (note that you will need to backport most of your new games in order to play them - a guide can be found here).</li>
	<li>6.72 - either stay on it or update to 9.00 (note that you will need to backport most of your new games in order to play them - a guide can be found here)</li>
	<li>7.02 & 7.5x (7.50, 7.51 & 7.55) - update to 9.00</li>
	<li>9.00 - currently the latest exploitable firmware - Stay!</li>
</ul>

## 3. Resetting and/or updating your PS4 &amp; Jailbreaking

<ul>
	<li><strong>REMOVE ANY ETHERNET CABLE AND/OR SKIP WI-FI CONNECTION. Keep everything offline.</strong></li>
	<li><strong>Navigate to Settings > System > Automatic Downloads > Uncheck Featured Content, System Software Update Files, Allow Restart and Application Update Files.</strong></li>
	<li>Navigate to Settings > Network > Check Connect to the Internet, then Set Up Internet Connection and:</li>
</ul>

<pre>
<strong>Connection: Wi-Fi or LAN cable
Set Up: Custom
IP Address: Automatic
DHCP Host Name: Do Not Specify
DNS Settings: Manual
Primary DNS: 192.241.221.79            - Explanation: This DNS will redirect you to the jailbreak website.
Secondary DNS: 165.227.83.145          - Explanation: This DNS will block every connection to any Sony/PlayStation server.
MTU Settings: Automatic
Proxy Server: Do Not Use</strong>
</pre>

<ul>
	<li><strong>IF ON A FIRMWARE LOWER THAN 9.00 SKIP THIS</strong>. Download Rufus and exfathax.img on your PC. Plug a USB drive to your PC.</li>
</ul>

<p><a href="https://rufus.ie/en/">Rufus - Create bootable USB drives the easy way</a>&nbsp;</p>

<p><a href="https://github.com/ChendoChap/pOOBs4/blob/main/exfathax.img">pOOBs4/exfathax.img at main &middot; ChendoChap/pOOBs4 (github.com)</a></p>

<ul>
	<li><strong>IF ON A FIRMWARE LOWER THAN 9.00 SKIP THIS</strong>. In Rufus > Device (select your USB stick) > Boot Section: Disk or ISO image and select exfathax.img > Start. Note that will erase the USB drive.</li>
	<li>Back on the PS4, navigate to Settings > User's Guide/Helpful Info > User Guide. The website should now look like this:</li>
</ul>

<p><img alt="" src="https://gcdn.pbrd.co/images/7wX8rDhdqbdq.png?o=1" style="width: 690px; height: 388px;" /></p>

<ul>
	<li>Wait to cache the theme. Select your PS4 version. Select GoldHEN. Do not move your mouse cursor and have patience. If you see not enough memory errors, select OK and continue until you see this screen:</li>
</ul>

<p><strong>FOR 9.00 ONLY:</strong></p>

<p><img alt="" src="https://gcdn.pbrd.co/images/IP6tzCrtH4M3.png?o=1" style="width: 698px; height: 393px;" /></p>

<p>If you see this plug your USB drive we did with Rufus, wait until the notification pops and disappears, then press OK. If you see this screen, it means you now jailbroken the PS4 (also on FW lower than 9.00 this should appear without a USB drive):</p>

<p><img alt="" src="https://gcdn.pbrd.co/images/akm7y6qEsy66.png?o=1" style="width: 698px; height: 393px;" /></p>

<ul>
	<li>Congratulations, you now have jailbroken your PS4! Enjoy! <strong>(9.00 users, you need to remove the USB after you see the &quot;You&#39;re all set!&quot; screen).</strong></li>
</ul>

<p>&nbsp;</p>

## 4. Final questions and answers and troubleshooting

<ul>
	<li>An error &quot; Not enough memory&quot; appears. It's a normal error. Keep pressing OK until you pass it.</li>
	<li>My PS4 just shutdown/rebooted itself. Also a normal thing that can happen. Do not worry, remove the USB drive if on 9.00 and keep trying the same procedure starting with User Guide.</li>
	<li>I rebooted the PS4, and now I can't launch my games/apps. Jailbreaking is not persistent/permanent and as a result you need to rejailbreak your PS4 every time you reboot/shut down your PS4. As a alternative, you can put your PS4 on rest mode and you don't need to rejailbreak.</li>
	<li>Will my PS4 die from doing this? No, even forced reboots won't kill your PS4 unless you're doing it every 2 seconds for years :)</li>
</ul>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>Credits for images: Modded Warfare & Blaine Lockflair</p>
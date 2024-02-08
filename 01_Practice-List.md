# <img src="https://avatars.githubusercontent.com/u/67481186?v=4" width="25"> Hack-The-Box-Writeups


# Easy
|S.No| Machine & Links         | Writeup | CVEs - Tags                                                               |
|----|-------------------------|---------|---------------------------------------------------------------------------|
|1   |Lame [1](https://www.hackthebox.com/machines/lame)  [2](https://app.hackthebox.com/machines/Lame)|[Lame](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/01_Lame.md)|CVE-2007-2447, CVE-2004-2687, CVE-2009-1185, unix, smb, samba, smbmap, smbclient, distccd, process, udev|
|2   |Shocker [1](https://www.hackthebox.com/machines/shocker)  [2](https://app.hackthebox.com/machines/Shocker)|[Shocker](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/03_Shocker.md)|CVE-2014-6271, unix, cgi-*, cgi-bin, user.sh, shellshock, gtfobins, sudo, RCE, reverse shell|
|3   |Bashed [1](https://www.hackthebox.com/machines/bashed)  [2](https://app.hackthebox.com/machines/Bashed)|[Bashed](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/04_Bashed.md)|unix, sudo, cronjob/scheduled task, RCE, reverse shell|
|4   |Nibbles [1](https://www.hackthebox.com/machines/nibbles)  [2](https://app.hackthebox.com/machines/Nibbles)|[Nibbles](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/05_Nibbles.md)|CVE-2015-6967, CVE-2017-16995, unix, sudo, nibbleblog, kernel, RCE, default creds, source code inspection|
|5   |Beep [1](https://www.hackthebox.com/machines/beep)  [2](https://app.hackthebox.com/machines/Beep)|[Beep](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/06_Beep.md)|CVE:N/A [1](https://www.exploit-db.com/exploits/37637), CVE-2012-4869, CVE-2014-6271, CVE-2012-4867, CVE-2016-1713, CVE-2015-6000, CVE-2013-3214, CVE-2013-3215, unix, sudo, Elastix, PBX, LFI, svwar, webmin, shellshock, cgi-*, smtp, pop3, email, vTiger CRM, reverse shell, ssh|
|6   |Sense [1](https://www.hackthebox.com/machines/sense)  [2](https://app.hackthebox.com/machines/Sense)|[Sense](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/09_Sense.md)|CVE-2014-4688, CVE-2016-10709, unix, default creds, rce, stored creds, pfsense|
|7   |Valentine [1](https://www.hackthebox.com/machines/valentine)  [2](https://app.hackthebox.com/machines/Valentine)|[Valentine](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/12_Valentine.md)|CVE-2014-0160, CVE-2014-0346, CVE-2016-5195, unix, heartbleed ssl/tsl, sslyze, bruteforce/decrypt/decode, hash/encrypted/encoded, ssh, openssl, kernel exploit, dirtycow, system binary exploit, tmux session|
|8   |Sunday  [1](https://www.hackthebox.com/machines/sunday)  [2](https://app.hackthebox.com/machines/Sunday)|[Sunday](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/14_Sunday.md)|unix, bruteforce/decrypt/decode, finger, hydra, hash/encrypted/encoded, ssh, stored creds, sudo, suid, system/config/backup file, shadow.backup, hashid, john, hashcat, wget, gtfobins, openssl, passwd, wget --post-file, Overwrite Different SUID Binary, Overwrite shadow, Overwrite sudoers, /etc/sudoers, pspy, cronjob/scheduled task, solaris, powershell|
|9   |Irked  [1](https://www.hackthebox.com/machines/irked)  [2](https://app.hackthebox.com/machines/Irked)|[Irked](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/16_Irked.md)|CVE-2010-2075, CVE-2016-1531, CVE-2018-6789, unix, hidden file, rce, reverse shell, stego, steghide, stored creds, suid, IRC, UnrealIRCd, Irssi, hexchat, Exim, ltrace|
|10  |FriendZone  [1](https://www.hackthebox.com/machines/friendzone)  [2](https://app.hackthebox.com/machines/FriendZone)|[FriendZone](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/17_FriendZone.md)|CVE-2021-3156, CVE-2019-10149, unix, subdomain, DNS, DNS zone transfer, XSS, LFI, local file inclusion, burp, rce, reverse shell, smb, stored creds, system/config/backup file, mysql, sql conf file, mysql_data.conf, pspy, cronjob/scheduled task, Python Library Hijacking, writable python module, source code inspection, aquatone, impacket, smbclient, crackmapexec, smtp, Exim, Sudo Baron Samedit vulnerability|


# Medium
|S.No| Machine & Links         | Writeup | CVEs - Tags                                                               |
|----|-------------------------|---------|---------------------------------------------------------------------------|
|1   |Cronos  [1](https://www.hackthebox.com/machines/cronos)  [2](https://app.hackthebox.com/machines/Cronos)|[Cronos](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/07_Cronos.md)|CVE-2017-16995, CVE-2018-15133, unix, burp, cronjob/scheduled task, DNS, DNS zone transfer, subdomain, sqli, RCE, reverse shell, KERNEL, Laravel|
|2   |Nineveh  [1](https://www.hackthebox.com/machines/nineveh)  [2](https://app.hackthebox.com/machines/Nineveh)|[Nineveh](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/08_Nineveh.md)|CVE:N/A [1](https://www.exploit-db.com/exploits/24044), CVE-2014-0476, CVE-2017-16995, unix, info.php, bruteforce/decrypt/decode, hydra, php login bypass, php comparisons error exploit, type juggling, php login bypass type juggling, LFI, rce, phpliteadmin, reverse shell, pspy, cronjob/scheduled task, chkrootkit, strings, ssh, stego, binwalk, system binary exploit, system/config/backup file, mail, port knock, knockd, chisel, ssh authorized keys, public SSH keystring, private SSH keystring, kernel, procmon.sh|
|3   |SolidState  [1](https://www.hackthebox.com/machines/solidstate)  [2](https://app.hackthebox.com/machines/SolidState)|[SolidState](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/10_SolidState.md)|CVE:N/A [1](https://www.exploit-db.com/exploits/35513) [2](https://www.exploit-db.com/exploits/50347), unix, Apache James Mail Server, smtp, pop3, email, mutt, ssh, sshpass, authenticated rce, cron/scheduled tasks, pspy, rbash(restricted bash shell)/restricted shell, smtp/pop/imap, ssh, default creds, telnet, /etc/bash_completion.d, RSIP|
|4   |Node  [1](https://www.hackthebox.com/machines/node)  [2](https://app.hackthebox.com/machines/Node)|[Node](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/11_Node.md)|CVE-2017-16995, unix, Express Node.js, API, hadoop, big data, crackstation.net, MongoDB, NoSQL, base64, unzip, fcrackzip, zip2john, john, ssh, cron/scheduled tasks, kernel exploit, SUID, binary analysis, ltrace, unzip, 7z, libc buffer overflow|
|5   |Poison  [1](https://www.hackthebox.com/machines/poison)  [2](https://app.hackthebox.com/machines/Poison)|[Poison](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/13_Poison.md)|unix, bruteforce/decrypt/decode, hash/encrypted/encoded, LFI, local file inclusion, log poisoning, rce, reverse shell, ssh, ssh tunnelling, proxychains, port forwarding, stored creds, system binary exploit, system/config/backup file, VNC, vncviewer, scp, phpinfo.php, phpinfolfi.py|
|6   |TartarSauce [1](https://www.hackthebox.com/machines/tartarsauce)  [2](https://app.hackthebox.com/machines/TartarSauce)|[TartarSauce](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/15_TartarSauce.md)|CVE:N/A [1](https://www.exploit-db.com/exploits/43348), CVE-2015-8351, unix, robots.txt, monstra cms, wordpress, wpscan, gwolle-gb, cron/scheduled tasks, pspy, systemctl list-timers, RFI, remote file inclusion, reverse shell, source code inspection, sudo, system binary exploit, gtfobins, tar, --checkpoint-action, --to-command, SUID, symbolic link|
|7   |Surveillance  [1](https://www.hackthebox.com/machines/surveillance)  [2](https://app.hackthebox.com/machines/Surveillance)|[Surveillance](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/23_Surveillance.md)|CVE-2023-41892, CVE-2023-26035, unix, Craft CMS, rce, reverse shell, stored creds, SQLBackupFile, .sql.zip, sha256, hash/encrypted/encoded, hashcat, mysql, ssh, ssh tunnelling, port forwarding, zoneminder, sudo, zmupdate.pl, Busybox|


# Hard
|S.No| Machine & Links         | Writeup | CVEs - Tags                                                               |
|----|-------------------------|---------|---------------------------------------------------------------------------|
|1   |                         |         |                                                                           |


# Insane
|S.No| Machine & Links         | Writeup | CVEs - Tags                                                               |
|----|-------------------------|---------|---------------------------------------------------------------------------|
|1   |Brainfuck  [1](https://www.hackthebox.com/machines/brainfuck)  [2](https://app.hackthebox.com/machines/Brainfuck)|[Brainfuck](https://github.com/h4md153v63n/CTFs/blob/main/01_HTB/02_Brainfuck.md)|CVE:N/A [1](https://www.exploit-db.com/exploits/41006)  [2](https://www.exploit-db.com/exploits/46978), smtp, pop3, email, mutt, ssh, id_rsa, ssh2john, john, tls, subdomain, wordpress, vigenere, RSA, lxd, lxc, ssh|


---


# <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*qI2nolBN5VmdOoa_msaZRw.png" width="30"> Proving-Grounds-Writeups


# Easy
|S.No| Machine & Links         | Writeup | CVEs - Tags                                                               |
|----|-------------------------|---------|---------------------------------------------------------------------------|
|1   |                         |         |                                                                           |


# Medium
|S.No| Machine & Links         | Writeup | CVEs - Tags                                                               |
|----|-------------------------|---------|---------------------------------------------------------------------------|
|1   |                         |         |                                                                           |


# Hard
|S.No| Machine & Links         | Writeup | CVEs - Tags                                                               |
|----|-------------------------|---------|---------------------------------------------------------------------------|
|1   |                         |         |                                                                           |


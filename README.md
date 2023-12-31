# NCL TOOLS

#### This is a list of tools used in NCL Gym challenges. It isn't extensive, feel free to open a PR if you have other tool suggestions

### OSINT
| Tool                  | Download/URL                                                                                           | Description                          |
| --------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------ |
| metadata2go           | [https://www.metadata2go.com/](https://www.metadata2go.com/)                                           | View metadata, exif.tools also works |
| IETF Datatracker      | [https://datatracker.ietf.org/doc/html/rfc4034](https://datatracker.ietf.org/doc/html/rfc4034)         | DNSSEC / IETF Protocol specification |
| Wikipedia             | [https://www.wikipedia.org/](https://www.wikipedia.org/)                                               | \-                                   |
| Online Barcode Reader | [https://online-barcode-reader.inliteresearch.com/](https://online-barcode-reader.inliteresearch.com/) | Barcode reader                       |
### CRYPTO
| Tool                          | Download/URL                                                           | Description                                                                                                                                                                     |
| ----------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cyberchef                     | [https://gchq.github.io/CyberChef/](https://gchq.github.io/CyberChef/) | Do number stuff and more! [https://cyberchef.cyberskyline.com/](https://cyberchef.cyberskyline.com/) is the NCL mirror                                                          |
| dcode                         | [https://www.dcode.fr](https://www.dcode.fr)                           | Cyberchef but more crypto and 🇫🇷                                                                                                                                              |
| Digital Invisible Ink Toolkit | [https://diit.sourceforge.net/](https://diit.sourceforge.net/)         | Old steg tool that NCL uses. See [https://diit.sourceforge.net/doco.html#whatarethealgorithms/](https://diit.sourceforge.net/doco.html#whatarethealgorithms/) for list of modes, **STEGHIDE IS ALSO USED** |
### PASSWORD CRACKING
| Tool     | Download/URL                                                                                                             | Description                                                                                                                                                     |
| -------- | ------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Hashcat  | Too lazy... it's included in Kali though                                                                                 | Extract password from hashes. ```hashcat hash.txt -m 0 -a 0 /usr/share/wordlists/rockyou.txt``` is a basic command for dictionary attack on MD5 with rockyou.txt  Also check out [https://www.kali.org/tools/john/](John) for more robust applications.  |
| ophcrack | [https://ophcrack.sourceforge.io/download.php?type=ophcrack](https://ophcrack.sourceforge.io/download.php?type=ophcrack) | NTLM Password cracker. Perhaps use XP Special wordlist. Cain and Abel possible alternative [https://github.com/xchwarze/Cain](https://github.com/xchwarze/Cain) |
### FORENSICS
| Tool    | Download/URL                             | Description                                               |
| ------- | ---------------------------------------- | --------------------------------------------------------- |
| git     | \-                                       | Honestly just like figure out VCS, idk either             |
| binwalk | Too lazy... it's included in Kali though | Lets you extract files combined/included in another file. |
### LOG ANALYSIS
| SQLite Viewer   | [https://sqlitebrowser.org/](https://sqlitebrowser.org/)           | Lets you view a variety of db files. Any SQL viewer should work, I just use this one.                                                                                                                                 |
| --------------- | ------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| epoch converter | [https://www.epochconverter.com/](https://www.epochconverter.com/) | Convert time from/to epoch                                                                                                                                                                                            |
| cat             | \-                                                                 | Just like be really good at passing args to cat, being able to format stuff / sort stuff is vital to log analysis. If you wanna write bash scripts to write to file instead that also works, but I feel cat is faster |
### NETWORK TRAFFIC ANALYSIS
Just use Wireshark tbh
### SCANNING
| Tool      | Download/URL                                               | Description                                                                                                            |
| --------- | ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Nmap      | Included in Kali, https://nmap.org/zenmap/ for GUI version | Network mapping tool                                                                                                   |
| Dirbuster | Too lazy... it's included in Kali though                   | Scan a web app for hidden files / directories via brute force, note that gobuster is faster, can be installed via apt. |
### WIRELESS ACCESS EXPLOITATION
| Tool        | Download/URL                             | Description                                                                                                                                                                                                             |
| ----------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| aircrack-ng | Too lazy... it's included in Kali though | wifi hacking                                                                                                                                                                                                            |
| Wireshark   | lazy                                     | Just putting this here to point out that Wireshark can decrypt traffic for different wireless protocols ```Edit → Preferences → Protocols → <protocol>``` then enable decryption and enter your key to decrypt the traffic. |
### ENUMERATION & EXPLOITATION
| Tool         | Download/URL                                                                                                                                                      | Description                                                                                                                                                   |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Python       | \-                                                                                                                                                                | \-                                                                                                                                                            |
| uncompyle    | [https://github.com/Mysterie/uncompyle2](https://github.com/Mysterie/uncompyle2)                                                                                  | Decompile python2, also check [https://pypi.org/project/uncompyle6/](https://pypi.org/project/uncompyle6/) ```pip install uncompyle6``` for new version of python |
| Ghidra       | [https://github.com/NationalSecurityAgency/ghidra/releases](https://github.com/NationalSecurityAgency/ghidra/releases)                                            | Reverse engineering tool                                                                                                                                      |
| GDB, JEF,etc | GDB usually already installed. [https://github.com/hugsy/gef](https://github.com/hugsy/gef), [https://github.com/pwndbg/pwndbg](https://github.com/pwndbg/pwndbg) | pwn, dynamic analysis                                                                                                                                         |
### WEB APPLICATION EXPLOITATION
| Tool       | Download/URL                                                                                                                    | Description                                                                                                   |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Burp Suite | preinstalled in Kali (I think) [https://portswigger.net/burp/communitydownload](https://portswigger.net/burp/communitydownload) | Web application testing, honestly most challenges should just need browser developer tools, burp is optional. |

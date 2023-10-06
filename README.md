# NCL TOOLS
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
| Digital Invisible Ink Toolkit | [https://diit.sourceforge.net/](https://diit.sourceforge.net/)         | Old steg tool that NCL uses. See [https://diit.sourceforge.net/doco.html#whatarethealgorithms/](https://diit.sourceforge.net/doco.html#whatarethealgorithms/) for list of modes |
### PASSWORD CRACKING
| Tool     | Download/URL                                                                                                             | Description                                                                                                                                                     |
| -------- | ------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Hashcat  | Too lazy... it's included in Kali though                                                                                 | Extract password from hashes. "hashcat hash.txt -m 0 -a 0 /usr/share/wordlists/rockyou.txt" is a basic command for dictionary attack on MD5 with rockyou.txt    |
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
Just use Wireshark.

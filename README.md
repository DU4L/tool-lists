# Tool List

Here you can find some useful tools to solve a CTF. Feel free to add some tools!

## Categories

1. [Forensic](#forensic)
2. [Misc](#misc)
3. [Crypto](#crypto)
4. [Reverse](#reverse)
5. [OSINT](#osint)


## Forensic

### Binwalk

Binwalk is a tool for searching binary files like images and audio files for embedded files and data.

<details><summary><b>Usefull commands</b></summary>
    ```sh
    binwalk file        Displays the embedded data in the given file 
    binwalk -e file     Displays and extracts the data from the given file
    ```
</details>

### Exiftool

Sometimes important stuff is hidden in the metadata of the image or the file , exiftool can be very helpful to view the metadata of the files.

<details><summary><b>Usefull commands</b></summary>
    ```sh
    exiftool "file"     shows the metadata of the given file
    ```
</details>

## Misc

## Crypto

Whatever happen, google is your friend. There are a lot cryptography tools online. Some of good tool are made offline like OpenSSL.



<details><summary><b>Classic cipher / Simple decoder online tool:</b></summary>
- hallo
- welt
</details>



<details><summary><b>Modern cryptography:</b></summary>
- https://gchq.github.io/CyberChef/ - All in one tool
- https://crackstation.net/ - Crack hash
- Cryptool
- John the Ripper 
- Hashcat

Cracking compressed file:
- John the Ripper
    ```sh
    john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt
    ```
- fcrackzip 
    ```sh
    fcrackzip -D -u -p rockyou.txt  filename.zip
    ```
- Hashcat 
    
</details>

## Reverse

- Ghidra: https://ghidra-sre.org/
- GDB*: https://www.gnu.org/software/gdb/download/ 
- GEF: https://github.com/hugsy/gef 
- x64dbg: https://x64dbg.com/
- pwntools: https://github.com/Gallopsled/pwntools
- radare2*: https://github.com/radareorg/radare2
- ApkTool: https://ibotpeaches.github.io/Apktool/
- Fiddler: https://www.telerik.com/fiddler
- Detect It Easy: https://github.com/horsicq/Detect-It-Easy


## OSINT

## Exploit

- Burp Suite: https://portswigger.net/burp
- Nmap: https://nmap.org/
- Gobuster: https://github.com/OJ/gobuster
- Exploit-db: https://www.exploit-db.com/
- Metasploit: https://www.metasploit.com/
- Hydra: https://github.com/vanhauser-thc/thc-hydra
- Zed Attack Proxy: https://www.zaproxy.org/

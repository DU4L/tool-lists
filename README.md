# Tool List

Here you can find some useful tools to solve a CTF. Feel free to add some tools!

## Categories

1. [Forensic](#forensic)
2. [Misc](#misc)
3. [Crypto](#crypto)

## Forensic

### Binwalk

Binwalk is a tool for searching binary files like images and audio files for embedded files and data.

<details><summary><b>Usefull commands</b></summary>
    ```sh
    binwalk file        //Displays the embedded data in the given file 
    binwalk -e file     //Displays and extracts the data from the given file
    ```
</details>

### Exiftool

Sometimes important stuff is hidden in the metadata of the image or the file , exiftool can be very helpful to view the metadata of the files.

<details><summary><b>Usefull commands</b></summary>
    ```sh
    exiftool "file"     //shows the metadata of the given file
    ```
</details>

## Misc

## Crypto

Whatever happen, google is your friend. There are a lot cryptography tools online. Some of good tool are made offline like OpenSSL.



<details><summary><b>Classic cipher / Simple decoder online tool:</b></summary>
    - https://quipqiup.com - quipqiup is a fast and automated cryptogram solver
    - https://www.base64decode.org/ - base64 decoder
    - https://www.urldecoder.org/ - URL decoder
    - https://emn178.github.io/online-tools/base32_decode.html -  Base32 decoder
    - https://cryptii.com/ - All in one tool
    - https://www.guballa.de/substitution-solver - Substitution solver
    - https://www.guballa.de/vigenere-solver - Vigenere solver
    - https://rot13.com/ - Rot 1 - 25 decryptor
    - https://www.dcode.fr -  All in one tool
    - http://rumkin.com/tools/cipher/ -  All in one tool
    - http://www.unit-conversion.info/texttools/morse-code/ - Morse code decoder
    - https://cryptii.com/pipes/ascii85-encoding - ASCII85 decoder
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

## OSINT

## Exploit

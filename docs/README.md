# Welcome stranger!
This is the repository for Berlin Sides 2017 "Smartcard Island".<br>
A  project from adesso AG and ZeitControl cardsystems GmbH.<br>
For further informations about these companies click on one of the specific images below.<br>
<div>
<a href="https://adesso.de"><img src="adesso_smartcard.png" float="left"  width="48%" ></a>
<a href="https://secure.zeitcontrol.de/shop"><img src="zeitcontrol_smartcard.png" float="right" width="48%" ></a>
</div>
<br>
<br>

# Technical details

The smartcard given to you is a BasicCard ZC7.6 with an NXP P5CD081 from the SmartMX family inside.

### Standard family features
- EEPROM: choice of 16 KB, 20 KB, 40 KB or 80 KB
  - Data retention time: 25 years minimum
  - Endurance: 500000 cycles typical
- ROM: 264 KB
- RAM: 7680 B
  - 256 B IRAM + 4.75 KB standard RAM usable for CPU
  - 2560 B FXRAM usable for FameXE
- Dedicated, Accelerated Secure_MX51 smart card CPU (Memory eXtended/enhanced 80C51) 
  - 5-metal layer 0.14 μm CMOS technology
  - Operating in Contact and Contactless mode (dependent on family type option)
  - Featuring a 24-bit universal memory space, 24-bit program counter
  - Combined universal program and data linear address range up to 16 MB
  - Additional instructions to improve:
    - pointer operations
    - performance
    - code density of both C and Java source code
- ISO/IEC 7816 contact interface
- ISO/IEC 14443 contactless interface
- PKI coprocessor FameXE
- Support of major Public Key Cryptography (PKC) systems such as RSA, Elgamel, DSS, Diffie-Hellman, Guillou-Quisquater, Fiat-Shamir and Elliptic Curves
  - 8192 bits maximum key length for RSA with randomly chosen modulus
  - 4096 bits maximum key length for calculation within RAM
  - 32-bit interface
  - Boolean operations for acceleration of standard, symmetric cipher algorithms
- High speed triple-DES coprocessor (64-bit parallel processing DES engine)
  - Two or three keys loadable
  - DES3 performance < 40 μs
- High speed AES coprocessor (128-bit parallel processing AES engine)
- Memory Management Unit (MMU) with increased number of 8 cache segments
- Low power and low voltage design using NXP Semiconductors’ handshaking technology
- Multiple source vectorized interrupt system with four priority levels
- Watch exception provides software debugging facility
- Multiple source RESET system
- Two 16-bit timers
- Highly reliable EEPROM for both data storage and program execution
- Bytewise EEPROM programming and read access
- Versatile EEPROM programming of 1 B to 64 B at a time or, optionally 1 B to 128 B at a time




 CIU fully compatible with ISO/IEC 14443A:
- 13.56 MHz operating frequency
- fully supports the T=CL protocol in accordance with ISO/IEC 14443-4
- factory configurable for higher input capacitance to match smaller loop antennas
- supported data transfer rates: 106 kbit/s, 212 kbit/s, 424 kbit/s and 848 kbit/s
- MIFARE reader infrastructure compatibility via optional MIFARE 1 K or 4 K
emulation including built-in anticollision support
 Two additional I/O ports: IO2 and IO3 for full-duplex serial data communication


## Applications & Use cases

## Useful tools

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/VX4/bs17/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/VX4/bs17/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

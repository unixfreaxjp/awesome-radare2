# Awesome Radare2 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="r2.svg" align="right" width="100">](http://rada.re/)

A curated list of awesome projects, articles and the other materials powered by Radare2.

## What is Radare2?

Radare is a portable reversing framework that can...

- Disassemble (and assemble for) many different architectures
- Debug with local native and remote debuggers (gdb, rap, r2pipe, winedbg, windbg, ...)
- Run on Linux, *BSD, Windows, OSX, Android, iOS, Solaris and Haiku
- Perform forensics on filesystems and data carving
- Be scripted in Python, Javascript, Go and more
- Visualize data structures of several file types
- Patch programs to uncover new features or fix vulnerabilities
- Use powerful analysis capabilities to speed up reversing
- Aid in software exploitation

More info [here](http://rada.re/).

### Table of Contents

- [Books](#books)
- [Videos](#videos)
   + [Recordings](#recordings)
   + [Asciinemas](#asciinemas)
   + [Conferences](#conferences)
- [Slides](#slides-and-workshops)   
- [Tutorials and Blogs](#tutorials-and-blogs)
- [Tools](#tools)
- [Scripts](#scripts)
- [Contributing](#contributing)


# Awesome Radare2 Materials

## Books

- [R2 "Book"](https://legacy.gitbook.com/book/radare/radare2book/details)
- [Radare2 Explorations](https://legacy.gitbook.com/book/monosource/radare2-explorations/details)
- [Radare2 wiki](http://r2wiki.readthedocs.io/en/latest/)
- [Binary Analysis Course](https://maxkersten.nl/binary-analysis-course/)

## Videos

### Recordings

- [r2pipe - connector to r2](https://www.youtube.com/watch?v=xGn_xbb28mE)
- [Solving a Self-modifying Crackme with r2pipe EMU vs DBG vs XOR](https://www.youtube.com/watch?v=ODCNbM9_U4M)
- [Creating a keygen for FrogSek KGM#1](https://www.youtube.com/watch?v=4xGAwI10VNM) - by @binaryheadache
- [Radare2 - An Introduction with a simple CrackMe - Part 1](https://www.youtube.com/watch?v=8dXhrOEGHTY) - by @antojosep007
- [Introduction To Reverse Engineering With Radare2](https://www.youtube.com/watch?v=LAkYW5ixvhg)
- [Scripting radare2 with python for dynamic analysis - TUMCTF 2016 Zwiebel part 2](https://www.youtube.com/watch?v=y69uIxU0eI8)
- [Solving a Crackme with Cutter and Z3](https://www.youtube.com/watch?v=oNGLIkSUgQo)
- [Handling self modifying code (SMC) with radare2](https://www.youtube.com/watch?v=BBWtpBZVJvQ)
- [Introduction to r2dec](https://www.youtube.com/watch?v=zc8AC5LWvOU)
- [radare2 explained - write over](https://www.youtube.com/watch?v=8GsiQWVlyLg)
- [radare2 explained - Text transformations](https://www.youtube.com/watch?v=pkUw4oX96Fw)
- [Solving "Dialtone" from Google CTF 2019 Quals using Cutter](https://www.youtube.com/watch?v=B3kz_yzNjEw)

### Asciinemas

- [metasploit x86/shikata_ga_nai decoder using r2pipe and ESIL](https://asciinema.org/a/26594)
- [ESIL for Windows programm (IOLI-crackme 0x02)](https://asciinema.org/a/42850)
- [Filter for string's searching (urls, emails)](https://asciinema.org/a/b429iwj4cx5ixpba4l01qxzmk)
- [Manual unpacking UPX on linux 64-bit](https://asciinema.org/a/bei8od5pxnihypp0j91o4ukj0)
- [radare2 classes recovery from rtti itanium](https://asciinema.org/a/201053)
- [example of finding ROP gadgets in dyld library cache](https://asciinema.org/a/IVqUALBLZOxkZu3agxkRydlSn)

### Conferences

- [HITB2019AMS - Overcoming Fear: Reversing with radare2](https://www.youtube.com/watch?v=317dNavABKo) - by @arnaugamez
- [r2con 2019 - videos](https://www.youtube.com/watch?v=yTXNTRV3KbQ&list=PLjIhlLNy_Y9OVAEI5KYs_4jSStmTy-24l), [r2con 2019 - materials](https://github.com/radareorg/r2con2019)
- [r2con 2018](https://www.youtube.com/watch?v=hzz0qTIynPI&list=PLjIhlLNy_Y9Po69BDCTEnrKvwLneSkG26)
- [r2con 2017](https://www.youtube.com/watch?v=URyd4bcV-Ik&list=PLjIhlLNy_Y9Oe-nfcPEpaki0_En5dhQ5S)
- [LinuxDays 2017 - Disassembling with radare2](https://www.youtube.com/watch?v=zhQ1GhlgCMY)
- [SUE 2017 - Reverse Engineering Embedded ARM Devices](https://www.youtube.com/watch?v=oXSx0Qo2Upk)
- [radare demystified (33c3)](https://www.youtube.com/watch?v=fnpBy3wWabA)
- [r2con 2016](https://www.youtube.com/watch?v=QVjrqlo5A9g&list=PLjIhlLNy_Y9O62rjwYD48pVER0EVh1-aU)
- [Reversing with Radare2 - OverDrive Conference](https://www.youtube.com/watch?v=GTreWP1lPzU)
- [Radare2 & frida hack-a-ton 2015](https://vimeo.com/151753106)
- [Radare from A to Z 2015](https://vimeo.com/151753230)
- [Reverse engineering embedded software using Radare2 - Linux.conf.au 2015](https://www.youtube.com/watch?v=R3sGlzXfEkU)
- [OggCamp - Shellcode - vext01](http://blip.tv/file/get/Oggcamp-ReversingShell888.mp4)
- [radare2 In Conversation - Richard Seymour](https://www.youtube.com/watch?v=Fqr19rpcY1w)
- [recon2017 - Bubble Struggle Call Graph Visualization with Radare2 - by mari0n](https://www.youtube.com/watch?v=ofRP2PorryU)

## Slides and Workshops

- [Radare2 cheat-sheet](https://github.com/zxgio/r2-cheatsheet)
- [r2m2 - radare2 + miasm2 = ♥](https://guedou.github.io/r2m2_talks/2016_r2con/slides.pdf)
- [Radare2 Workshop 2015 (Defcon)](https://github.com/maijin/workshop2015)
- [Emulating Code In Radare2](http://radare.org/get/lacon2k15-esil.pdf)
- [Radare from A to Z 2015](http://radare.org/get/RadareAZ-NN2015.pdf)
- [Radare2 Workshop 2015 (Hack.lu)](http://2015.hack.lu/archive/2015/radare2-workshop/)
- [Radare2 & frida hack-a-ton 2015](http://lolcathost.org/b/radare2-ncn2015-hack-a-ton.pdf)
- [radare2: evolution](http://rada.re/get/lacon2k11.pdf)
- [radare2: from forensics to bindiffing ](http://radare.org/get/rooted2011.pdf)
- [ESIL, the Universal IL for radare2 (ZeroNights)](https://www.slideshare.net/AntonKochkov/slidesen)
- [Brief intro to RE using @radareorg](https://github.com/arnaugamez/talks/tree/master/2018/02_noconname-lab)

## Tutorials and Blogs

- [Configuring and running radare2 on mobile Android phones](http://www.blackstormsecurity.com/docs/radare2_arm.pdf)
- [Arbitrary Code Guard vs. Kernel Code Injections](https://www.countercraft.eu/blog/post/arbitrary-vs-kernel/)
- [Radare2 Practical Guide](https://koffiedrinker.be/notes/radare2_practical_guide/) - by @koffiezuiper
- [Radare2 Supporting a new architecture](https://koffiedrinker.be/notes/radare2_cpu_architecture/) - by @koffiezuiper
- [Reversing a Self-Modifying Binary with radare2](https://www.megabeets.net/reversing-a-self-modifying-binary-with-radare2/) - by @megabeets_
- [Linux Malware by @MalwareMustDie](https://www.reddit.com/r/LinuxMalware/)
- [Radare2 - Using Emulation To Unpack Metasploit Encoders](https://blog.xpnsec.com/radare2-using-emulation-to-unpack-metasploit-encoders/) - by @_xpn_
- [Reverse engineering a Gameboy ROM with radare2](https://www.megabeets.net/reverse-engineering-a-gameboy-rom-with-radare2/) - by @megabeets_
- [radare2 as an alternative to gdb-peda](https://monosource.github.io/2016/10/26/radare2-peda/)
- [How to find offsets for v0rtex (by Siguza)](https://gist.github.com/uroboro/5b2b2b2aa1793132c4e91826ce844957)
- [Debugging a Forking Server with r2](https://blankhat.blogspot.ru/2018/01/debugging-forking-server-with-r2_1.html)
- [Defeating IOLI with radare2 in 2017](https://dustri.org/b/defeating-ioli-with-radare2-in-2017.html)
- [Using r2 to analyse Minidumps](http://radare.today/posts/minidump/)
- [Android malware analysis with Radare: Dissecting the Triada Trojan](https://www.nowsecure.com/blog/2016/11/21/android-malware-analysis-radare-triada-trojan/)
- [Reversing EVM bytecode with radare2](https://blog.positive.com/reversing-evm-bytecode-with-radare2-ab77247e5e53)
- [Radare2’s Visual Mode](https://moveax.me/radare2-visual-mode/)
- [Crackme0x03 Dissected with Radare2](https://moveax.me/crackme0x03/)
- [Crackme0x02 Dissected with Radare2](https://moveax.me/crackme0x02/)
- [Crackme0x01 Dissected with Radare2](https://moveax.me/crackme0x01/)
- [Debugging Using Radare2… and Windows!](https://goggleheadedhacker.com/blog/post/5) - by @jacob16682
- [Decrypting APT33’s Dropshot Malware with Radare2 and Cutter – Part 1](https://www.megabeets.net/decrypting-dropshot-with-radare2-and-cutter-part-1/) - by @megabeets_
- [Decrypting APT33’s Dropshot Malware with Radare2 and Cutter – Part 2](https://www.megabeets.net/decrypting-dropshot-with-radare2-and-cutter-part-2/) - by @megabeets_
- [A journey into Radare 2 – Part 2: Exploitation](https://www.megabeets.net/a-journey-into-radare-2-part-2/) - by @megabeets_
- [A journey into Radare 2 – Part 1: Simple crackme](https://www.megabeets.net/a-journey-into-radare-2-part-1/) - by @megabeets_
- [Reverse Engineering With Radare2](https://insinuator.net/tag/radare2/) - by @insinuator
- [radare2 redux: Single-Step Debug a 64-bit Executable and Shared Object](http://davidjwalling.blogspot.ru/2016/10/radare2-redux-single-step-debug-64-bit.html)
- [Reversing and Exploiting Embedded Devices: The Software Stack (Part 1)](https://p16.praetorian.com/blog/reversing-and-exploiting-embedded-devices-part-1-the-software-stack)
- [Binary Bomb with Radare2](https://www.unlogic.co.uk/2016/04/12/binary-bomb-with-radare2-prelude/) - by @binaryheadache
- [crackserial_linux with radare2](https://www.unlogic.co.uk/2016/06/13/crackserial_linux-with-radare2/#crackserial_linux-with-radare2) - by @binaryheadache
- [Examining malware with r2](https://www.unlogic.co.uk/2017/06/28/examining-malware-with-r2/) - by @binaryheadache
- [Breaking Cerber strings obfuscation with Python and radare2](http://aassfxxx.infos.st/article26/breaking-cerber-strings-obfuscation-with-python-and-radare2) - by @aaSSfxxx
- [Radare2 of the Lost Magic Gadget](https://0xabe.io/howto/exploit/2016/03/30/Radare2-of-the-Lost-Magic-Gadget.html) - by @0xabe_io
- [Radare 2 in 0x1E minutes](https://blog.techorganic.com/2016/03/08/radare-2-in-0x1e-minutes/) - by @superkojiman
- [Pwning With Radare2](https://crowell.github.io/blog/2014/11/23/pwning-with-radare2/) - by @crowell
- [How to radare2 a fake openssh exploit](https://dustri.org/b/how-to-radare2-a-fake-openssh-exploit.html) - by jvoisin
- [Disassembling 6502 code with Radare – Part I](https://retro.moe/2015/11/18/disassembling-6502-code-with-radare-part-i/) - by @ricardoquesada
- [Disassembling 6502 code with Radare – Part II](https://retro.moe/2015/12/09/disassembling-6502-core-with-radare-part-ii/) - by @ricardoquesada
- [Unpacking shikata-ga-nai by scripting radare2](http://radare.today/posts/unpacking-shikata-ga-nai-by-scripting-radare2/)
- [This repository contains a collection of documents, scripts and utilities that will allow you to use IDA and R2](https://github.com/radare/radare2ida)
- [Raspberry PI hang instruction](https://www.nowsecure.com/blog/2015/08/16/raspberry-pi-hang-instruction/) - by @pancake
- [Reverse Engineering With Radare2, Part 1](https://samsymons.com/blog/reverse-engineering-with-radare2-part-1/) - by @sam_symons
- [Simple crackme with Radare2](http://remchp.com/blog/?p=126) - by @futex90
- [Pwning With Radare2](http://crowell.github.io/blog/2014/11/23/pwning-with-radare2/) - by @crowell
- [Reversing the FBI malware's payload (shellcode) with radare2](https://www.reddit.com/r/ReverseEngineering/comments/2de2ud/reversing_the_fbi_malwares_payload_shellcode_with/) - by @MalwareMustDie
- [ROPping to Victory](https://jmpesp.me/rop-emporium-ret2win-with-radare-and-pwntools/)
- [ROPping to Victory - Part 2, split](https://jmpesp.me/ropping-to-victory-part-2-split/)
- [Radare2 IO plugin tutorial](https://wenzel.github.io/2018/04/15/radare2-io-plugin-tutorial.html)
- [Unpacking Executables - The ESP Trick](https://goggleheadedhacker.com/blog/post/6)
- [Linux Malware Analysis — Why Homebrew Encryption is Bad](https://goggleheadedhacker.com/blog/post/4)
- [Writing A Malware Config Parser Using Radare2 And Ruby](https://boozallenmts.com/resources/news/writing-malware-config-parser-using-radare2-and-ruby)
- [Hackaday Superconference Badge Hacking](https://citizengadget.com/post/167530351112/hackaday-superconference-badge-hacking)
- [OnePlus Device Root Exploit: Backdoor in EngineerMode App for Diagnostics Mode](https://www.nowsecure.com/blog/2017/11/14/oneplus-device-root-exploit-backdoor-engineermode-app-diagnostics-mode/)
- [GSoC 2018 Final: Debugging and Emulation Support for Cutter](http://radare.today/posts/cutter_debug/)
- [GSoC 2018 Final: Console Interface Improvementes](http://radare.today/posts/cli_improvements/)
- [GSoC 2018 Radeco Pseudo C Code Generation](http://radare.today/posts/gsoc_2018_radeco_pseudo_c_code_generation/)
- [GSoC'18 Final: Type inference](http://radare.today/posts/type_inference/)
- [Easy way for analyzing the GootKit banking malware with radare2](http://reversingminds-blog.logdown.com/posts/7369479where) - by @D00RT
- [Decrypting Mirai Configuration With Radare2 (Part 1)](https://www.taintedbits.com/2018/09/03/decrypting-mirai-configuration-with-radare2-part-1/)
- [Decrypting Mirai Configuration With Radare2 (Part 2)](https://www.taintedbits.com/2018/09/15/decrypting-mirai-configuration-with-radare2-part-2/)
- [Reversing Bushido IOT Botnet by ZullSec](https://www.taintedbits.com/2018/09/02/reversing-bushido-iot-botnet-by-zullsec/)
- [Emulating Decryption Function With Radare2](https://www.taintedbits.com/2018/08/15/emulating-decryption-function-with-radare2/)
- [Automating RE Using r2pipe](https://goggleheadedhacker.com/blog/post/8)
- [Unstacking Strings with Cutter and Radare2](https://securitykitten.github.io/2018/07/06/unstacking-strings-with-cutter-and-radare2.html)
- [English Report of "FHAPPI Campaign" : FreeHosting APT PowerSploit Poison Ivy](http://blog.0day.jp/p/english-report-of-fhappi-freehosting.html)
- [Binary patching and intro to assembly with r2](https://www.leungs.xyz/reversing/2018/06/18/radare2-binary-patching-introduction.html)
- [Ground Zero: Part 3-2 – Reverse Engineering – Patching Binaries with Radare2 – ARM64](https://scriptdotsh.com/index.php/2018/08/13/reverse-engineering-patching-binaries-with-radare2-arm-aarch64/)
- [Intro to radare2 for malware analysi](https://malwology.com/2018/11/30/intro-to-radare2-for-malware-analysis/) - by @asoni
- [Intro to cutter for malware analysis](https://malwology.com/2019/03/14/intro-to-cutter-for-malware-analysis/) - by @asoni
- [Binary Analysis with Jupyter and Radare2](https://isc.sans.edu/forums/diary/Binary+Analysis+with+Jupyter+and+Radare2/24748/)
- [Down the Rabbit Hole - Part II: Analyzing an EFI Application with Radare2](https://erfur.github.io/down_the_rabbit_hole_pt2/) - by @ihavelotsofspac
- [Down the Rabbit Hole - Part III: Patching the Whitelist](https://erfur.github.io/down_the_rabbit_hole_pt3/) - by @ihavelotsofspac
- [Reversing C code in x64 systems with Radare2 part I](http://ly0n.me/2019/01/10/reversing-c-code-in-x64-systems-with-radare2-part-i/)
- [Reversing x64 linux code with Radare2 part II](http://ly0n.me/2019/01/14/reversing-x64-linux-code-with-radare2-part-ii/)
- [Deobfuscating APT32 Flow Graphs with Cutter and Radare2](https://research.checkpoint.com/deobfuscating-apt32-flow-graphs-with-cutter-and-radare2/)
- [Intro to Reversing iOS Swift Apps with radare2](https://grepharder.github.io/blog/0x01_intro_to_reversing_ios_swift_apps_with_radare2.html)
- [MMD-0064-2019 - Linux/AirDropBot](https://blog.malwaremustdie.org/2019/09/mmd-0064-2019-linuxairdropbot.html)
- [Dynamic Instrumentation: Frida And r2frida For Noobs](https://bananamafia.dev/post/r2frida-1/)

## CTF Writeups
- [Reversing MalwareTech challenge with Radare2 and inline assembly](https://prsecurity.org/reversing-malwaretech-challange-with-radare2-and-inline-assembly/)
- [Solving avatao's "R3v3rs3 4"](https://github.com/sghctoma/writeups/blob/master/hacktivity2015-avatao/01-reverse4/01-reverse4.md) - by @sghctoma
- [Solving ‘heap’ from defcon 2014 qualifier with r2](https://www.securityartwork.es/2015/12/16/head-defcon-2/) - by @alvaro_fe
- [Exploiting ezhp (pwn200) from PlaidCTF 2014 with radare2](https://dustri.org/b/exploiting-ezhp-pwn200-from-plaidctf-2014-with-radare2.html)
- [Write-ups from RHME3 pre-qualifications at RADARE2 conference](https://www.riscure.com/blog/write-ups-rhme3-pre-qualifications-radare2-conference/)
- [Hackover CTF 2016 - tiny_backdoor writeup](http://karabut.com/hackover-ctf-2016-tiny_backdoor-writeup.html)
- [Baleful was a challenge relased in picoctf](http://lolcathost.org/b/BalefulRadare_EN_part_1of2.pdf)
- [At Gunpoint Hacklu 2014 With Radare2](https://crowell.github.io/blog/2014/11/23/at-gunpoint-hacklu-2014-with-radare2/) - by @crowell
- [Solving game2 from the badge of Black Alps 2017 with radare2](https://dustri.org/b/solving-game2-from-the-badge-of-black-alps-2017-with-radare2.html)
- [ROPEmporium: Pivot 64-bit CTF Walkthrough With Radare2](http://radiofreerobotron.net/blog/2017/12/04/ropemporium-pivot-ctf-walkthrough2/)
- [ROPEmporium: Pivot 32-bit CTF Walkthrough With Radare2](http://radiofreerobotron.net/blog/2017/11/23/ropemporium-pivot-ctf-walkthrough/)
- [Gynvael - Mission 22 - Solution](https://ctfs.ghost.io/gynvael-mission-22-solution/)
- [Xiomara CTF 2018 - Slammer](https://jbzteam.github.io/xiomaractf2018/Slammer)
- [mrmcd ctf 2017 - once_upon_a_time](https://github.com/chrysh/ctf_writeups/tree/master/mrmcd_ctf_2017/once_upon_a_time)
- [Pinky's Palace siege](https://capsop.com/itsec/english/ctf/vulnhub/2018/09/17/Pinkys-Palace-siege.html)
- [Introduction to Reverse Engineering with radare2 Cutter - Part I](https://www.jamieweb.net/blog/radare2-cutter-part-1-key-terminology-and-overview/)
- [Introduction to Reverse Engineering with radare2 Cutter - Part II](https://www.jamieweb.net/blog/radare2-cutter-part-2-analysing-a-basic-program/)
- [Introduction to Reverse Engineering with radare2 Cutter - Part III](https://www.jamieweb.net/blog/radare2-cutter-part-3-solving-a-crackme-challenge/)
- [Android OWASP crackmes: Write-up UnCrackable Level 2](https://enovella.github.io/android/reverse/2017/05/20/android-owasp-crackmes-level-2.html)

## Tools

- [Docker image encapsulates the reverse-engineering framework](https://hub.docker.com/r/remnux/radare2/)
- [Malfunction - Malware Analysis Tool using Function Level Fuzzy Hashing](https://github.com/Dynetics/Malfunction)
- [rarop - graphical ROP chain builder using radare2 and r2pipe](https://github.com/jpenalbae/rarop)
- [Radare2 and Frida better together](https://github.com/nowsecure/r2frida)
- [r2frida wiki](https://github.com/enovella/r2frida-wiki)
- [Android APK analyzer based on radare2](https://github.com/mhelwig/apk-anal)
- [Cutter - A Qt and C++ GUI for radare2](https://github.com/radareorg/cutter)
- [Fuzzing tool (TFuzz): a fuzzing tool based on program transformation](https://github.com/HexHive/T-Fuzz)
- [Radare2 VMI IO and debugger plugins](https://github.com/Wenzel/r2vmi)
- [Radare2 module for Yara](https://r2yara.readthedocs.io/en/latest/)
- [predator - genetic Algorithm in C++ to evolve assembly opcodes to harm the linux system in order to identify red flags or vulnerabilities](https://github.com/sha0coder/predator)
- [radare2 + miasm2](https://github.com/guedou/r2m2)
- [Use angr inside the radare2 debugger. Create an angr state from the current debugger state.](https://github.com/andreafioraldi/r2angrdbg)
- [Bootloader research tools (very much a work in progress)](https://github.com/bx/bootloader_instrumentation_suite)
- [ICSREF: ICS Reverse Engineering Framework](https://github.com/momalab/ICSREF)
- [Extract labels from IDA .lst or Ghidra .csv file and export x64dbg database. Supporting radare2](https://github.com/utkonos/lst2x64dbg)
- [Deep ghidra decompiler integration for radare2](https://github.com/radareorg/r2ghidra-dec)

## Scripts

- [r2kit - a set of scripts for a radare-based malware code analysis workflow](https://github.com/cmatthewbrooks/r2kit) - by @cmatthewbrooks
- [Malware analysis toolbox](https://github.com/redmed666/malware_analysis_tools)
- [helper radare2 script to analyze UEFI firmware modules](https://github.com/mytbk/radare-uefi)
- [ThinkPwn Scanner](https://github.com/Cr4sh/ThinkPwn/blob/master/scan_thinkpwn.py) - by @d_olex and @trufae
- [radare2-lldb integration](https://github.com/nowsecure/r2lldb)
- [create a YARA signature for the bytes of the current function](https://gist.github.com/cmatthewbrooks/ea38729ec5f69c8c7c966d3e37016020)
- [A radare2 Plugin to perform symbolic execution with a simple macro call (r2 + angr)](https://github.com/gast04/r4ge)
- [Just a simple radare2 Jupyter kernel](https://github.com/guedou/jupyter-radare2)
- [r2scapy - a radare2 plugin that decodes packets with Scapy](https://github.com/guedou/r2scapy)
- [A plugin for Hex-Ray's IDA Pro and radare2 to export the symbols recognized to the ELF symbol table](https://github.com/danigargu/syms2elf)
- [radare2 plugin - converts asm to pseudo-C code (experimental)](https://github.com/wargio/r2dec-js)
- [A python script using radare2 for decrypt and patch the strings of GootKit malware](https://github.com/d00rt/gootkit_string_patcher)
- [Collection of scripts for radare2 for MIPS arch](https://github.com/mrmacete/r2scripts/)
- [Extract functions and opcodes with radare2](https://github.com/andrewaeva/strange-functions) - by @andrewaeva
- [r2-ropstats - a set of tools based on radare2 for analysis of ROP gadgets and payloads](https://github.com/shaded-enmity/r2-ropstats)
- [Patch kextd using radare2](https://github.com/Tyilo/kextd_patcher)
- [Python-r2pipe script that draws ascii and graphviz graphs of library dependencies](https://github.com/radare/radare2-r2pipe/blob/master/python/examples/libgraph.py)
- [Simple XOR DDOS strings deobfuscator](https://github.com/jpenalbae/r2-scripts/tree/master/ddos-xor-deobfuscator) - by @NighterMan
- [Decode multiple shellcodes encoded with msfencode](https://github.com/jpenalbae/r2-scripts/tree/master/msfdecoder) - by @NighterMan
- [Baleful CTF task plugins](https://github.com/radare/radare2-extras/tree/master/baleful)
- [Integration of pwntools and radare2](https://bannsecurity.com/index.php/tutorials/48-integration-of-pwntools-and-radare2)
- [r2scapy - a radare2 plugin that decodes packets with Scapy](https://github.com/guedou/r2scapy) - by @guedou
- [Deobfuscation of API calls in Bitpaymer (v2)](https://github.com/mauronz/malware_analysis/blob/master/deobf_bitpaymer_cutter.py)
- [Prints agx (cross reference graph) with 2 caller levels](https://github.com/apasamar/radare_stuff/blob/master/agx_depth.py)
- [radare2 script to autoname functions by taking it from the assert calls](https://gist.github.com/radare/04612d3804fa72c0cc832d06208cadaf)
- [r2 plugin to read/write memory using the checkm8 exploit](https://github.com/radareorg/radare2-extras/tree/master/checkm8)

## Contributing

[Please refer the guidelines at contributing.md for details](CONTRIBUTING.md).

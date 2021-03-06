# IRC Bot for pentest learning

This project aims to provide a tiny example of how an IRC Bot can serve as an agent of DoS attack.

# Quick start

Make sure that you have IO::Socket dependency and Threads support at your Perl setup and run the following commands:

**On a Linux shell:**

```
$ sudo chmod 744 irc-bot
$ ./irc-bot
```

**On a Windows Prompt:**

```
x:\> perl irc-bot
```

# FAQ

Q: How do I evaluate whether the attack is happening successfully??<br/>
A: At Bash shell, run `sudo tcpdump -i <interface> -v udp` and watch if the packets are being sent.

# Contributing

Please, feel free to send us pull requests or suggestions.

# Indirect collaboration

* Thanks to XXxxImmortalxxXX of Go4Expert. Your [article](http://www.go4expert.com/articles/irc-bot-perl-t11831/) was fundamental to the start of this project.
* Thanks to Artem Nosulchik of LINUX SCREW for [UDP Flood](http://www.linuxscrew.com/2008/04/10/tiny-perl-script-for-udp-flooding/) source.

# Changelog

None so far.

# License

This software is under GPL v3 license. For further information, please take a look on LICENSE file.

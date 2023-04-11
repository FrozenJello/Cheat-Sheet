<p align="center">
  <img src="https://github.com/Kitsun3Sec/Pentest-Cheat-Sheets/blob/master/CheatSheets/28533648.png" alt="Pentest Cheat Sheets" width="300" />
</p>

# Pentest-Cheat-Sheets
This repo has a collection of snippets of codes and commands to help our lives!
The main purpose is not be a crutch, this is a way to do not waste our precious time!
This repo also helps who trying to get OSCP. You'll find many ways to do something without Metasploit Framework.

## Ninja Tricks

- [Recon](#recon)
  - [DNS](#dns)
  - [Nmap](#nmap)
  - [NetCat](#netcat)
  - [Mysql](#mysql)
  - [MS SQL](#ms-sql)
  - [Web Enumeration](#web-enumeration)
- [Exploitation](#exploitation)
  - [System Network](#system-network)

  - [Web Application](#web-application)

- [Post-exploitation](#post-exploitation)
  - [Reverse Shell](#reverse-shell)

- [Resources](#resources)
  - [Wordlist](#wordlist)
    - [seclist](#seclist)
    - [cotse](#cotse)
    - [PacketStorm](#packetstorm)
  - [Default Passwords](#default-passwords)
    - [Default Passoword](#default-password)
    - [Router Password](#Router-password)


# Recon

## DNS

### Nslookup

Resolve a given hostname to the corresponding IP.

```shell
nslookup targetorganization.com
```

### Reverse DNS lookup

```shell
nslookup -type=PTR IP_address
```
# resources

## Wordlist

* Wordlists
  * [PacketStorm](https://packetstormsecurity.com/Crackers/wordlists/dictionaries/)
  * [SecList](https://github.com/danielmiessler/SecLists)
  * [cotse](http://www.cotse.com/tools/wordlists1.htm)
* Default Password
  * [DefaultPassword](http://www.defaultpassword.com/)
  * [RouterPassword](http://www.routerpasswords.com/)
* Leak
  * [Pastebin](https://pastebin.com)
* Tables
  * [RainbowCrack](https://project-rainbowcrack.com/table.htm)


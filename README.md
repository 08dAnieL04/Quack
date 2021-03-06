# Quack Toolkit

![quack](https://i.imgur.com/dXxtAt7.jpg)

<p align="center">
  <a href="http://egozi.cf/">
    <img src="https://img.shields.io/badge/EgoziProject-Daniel%20Shten-blue.svg">
  </a>
  <a href="https://github.com/08dAnieL04/quack/releases">
    <img src="https://img.shields.io/github/v/release/08dAnieL04/quack.svg">
  </a>
  <a href="https://wikipedia.org/wiki/Python_(programming_language)">
    <img src="https://img.shields.io/badge/language-python-blue.svg">
 </a>
  <a href="https://github.com/08dAnieL04/quack/issues?q=is%3Aissue+is%3Aclosed">
      <img src="https://img.shields.io/github/issues/08dAnieL04/quack.svg">
  </a>
  <a href="https://github.com/08dAnieL04/quack/wiki">
      <img src="https://img.shields.io/badge/Wiki%20-Quack-lightgrey.svg">
 </a>
  <a href="https://twitter.com/08dAnieL04">
    <img src="https://img.shields.io/badge/Twitter-@08dAnieL04-blue.svg">
 </a>
</p>

***

# About Quack Toolkit

```
Quack Toolkit is a set of tools to provide denial 
of service attacks. Quack Toolkit includes SMS attack 
tool, HTTP attack tool and many other attack tools.
```

***

# Getting started

## Quack installation

> cd Quack

> chmod +x install.sh

> ./install.sh

## Quack uninstallation

> cd Quack

> chmod +x uninstall.sh

> ./uninstall.sh

***

# Quack Toolkit execution

> quack -h

```
usage: quack [-h] [--target <IP:port/URL/phone>]
             [--tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]]
             [--timeout <timeout>] [--threads <threads>] [-u] [--version]

optional arguments:
  -h, --help            show this help message and exit
  --target <IP:port/URL/phone>
                        Target IP:port, URL or phone.
  --tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]
                        Attack tool.
  --timeout <timeout>   Timeout in secounds.
  --threads <threads>   Threads count.
  -u, --update          Update Quack Toolkit.
  --version             Show Quack Toolkit version.
```

***
  
# Quack Toolkit examples

## Example of the SMS attack
    
> quack --tool SMS --target 15554443333 --timeout 10 --threads 10
    
## Example of the HTTP attack

> quack --tool HTTP --target http://<span></span>example.com/ --timeout 10 --threads 10
    
## Example of the TCP attack

> quack --tool TCP --target 192.168.1.100:80 --timeout 10 --threads 10

***

# Quack Toolkit disclaimer

```
Usage of the Quack Toolkit for attacking targets without prior mutual consent is illegal.
It is the end user's responsibility to obey all applicable local, state, federal, and international laws.
Developers assume no liability and are not responsible for any misuse or damage caused by this program.
```

***

# Quack Toolkit license

By :- dAnieL Leave a Credit

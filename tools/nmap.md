# Nmap

Nmap is an essential tool for reconnaisance through its port scanning features.

## Basics:
```bash
man nmap
```
Will obviously bring up the man page for nmap.
<br>

```bash
nmap -h
```
Equally, this brings up the help page.

## Basic parameters:
```bash
nmap -sS
```
This will run a **Syn Scan**, also known as a stealth scan.
<br>

```bash
nmap -sU
```
This will run a **UDP** Scan.
<br>

```bash
nmap -O
```
This will enable **OS Detection**.
<br>

```bash
nmap -sV
```
This will enable service version detection.
<br>

```bash
nmap -v
# or this
nmap -vv
```
These will show the **Verbose** output, the `-vv` simply means Very verbose.
<br>

```bash
nmap -oX
```
This will save the output in an **XML** file.
<br>

```bash
nmap -A
```
This will provide an **Agressive** scan.
<br>

```bash
nmap -T5
```
This will set the **timing** to the max level, however this can be adjusted on a 1-5 scale.
<br>

```bash
nmap -p 4444
```
Scan a **specific port**, in this case `4444`.
<br>

```bash
nmap -p-
```
Scan **all ports**.
<br>

```bash
nmap --script vuln
```
this will run all **scripts** out of the **vulnerability category**
<br>

```bash
nmap -Pn
```
**Dont ping** the host.
<br>

> Last updated by Chris Harris (@cjharris18) on the 27th October 2020.

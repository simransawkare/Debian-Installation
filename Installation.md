# Debian Installation

https://www.debian.org/download.es.html

- Virtual Box Setup
- New
- name - Debian > type - Linux > Version - Debian ( 64-bit )
- Memory Size - 1024
- Create a virtual disk now
- VDI ( Virtual Disk Image )
- Dynamically allocated
- File Location and size - 40 GB.
- start machine > select ISO of Debian > start

---

## Installation 

### Menu

1. Graphical Installation
2. Install in only tab interface / mouse not working { use on graphic card problems }
3. Advance Option { rescue mode available }
4. for colour blindness peoples
5. help
6. colour blind peoples

#### Graphical Installation

- Language - English > Location - India > Keyboard - American english > Continue
- Hostname - simran
- domain ( optional )
- Root password - \****
- User simran
- make one user - simran > Password
- select mannual ( anathot 3 options can format hard drive and install kali ) > create partition table > allocate 60 gb space minimum > /boot partition - 1 gb , ext 4 / xfs > swap - 1 gb > / - XFS file system > yes > start installation
- no
- debian.org > > >
- software selection - only tick to " standard system utilities "
- install the GRUB boot loader - /dev/sda (ata-VBOX_HARDDISK_VB54d83273-e93359f9)

---

### Configuration

```bash
apt install bash*
```

```bash
apt install vim
```

```bash
apt install net-tools
```

```bash
apt install openssh-server
```

```bash
apt install ssh
```

```bash
vim /etc/ssh/sshd_config
```

```bash
# on line no. 34 root login = yes
```

```bash
systemctl restart sshd
```

```bash
systemctl enable ssh
```

```bash
systemctl restart sshd
```

```bash
vim /etc/network/interfaces
```

```bash
# give static IP
```

```bash
cat /etc/os-release
```

```bash
cat /etc/apt/sources.list
```

```bash
# https://debgen.simplylinux.ch/
```

If tab is not working:

```bash
apt install net-tools
```

```bash
apt install vim
```

```bash
apt install bash*
```

```bash
apt install bash-completion
```

```bash
apt install --reinstall bash-completion
```

---

### Debian sourcelist file content

```bash
# deb cdrom:[Debian GNU/Linux 11.3.0 _Bullseye_ - Official amd64 NETINST 20220326-11:22]/ bullseye main  

#deb cdrom:[Debian GNU/Linux 11.3.0 _Bullseye_ - Official amd64 NETINST 20220326-11:22]/ bullseye main  

deb http://deb.debian.org/debian/ bullseye main  
deb-src http://deb.debian.org/debian/ bullseye main  

deb http://security.debian.org/debian-security bullseye-security main  
deb-src http://security.debian.org/debian-security bullseye-security main  

# bullseye-updates, to get updates before a point release is made;  
# see https://www.debian.org/doc/manuals/debian-reference/ch02.en.html#_updates_and_backports  
deb http://deb.debian.org/debian/ bullseye-updates main  
deb-src http://deb.debian.org/debian/ bullseye-updates main  

# This system was installed using small removable media  
# (e.g. netinst, live or single CD). The matching "deb cdrom"  
# entries were disabled at the end of the installation process.  
# For information about how to configure apt package sources,  
# see the sources.list(5) manual.
```

---

### Debian full screen on virtualbox

Debian full screen on virtualbox.
- https://gransfall.com/virtual-box-how-configure-full-screen-for-debian/

Debian full screen on virtualbox.
- https://unix.stackexchange.com/questions/3889/how-to-make-a-distro-be-fullscreen-on-virtualbox

---

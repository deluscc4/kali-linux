# Kali Linux

## This is a repository made for taking notes from my study.<br>

### Kali's community and documentation: https://www.kali.org/docs/

# What is Kali?
### Kali is a free Operational system Linux-based which has more than 300 tools for hacking.

## Timeline
### 2006, May: << back | track 5r³
- Security audit;
- Log archives collecting.

### 2007: Metasploit.<br>
### 2013: Ubuntu Lucid > .deb ==> Kali Linux.


# Installation

1. Live CD: Flash drive or CD-ROM;
- Rufus: https://rufus.ie/pt_BR/
- Kali (Bare Metal) ISO (Identical Storage Image of optical media): https://www.kali.org/get-kali/
- Device > Your physical media;
- Boot selection > ISO;

2. Virtual machine: VirtualBox or VMWare;
- VirtualBox: https://www.virtualbox.org/wiki/Downloads
- Kali ISO (Identical Storage Image of optical media): https://www.kali.org/get-kali/
- VM Import > ISO;
- Login: kali | Password: kali.

3. Direct installation, your only OS;

4. Dual-boot: when starting the computer, you choose which one you desire.
- Windows search: diskmgmt.msc > Right click on (C:) > Shrink volume > 50 GB;
- Right click on 'Unallocated' > New Simple Volume;
- Start a boot with your Live CD > Graphical install;
- Select language > Default hostname > Domain name empty > Username, login and password: kali 
- Partition disks steps: Manual > Select logical 52.4 GB > Resize the partition (currently 52.4 GB) > Yes > 48.4 GB >;
- Select logical 48.4 GB > Use as: Ext4 journaling file system (first option) > Mount point: / - the root file system >;
- Done setting up the partition > Select logical 4.0 GB > Create a new partition > Use as: swap area > Done >;
- Finish partitioning and write changes to disk > Yes > Continue> Install the GRUB boot loader (Yes) > Select /dev/sda >;
- Reinstall the machine.

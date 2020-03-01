![](Metasploit-1.png)

# Metasploit Framework Installer

Author: Rapid7 LLC

For termux installation:

$apt install git -y

$git clone https://github.com/471D38UNNUX/Metasploit-Framework-Installer

$cd Metasploit-Framework-Installer

$bash Metasploit-Framework-Installer-For-Termux.sh

For start Metasploit Framework.

$msfconsole

For linux installation:

#sudo apt install git -y (for Linux based on Debian)

#sudo yum install git -y (for Linux based on Red Hat)

#sudo zypper install git (for Linux based on SUSE)

#sudo  pacman -S git (for Linux based on Arch)

#git clone https://github.com/471D38UNNUX/Metasploit-Framework-Installer

#cd Metasploit-Framework-Installer

#cd Linux

#bash Metasploit-Framework-Installer-For-(your linux based).sh

For start Metasploit Framework.

#msfconsole

For Linux based on Red Hat and SUSE command not found problem copy all files in msfix to /bin

For Kali/Parrot installation:

#sudo apt install git -y

#git clone https://github.com/471D38UNNUX/Metasploit-Framework-Installer

#cd Metasploit-Framework-Installer

#cd Linux

#bash Metasploit-Framework-Installer-For-Kali.sh

For start Metasploit Framework.

#msfconsole

You can also use linux based on Debian method.

Nb: for Linux WSL 1 version, before install Metasploit Framework, please turn off all antivirus and firewall.

For windows installation:

Before install Metasploit Framework, please turn off all antivirus and firewall.

First download and install Git Bash and Postgresql in this link:

Git Bash  : https://git-scm.com/downloads

Postgresql: https://www.enterprisedb.com/downloads/postgres-postgresql-downloads

After install git, open your cmd and run this script:

git clone https://github.com/471D38UNNUX/Metasploit-Framework-Installer

cd Metasploit-Framework-Installer

Metasploit-Framework-Installer-For-Windows.bat (Windows 10 build 17063 or newer)

For windows earlier version than Windows 10 build 17063:

cd Windows Old

cd (32/64) bit

Metasploit-Framework-Installer-For-Windows.bat

Before run Metasploit Framework, run postgresql service first:

Search and open pgAdmin 4.

Click on Servers > PostgreSQL in the left tree.

Enter super user password set during installation.

For run Metasploit Framework:

Open cmd and run this command:

msfdb init

msfconsole

For update Metasploit Framework run msfupdate

Enjoy.

![](fery_metasploit.png)

Nb: I'm not owner this tool, but i just made installation for usage more easier.

For more information you can visit official website: https://www.rapid7.com/products/metasploit/

Official repository: https://github.com/rapid7/metasploit-framework

Rapid7 channel: https://www.youtube.com/channel/UCnctXOUIeRFu1BR5O0W5e9w

![](rapid7-logo.jpg)

# pico-ctf-scan-surprise

# scan surprise

A brief description of what this project does and who it's for
(kali㉿kali)-[~]
└─$ cd Downloads
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads]
└─$ ls
challenge.zip  garden.jpg  red.png
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads]
└─$ unzip challenge.zip 
Archive:  challenge.zip
   creating: home/ctf-player/drop-in/
 extracting: home/ctf-player/drop-in/flag.png  
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads]
└─$ ls
challenge.zip  garden.jpg  home  red.png
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads]
└─$ cd home     
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home]
└─$ ls
ctf-player
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home]
└─$ cd ctf-player 
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home/ctf-player]
└─$ ls
drop-in
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home/ctf-player]
└─$ cd drop-in   
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home/ctf-player/drop-in]
└─$ ls
flag.png
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home/ctf-player/drop-in]
└─$ exiftool flag.png  
ExifTool Version Number         : 13.10
File Name                       : flag.png
Directory                       : .
File Size                       : 350 bytes
File Modification Date/Time     : 2024:03:11 20:10:50-04:00
File Access Date/Time           : 2024:03:11 20:10:50-04:00
File Inode Change Date/Time     : 2025:04:16 11:46:37-04:00
File Permissions                : -rw-r--r--
File Type                       : PNG
File Type Extension             : png
MIME Type                       : image/png
Image Width                     : 99
Image Height                    : 99
Bit Depth                       : 1
Color Type                      : Palette
Compression                     : Deflate/Inflate
Filter                          : Adaptive
Interlace                       : Noninterlaced
Palette                         : (Binary data 6 bytes, use -b option to extract)
Transparency                    : 255 255
Pixels Per Unit X               : 2834
Pixels Per Unit Y               : 2834
Pixel Units                     : meters
Image Size                      : 99x99
Megapixels                      : 0.010
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home/ctf-player/drop-in]
└─$ zbarimg            
Command 'zbarimg' not found, but can be installed with:
sudo apt install zbar-tools
Do you want to install it? (N/y)y
sudo apt install zbar-tools
[sudo] password for kali: 
The following packages were automatically installed and are no longer required:
  icu-devtools  libflac12t64  libgeos3.13.0  libglapi-mesa  libicu-dev  liblbfgsb0  libpoppler145  libpython3.12-minimal  libpython3.12-stdlib  libpython3.12t64  python3-setproctitle  python3.12-tk  ruby-zeitwerk  strongswan
Use 'sudo apt autoremove' to remove them.

Installing:
  zbar-tools
                                                                                                                                                                                                                                            
Suggested packages:
  zbarcam-gtk  zbarcam-qt

Summary:
  Upgrading: 0, Installing: 1, Removing: 0, Not Upgrading: 7
  Download size: 37.8 kB
  Space needed: 101 kB / 3,248 MB available

Get:1 http://kali.download/kali kali-rolling/main amd64 zbar-tools amd64 0.23.93-7 [37.8 kB]
Fetched 37.8 kB in 2s (17.2 kB/s)   
Selecting previously unselected package zbar-tools.
(Reading database ... 416601 files and directories currently installed.)
Preparing to unpack .../zbar-tools_0.23.93-7_amd64.deb ...
Unpacking zbar-tools (0.23.93-7) ...
Setting up zbar-tools (0.23.93-7) ...
Processing triggers for dbus (1.16.2-1) ...
Processing triggers for kali-menu (2025.1.1) ...
Processing triggers for man-db (2.13.0-1) ...
Scanning processes...                                                                                                                                                                                                                       
Scanning linux images...                                                                                                                                                                                                                    

Running kernel seems to be up-to-date.

No services need to be restarted.

No containers need to be restarted.

No user sessions are running outdated binaries.

No VM guests are running outdated hypervisor (qemu) binaries on this host.
                                                                                                                                                                                                                                            
┌──(kali㉿kali)-[~/Downloads/home/ctf-player/drop-in]
└─$ zbarimg flag.png 
QR-Code:picoCTF{p33k_@_b00_d4ca652e}
scanned 1 barcode symbols from 1 images in 0.03 seconds


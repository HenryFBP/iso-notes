Hashes are MD5 by default.

## Sites

- <https://mirror.mika.moe/>

## Win10_Pro_1703_English_x64_June_2017.iso mshaz1000.iso

### Hashes:

    SHA-1: B9112A0AC29B93FA2598476AA13F7F0966332A76

### Notes

- <magnet:?xt=urn:btih:51f1062816f6bf35a2ef21015716b66a35b0a27f&dn=Win10Pro1703EnglishX64June2017.isoMshaz1000&tr=udp://tracker.openbittorrent.com:80&tr=udp://tracker.opentrackr.org:1337/announce>

This folder:

    \sources\$OEM$

Has some really SUS files in it.

Seem to be shitty hacktools that are just repacked KMS activator. Maybe RATs or Trojans.

Opened the files with PPEE and there are a bunch of encrypted strings, which is even more sus.

So, don't run them unless you don't care about that. Ideally, use "Reset this PC" immediately after installing this ISO. I did that, and the files were gone. Install MalwareBytes and run a full scan after to be safe(r). I did that and found 0 items.

Then, after that, just run `git clone https://github.com/HenryFBP/KMS-activator` and activate if Windows ever expires.

These SUS files specifically:

#### \sources\$OEM$\$$\SETUP\SCRIPTS\Re-LoaderByR@1n.exe

- https://www.virustotal.com/gui/file/4ac8f2d8a45abe82179aa85d0a3aa4613a230d126f0eba82591fb43a7a7e46b2/detection

MD5	686a5620c3da7834205c14d95d2a2d10
SHA-1	aa92ac2cbcc42758b739bab0f60aa5b10cb8b34f
SHA-256	4ac8f2d8a45abe82179aa85d0a3aa4613a230d126f0eba82591fb43a7a7e46b2
Vhash	21603655156901431z1a
Authentihash	48b93951a736755984500fc9e6994c6947232bb46cbbbeffa3aa0a52581e6fe2
Imphash	f34d5f2d4577ed6d9ceec516c1f5a744
SSDEEP	24576:2kgmiJVSExWaicZhTAb1KbQrV+0xxb0V++gXgEjIIxF+XqU3VGEqgLc7Vl:21poGAb106V+r8wCtU3V/q0YVl
TLSH	T10E751248D85A6B94CF56B6F219D65E8F592C3C034E68C3B62430BEDB5571FA3CE0898C
File type	Win32 EXE
Magic	MS-DOS executable, MZ for MS-DOS
TrID	Win32 Executable (generic) (52.9%)
TrID	Generic Win/DOS Executable (23.5%)
TrID	DOS Executable Generic (23.5%)
File size	1.51 MB (1584122 bytes)
PEiD packer	.NET executable


#### \sources\$OEM$\$1\Users\Public\Desktop\Aktivator!!!\Re-LoaderByR@1n.exe

Same as above.

#### \sources\$OEM$\$1\Users\Public\Desktop\Aktivator!!!\KMS Tools Portable 06_08_2016_\KMSTools.exe

- <https://www.virustotal.com/gui/file/3fd5a6f633a45a5a6a18ebb19277eda4a39c7faf3f0a4b687398197e2087c829/detection>

MD5	c987215b6635eb581e04e1c4f332fd77
SHA-1	a1f36010746ba572e4a8ab23dd34c6bbdb9eed35
SHA-256	3fd5a6f633a45a5a6a18ebb19277eda4a39c7faf3f0a4b687398197e2087c829
Vhash	01705656655d75724012z28007840073z9035zd1z28c1z7019z
Authentihash	12143b45a039cff31bdb71ab65314326afdc06df12819028fd0f52a8ce61d1c9
Imphash	cba3b27c57f8bba41d26d9c72220ba95
SSDEEP	393216:y2WtB6YmNeD/5yVYwVnyAiTduMlHnAfcXFh2dx734dZL:y206Y3D/9wVny3TcM9Afqjmxru
TLSH	T1CE1722323282C2BED95139F1DC996EB1126D7E154A26CCC362B0BE0DB6B25E3ED7550C
File type	Win32 EXE
Magic	PE32 executable for MS Windows (GUI) Intel 80386 32-bit
TrID	InstallShield setup (49%)
TrID	Microsoft Visual C++ compiled executable (generic) (18.8%)
TrID	Win64 Executable (generic) (11.9%)
TrID	Win16 NE executable (generic) (5.7%)
TrID	Win32 Executable (generic) (5.1%)
File size	17.69 MB (18553976 bytes)


## Win10_20H2_English_x64.iso

### Hashes

    CRC32: 23717768
    CRC64: 3C5D816E0EA91787
    SHA256: E793F3C94D075B1AA710EC8D462CEE77FDE82CAF400D143D68036F72C12D9A7E
    SHA1: 30DD6A48DFEA77C37E51573BCB75BE4EDD6FEBFF
    BLAKE2sp: BEAE1CB28A2BC2EC9410352AD976D744A935956501B5DE26160ECC22C7359B5F

## Win10_1703_English_x64.iso

### If it install W10 Home and not Pro

Odd thing. If Windows 10 Home is installed, booting from the USB Key seems to not allow you to install Windows 10 Pro. Maybe W10 installer reads for product keys on all NTFS drives? Sneaky if true, M$...

Recommend booting into Linux, wiping the drive containing Windows 10 Home, and THEN trying to install Windows 10 Pro... Also, probably don't enable internet at all.

Results: I wiped the HDD. Not sure why it doesn't let me pick Pro. It just installs Home.

Conclusion: Not sure. Do research and find an ISO that works. Thanks M$.

### Notes

-   Works with https://github.com/HenryFBP/KMS-activator
-   No license needed
-   Home OR Pro edition should show up
-   Relevant:
    -   <https://go.microsoft.com/fwlink/?LinkID=799445>
    -   <https://www.microsoft.com/en-us/software-download/windows10>
    -   <https://support.microsoft.com/en-us/help/3159635/windows-10-update-assistant>
    -   <https://archive.org/details/Win10Pro1703EnglishX64June2017.isoMshaz1000>


### Hashes

    MD5: EFFCCFDA8A8DCF0B91BB3878702AE2D8
    SHA1: CE8005A659E8DF7FE9B080352CB1C313C3E9ADCE
    SHA256: B842A801BF1DEDF3ACBFD909F91FB2A741EEF20FDA133DAA1878E46A07EC9237

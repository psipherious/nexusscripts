# build/windows
                 _.-;;-._
          '-..-'|   ||   |
          '-..-'|_.-;;-._|
          '-..-'|   ||   |
    jgs   '-..-'|_.-''-._|


## Scripts to ease setting up the dependencies and building Nexus on Windows.

The process is based off of these instructions https://bitcointalk.org/index.php?topic=149479.0

Several scripts have been added to ease the process. 

# Do this stuff first

## Get the nexusscripts package

Download this zip file

https://github.com/physicsdude/nexusscripts/archive/master.zip

And extract it to C:\

So, when you go to 'This PC > Local Disk (C:)' you see 'nexusscripts-master'.

## Install the msys shell

Get the MinGW installation manager from

http://sourceforge.net/projects/mingw/files/Installer/mingw-get-setup.exe/download

From the MinGW installation manager -> All packages -> MSYS
mark the following for installation:

 msys-autoconf bin
 msys-automake bin
 msys-base bin
 msys-libtool bin

Go to All Packages and make sure or select all of these for installation also

 msys-gzip bin
 msys-libopenssl bin
 msys-sed bin
 msys-tar bin
 msys-wget bin
 msys-zip bin

then click on 

#### Installation -> Apply changes

Make sure no mingw packages are checked for installation or present from a previous install. 
Only the above msys packages should be installed. 
Also make sure that msys-gcc and msys-w32api packages are not installed.

## Install the MinGW-builds project toolchain

Download 

http://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/4.9.2/threads-posix/dwarf/i686-4.9.2-release-posix-dwarf-rt_v3-rev1.7z/download

and unpack it to C:\ 

## Run the script to set up the prereqs and build Nexus!

Using the windows file explorer, navigate to:

##### C:\nexusscripts-master\build\windows

There should be a file in that directory called

#### start-msys.bat

Double click this file to open the msys shell. 

From here you can run UNIX-like commands like a real haxxor.

Once the command window opens, copy/paste these commands:

    cd /c/nexusscripts-master/build/windows

    ./setup-on-windows.sh

All kinds of info is printed out to the screen.
You can usually ignore this but when something goes wrong,
make sure to save the error messages so you can fix it
or have useful info to ask for help.

When (and if) that script completes successfully, you'll have your very own version of nexus-qt.exe that you built from scratch! Look for a message near the end which will tell you exactly where it is. 

# Great job!


           !
           !
           ^
          / \
         /___\
        |=   =|
        |     |
        |  N  |
        |  E  |
        |  X  |
        |  U  |
        |  S  |
        |     |
        |     |
        |     |
       /|##!##|\
      / |##!##| \
     /  |##!##|  \
    |  / ^ | ^ \  |
    | /  ( | )  \ |
    |/   ( | )   \|
        ((   ))
       ((  :  ))
       ((  :  ))
        ((   ))
         (( ))
          ( )
           .
           .
           .
    
#### A bit of Microsoft history.

Bill Gates' grandfather was J.W. Maxwell. Maxwell founded Seattle's 

# National City Bank in 1906. 

His son, James Willard Maxwell was 

# also a banker 

and 

# established a million-dollar trust fund 

for William (Bill) Henry Gates III.

#### And now for something completely different.

Richard Matthew Stallman (born March 16, 1953), often known by his initials, rms,[1] is an American software freedom activist and programmer. He campaigns for software to be distributed in a manner such that its users receive the freedoms to use, study, distribute and modify that software. Software that ensures these freedoms is termed free software. Stallman launched the GNU Project, founded the Free Software Foundation, developed the GNU Compiler Collection and GNU Emacs, and wrote the GNU General Public License.

https://en.wikipedia.org/wiki/Richard_Stallman

http://www.fsf.org/

http://home.iprimus.com.au/cojoco/rms/157-5746_IMG.JPG

#### How to Install Linux on Windows

https://www.lifewire.com/install-ubuntu-linux-windows-10-steps-2202108

# THE TRUTH IS OUT THERE

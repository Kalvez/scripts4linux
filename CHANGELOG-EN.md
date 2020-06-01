### ..::CHANGELOG - JUN. 01 2020::..
```
-Installer: Small fixes | The 'bc' packages was added during the script installation for Debian, Raspbian & Kali Linux.
-Infos: Deletion of the 'version' line for Debian/Raspbian/Kali Linux & Manjaro. | Deletion of the 'No LSB modules are available' message if no LSB modules are installed. | Supports now bi-GPU setups. | VMware video adapter is now supported.
-Archive: Small translation fixes.
-Manjaro: Deletion of coloured lines in the scripts as it is not supported by the OS.
```
### ..::CHANGELOG - MAY  23 2020::..
```
-Infos: Small bug fix.
-Backup: A 'restore' option has been added. You now either have the choice to backup or restore.
```
### ..::CHANGELOG - MAY  09 2020::..
```
-The '/etc/' folders and subfolders support is dropped in the 'backup' script.
```
### ..::CHANGELOG - MAY  08 2020::..  
```
-Regarding 'archive' & 'backup' : Lesser arguments were used with 'pv' as they weren't that relevant because they did not displayed correct information (such as compression rate and compressed file size).
-Minor bug fixes.
```
### ..::CHANGELOG - MAY  07 2020::..
```
-The 'backup' and 'archive' scripts does not use the '*.zip' format for the benefit of the '*.tar' archive format.
-To optimise the compression time, 'pigz' is now used.
```
### ..::CHANGELOG - MAY  06 2020::..
```
-The 'auto-installer' script has been updated for compatibility reasons regarding Pop!_OS 20.04.
-A 'Graphics' line has been added to the 'infos' script. It now permits to display the used GPU in the computer.
-Creation of an English changelog.
```

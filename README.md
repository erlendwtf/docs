# Generic docs

## How to UPDATE Winget packages @ Microsoft GitHub repo

* winget install wingetcreate
* wingetcreate token -s
* fork the winget-pkgs repo (optional: update your fork if already forked)
* terminal -> cd c:\winget\winget-pkgs
* (optional: git pull)
* wingetcreate update Dell.CommandUpdate.Universal -v 5.0.0 -u https://dl.dell.com/FOLDER10408436M/1/Dell-Command-Update-Windows-Universal-Application_1WR6C_WIN_5.0.0_A00.EXE`|x64 -o C:\winget\winget-pkgs
* wingetcreate submit --prtitle "New version: Dell.CommandUpdate.Universal 5.0.0" C:\winget\winget-pkgs\manifests\d\Dell\CommandUpdate\Universal\5.0.0

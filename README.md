<div style="display: flex; align-items: center;">
 <img src="https://github.com/user-attachments/assets/05656b48-97c5-4492-8951-a531d3df4fc9" alt="Command Logo" style="width: 10%; margin-right: 20px;">
  <h1>Windows Command Lines Cheat Sheet</h1>
</div>

Are you looking to boost productivity and streamline your workflow on Windows? This document helps you master essential command lines for efficient system management. Explore these commands, sorted by usage frequency, to work smarter and become more proficient, reducing time spent on repetitive tasks.

## Frequently Used Commands

1. **Display IP Configuration**: `ipconfig /all`
2. **Ping a Host**: `ping hostname_or_ip`
3. **List Files and Directories**: `dir`
4. **Change Directory**: `cd path\to\directory`
5. **Copy Files**: `copy source_file destination_directory`
6. **Move Files**: `move source_file destination_directory`
7. **Delete Files**: `del file_name`
8. **Create a Directory**: `mkdir directory_name`
9. **Remove a Directory**: `rmdir /s /q directory_name`
10. **System Information**: `systeminfo`

## Moderately Used Commands

1. **Flush DNS Cache**: `ipconfig /flushdns`
2. **Display ARP Cache**: `arp -a`
3. **List Running Processes**: `tasklist`
4. **Kill a Process**: `taskkill /IM process_name.exe /F`
5. **Open Task Manager**: `taskmgr`
6. **Open Device Manager**: `devmgmt.msc`
7. **Open Disk Management**: `diskmgmt.msc`
8. **Open Event Viewer**: `eventvwr.msc`
9. **Shut Down**: `shutdown /s /f /t 0`
10. **Restart**: `shutdown /r /f /t 0`
11. **Log Off**: `shutdown /l`
12. **Lock Computer**: `rundll32.exe user32.dll,LockWorkStation`

## Less Frequently Used Commands

1. **Grant Full Control to a User**: `icacls path\to\file /grant username:F`
2. **Remove a User’s Access**: `icacls path\to\file /remove username`
3. **Change File Attributes**: `attrib +r -a +h -s filename`
4. **Check Disk Usage**: `chkdsk`
5. **Open Group Policy Editor**: `gpedit.msc`
6. **List User Accounts**: `net user`
7. **Create User Account**: `net user username password /add`
8. **Delete User Account**: `net user username /delete`
9. **Add User to Group**: `net localgroup group_name username /add`
10. **Remove User from Group**: `net localgroup group_name username /delete`

## Rarely Used Commands

1. **System File Checker**: `sfc /scannow`
2. **Check and Repair Disk**: `chkdsk /f`
3. **Edit System Registry**: `regedit`
4. **List Network Interfaces**: `ipconfig /all`
5. **Release IP Address**: `ipconfig /release`
6. **Renew IP Address**: `ipconfig /renew`
7. **Open Performance Monitor**: `perfmon.msc`
8. **List All Services with Status**: `sc query`
9. **Configure Service to Start Automatically**: `sc config service_name start= auto`
10. **Stop a Service**: `net stop service_name`
11. **Start a Service**: `net start service_name`
12. **Check Firewall Status**: `netsh advfirewall show allprofiles`
13. **Enable Firewall**: `netsh advfirewall set allprofiles state on`
14. **Disable Firewall**: `netsh advfirewall set allprofiles state off`
15. **Add a Firewall Rule**: `netsh advfirewall firewall add rule name="RuleName" protocol=TCP dir=in localport=PortNumber action=allow`
16. **Delete a Firewall Rule**: `netsh advfirewall firewall delete rule name="RuleName"`

## Advanced and Specialized Commands

1. **Set Password for User**: `net user username new_password`
2. **List Local Groups**: `net localgroup`
3. **Create a New Local Group**: `net localgroup group_name /add`
4. **Delete a Local Group**: `net localgroup group_name /delete`
5. **Set Sleep Timer**: `powercfg /change standby-timeout-ac 30`
6. **Set Hibernate Timer**: `powercfg /change hibernate-timeout-ac 60`
7. **Create a Power Plan**: `powercfg /create scheme_name`
8. **Delete a Power Plan**: `powercfg /delete scheme_name`
9. **List Disks**: `diskpart` -> `DISKPART> list disk`
10. **Select a Disk**: `diskpart` -> `DISKPART> select disk 0`
11. **List Partitions**: `diskpart` -> `DISKPART> list partition`
12. **Format a Disk**: `format X: /FS:NTFS`
13. **Convert FAT32 to NTFS**: `convert X: /FS:NTFS`
14. **Check Disk for Errors**: `chkdsk X: /F /R`
15. **Create a Partition**: `diskpart` -> `DISKPART> create partition primary`
16. **Assign a Drive Letter**: `diskpart` -> `DISKPART> assign letter=X`
17. **Hibernate**: `shutdown /h`
18. **Abort Shutdown**: `shutdown /a`

## PowerShell Commands

1. **List Installed Programs**: `Get-WmiObject -Class Win32_Product`
2. **Update Help Files**: `Update-Help`
3. **List Services**: `Get-Service`
4. **Stop a Service**: `Stop-Service -Name service_name`
5. **Start a Service**: `Start-Service -Name service_name`
6. **Restart a Service**: `Restart-Service -Name service_name`
7. **Get Event Logs**: `Get-EventLog -LogName System`
8. **Get Detailed Disk Information**: `Get-PhysicalDisk`
9. **Get System Uptime**: `(Get-CimInstance Win32_OperatingSystem).LastBootUpTime`
10. **Get Installed Windows Features**: `Get-WindowsFeature`
11. **Enable a Windows Feature**: `Enable-WindowsOptionalFeature -Online -FeatureName "FeatureName"`
12. **Disable a Windows Feature**: `Disable-WindowsOptionalFeature -Online -FeatureName "FeatureName"`

## Conclusion

This cheat sheet aims to provide a quick and easy reference for Windows command lines, helping you manage and troubleshoot your Windows systems more effectively. Whether you are a beginner looking to understand basic commands or an advanced user seeking to optimize system performance, this guide covers a wide range of commands to meet your needs. Feel free to explore and make the most out of these powerful command line tools.

Happy learning! 🚀
## Contact

For any questions or feedback, please reach out via email: [gcfjxvkj@gmail.com](gcfjxvkj@gmail.com)


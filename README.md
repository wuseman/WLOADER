# wloader

<p align="center">
  <a href="https://www.youtube.com/watch?v=q-ROJTj0fLU">
    <img src="wloader.png" alt="Watch the video" style="width: 100%; max-width: 600px; border-radius: 10px;">
  </a>
</p>

Windows 10 PRO Activator without using any backdoor loader from China and neither you will need any crack anymore that is valid for a week or two.

This is script is written for cmd. This script will also removing all bloatware from Windows 10. Edit script after your needs.

To display more detailed license information–including the activation ID, installation ID, and other details–run the following command:

```
slmgr.vbs /dlv
```

## Run Windows 11 PRO Installer:

Greetings to: Minionguyjpro - Author

```bash
sc config LicenseManager start= auto & net start LicenseManager
sc config wuauserv start= auto & net start wuauserv
changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T
exit
```


## Upgrade Windows 10/11 to PRO by copy and paste below:

```bash
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
slmgr /skms kms8.msguides.com
slmgr /ato
```

### Activate Windows 10 Enterprise 10.0.19043 N/A Build 19043, full example

```bash
slmgr.vbs /ipk DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4
slmgr /skms kms8.msguides.com
slmgr.vbs /ato
```


### View the License Expiration Date

```
slmgr.vbs /xpr
```

* Remove Activation Key

```
slmgr.vbs /upk
```

### Uninstall Product Key

```
slmgr.vbs /cpky
```

### Set Your License Key

```
slmgr.vbs /ipk #####-#####-#####-#####-#####
```

* Configure slmgr Via Remote

slmgr.vbs computername username password /option

### Windows 10 Keys

```
Home:                TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
Home N:              3KHY7-WNT83-DGQKR-F7HPR-844BM
Professional:        W269N-WFGWX-YVC9B-4J6C9-T83GX
rofessional N:      MH37W-N47XK-V7XM9-C7227-GCQG9
Education:           NW6C2-QMPVW-D7KKK-3GKT6-VCFB2
Education N:         2WH4N-8QGBV-H22JP-CT43Q-MDWWJ
Enterprise:          NPPR9-FWDCX-D2C8J-H872K-2YT43
Enterprise N:        DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4
Enterprise LSTB:     WNMTR-4C88C-JK8YV-HQ7T2-76DF9
Enterprise LSTB N:   2F77B-TNFGY-69QQF-B8YKP-D69TJ
```


### KMS Servers

* Add keys via

    ```bash
    slmgr /skms <server>
    ```

* Some Available Servers

    ```bash
    kms.digiboy.ir
    kms.cangshui.net
    hq1.chinancce.com
    54.223.212.31
    kms.cnlic.com
    kms.chinancce.com
    kms.ddns.net
    franklv.ddns.net
    k.zpale.com
    m.zpale.com
    mvg.zpale.com
    kms.shuax.com
    kensol263.imwork.net:1688
    xykz.f3322.org
    kms789.com
    dimanyakms.sytes.net:1688
    kms.03k.org:1688
    ```


### SLMGR Commands

```bash
slmgr.exe -ato                                    Activate Windows license and product key against Microsoft’s server.
slmgr.exe -atp                                    Confirmation_ID Activate Windows with user-provided Confirmation   ID.
slmgr.exe -ckms                                   Clear the name of KMS server used to default and port to default.
slmgr.exe -cpky                                   Clear product key from the registry (prevents disclosure   attacks).
slmgr.exe -dli                                    Display the current license information with activation status and   partial product key.
slmgr.exe -dlv                                    Verbose, similar to -dli but with more information.
slmgr.exe -dti                                    Display Installation ID for offline activation.
slmgr.exe -ipk                                    Key Enter a new product key supplied as   xxxxx-xxxxx-xxxxx-xxxxx-xxxxx.
slmgr.exe -ilc                                    License_file Install license.
slmgr.exe -rilc                                   Re-install system license files.
slmgr.exe -rearm                                  Reset the evaluation period/licensing status and activation   state of the machine.
slmgr.exe -skms activationservername:port         Set the Volume Licensing KMS server   and/or the port used for KMS activation (where supported by your   Windows edition).
slmgr.exe -skhc                                   Enable KMS host caching (default), this blocks the use of DNS   priority and weight after the initial discovery of a working KMS host.
slmgr.exe -ckhc                                   Disable KMS host caching. This setting instructs the client to   use DNS auto-discovery each time it attempts KMS activation                          
slmgr.exe -sai interval                           Sets the interval in minutes for unactivated clients to   attempt KMS connection. The activation interval must be between 15 - 30 days
slmgr.exe -sri interval                           Sets the renewal interval in minutes for activated   clients to attempt KMS connection. The renewal interval must be between
slmgr.exe -spri                                   Set the KMS priority to normal (default)
slmgr.exe -cpri                                   Set the KMS priority to low.
slmgr.exe -sprt port                              Sets the port on which the KMS host listens for client   activation requests. The default TCP port is 1688.
slmgr.exe -sdns                                   Enable DNS publishing by the KMS host (default).
slmgr.exe -cdns                                   Disable DNS publishing by the KMS host.
slmgr.exe -upk                                    Uninstall current installed product key and return license status   back to trial state.
slmgr.exe -xpr                                    Show the expiry date of current license (if not permanently   activated).   Token-based activation:
slmgr.exe -lil                                    List the installed token-based activation issuance licenses. 
slmgr.exe -ril ILID ILvID                         Remove an installed token-based activation issuance  license. 
slmgr.exe -stao                                   Set the Token-based Activation Only flag, disabling automatic KMS  activation.
slmgr.exe -ctao                                   Clear the Token-based Activation Only flag (default), enabling automatic KMS activation.
slmgr.exe -ltc                                    List valid token-based activation certificates that can activate installed software
slmgr.exe -fta Certificate Thumbprint             Force token-based activation using the   identified certificate. 
```

### Disable RealTime Protection / Windows Defenders / Windows AutoScans

* Print current settings

```bash
Get-MpPreference
```


* Copy and paste for disable all protection at once

```bash
Set-MpPreference -DisableArchiveScanning      $true                
Set-MpPreference -DisableAutoExclusions       $true                   
Set-MpPreference -DisableBehaviorMonitoring   $true              
Set-MpPreference -DisableBlockAtFirstSeen     $true                     
Set-MpPreference -DisableRealtimeMonitoring   $true
Set-MpPreference -DisableScanningNetworkFiles $true                  
Set-MpPreference -DisableScriptScanning       $true                
Set-MpPreference -DisableArchiveScanning      $true
Set-MpPreference -ScanParameters              0
```


### Install WSL2 (Gentoo)

```bash
Enable-WindowsOptionalFeature -NoRestart -Online -FeatureName Microsoft-Windows-Subsystem-Linux
Enable-WindowsOptionalFeature -NoRestart -Online -FeatureName VirtualMachinePlatform
wsl --set-default-version 2
wsl --import gentoo C:\Users\salfter\gentoo\ C:\Users\salfter\Downloads\stage3-amd64-nomultilib-20200624T214505Z.tar --version 2
```

### Resource(s)

    * https://www.reneelab.com/win10-activation-crack-free.html
    * https://docs.microsoft.com/sv-se/windows-server/get-started/kmsclientkeys
    * https://gist.github.com/Minionguyjpro/d913b3931e844ad8ad9a758a4aca4b63

### Get In Touch

If you have problems, questions, ideas or suggestions please contact us by posting to wuseman@nr1.nu

### Website

    * https://wwww.nr1.nu

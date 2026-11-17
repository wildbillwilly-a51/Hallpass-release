# Hallpass releases

H4LLP@55 is a Windows desktop app for choosing a network connection for supported applications.

Download the Windows x64 installer and matching SHA-256 file from the release assets. The installer
includes .NET 10. Run Setup, approve the Windows administrator prompt, then open **H4LLP@55** from
Start. This build is unsigned and may show **Unknown publisher**.

To check the download, run `Get-FileHash -Algorithm SHA256 .\Hallpass-1.0.0-win-x64-Setup.exe` in
PowerShell and compare the hash with the first field of the `.sha256` file.

For the browser extension, expand **Set up a profile** in the dashboard. Before uninstalling, remove
the optional helper if you enabled it, set any browser profile using the extension to **Not changed**,
and exit the app from its tray menu. Then uninstall **H4LLP@55** from Windows Settings.

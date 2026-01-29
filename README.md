# Windows 11 One-Click Setup

⚙️ What It Does
<br> >> Automates Windows 11 deployment using official Microsoft ISO images with pre-configured unattended setup (autounattend.xml). Performs:
<br> >> Automatic partitioning (UEFI/GPT)
<br> >> Silent installation from official sources
<br> >> Pre-configured regional settings & user account
<br> >> TPM 2.0/Secure Boot compliance check

⚠️ Legal Requirements
<br> >> ✅ You MUST have a valid Windows 11 Pro/Home license
<br> >> ✅ Installer downloads ISO only from Microsoft servers
<br> >> ❌ NOT for piracy, license circumvention, or unauthorized distribution
<br> >> ℹ️ Complies with Microsoft's Volume Licensing terms for enterprise deployment

🔒 Security Notice
<br> >> SHA-256 verified Microsoft ISO downloads only
<br> >> No telemetry/malware/backdoors
<br> >> Source code auditable (see /scripts/)
<br> >> Never run unsigned .exe files from untrusted sources

▶️ Usage
```powershell
# 1. Verify digital signature
 Get-AuthenticodeSignature .\Win11-OneClick-Installer.exe
# 2. Run with admin rights (requires valid license key)
 .\Windows11Pro_Installer_x64.exe --license-key YOUR-VALID-KEY
```
📜 License
<br> This tool is a deployment wrapper only.
<br> Windows 11 licensing governed by Microsoft Software License Terms.




<!-- topics: windows-11, windows-deployment, automation, sysadmin, powershell -->


**Run Powershell as Administrator**

Press Windows + X keys together on the keyboard to open the WinX menu. Click on "Windows PowerShell (Admin)".

- Disable Edge Sidebar and Bing Discover Button.
```powershell
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name HubsSidebarEnabled -Value 0
```
- Disable the Edge Collections feature.
```powershell
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name EdgeCollectionsEnabled -Value 0
```
- Disable usage and crash-related data reporting.
```powershell
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name DiagnosticData -Value 0
```
- Disable Shopping features(price comparison, coupons, rebates...) in Microsoft Edge.
```powershell
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name EdgeShoppingAssistantEnabled -Value 0
```
- Disable Microsoft Rewards experience in their Microsoft Edge user profile.
```powershell
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name ShowMicrosoftRewards -Value 0
```

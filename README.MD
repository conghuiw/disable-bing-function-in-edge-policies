**Run Powershell as Administrator**

Press Windows + X keys together on the keyboard to open the WinX menu. Click on "Windows PowerShell (Admin)".

- Enable or Disable Edge Sidebar and Bing Discover Button.
```powershell
#Enable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name HubsSidebarEnabled -Value 1

#Disable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name HubsSidebarEnabled -Value 0
```
- Enable or Disable the Edge Collections feature.
```powershell
#Enable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name EdgeCollectionsEnabled -Value 1

#Disable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name EdgeCollectionsEnabled -Value 0
```
- Enable or Disable usage and crash-related data reporting.
```powershell
#Enable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name DiagnosticData -Value 1

#Disable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name DiagnosticData -Value 0
```
- Enable or Disable Shopping features(price comparison, coupons, rebates...) in Microsoft Edge.
```powershell
#Enable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name EdgeShoppingAssistantEnabled -Value 1

#Disable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name EdgeShoppingAssistantEnabled -Value 0
```
- Enable or Disable personalization of ads.
```powershell
#Enable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name PersonalizationReportingEnabled -Value 1

#Disable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name PersonalizationReportingEnabled -Value 0
```
- Enable or Disable Microsoft Rewards experience in their Microsoft Edge user profile.
```powershell
#Enable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name ShowMicrosoftRewards -Value 1

#Disable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name ShowMicrosoftRewards -Value 0
```
- Enable or Disable Microsoft Edge Desktop Search Bar.
```powershell
#Enable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name WebWidgetAllowed -Value 1

#Disable
Set-ItemProperty -Path HKCU:\Software\Policies\Microsoft\Edge -Name WebWidgetAllowed -Value 0
```

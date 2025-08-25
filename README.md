# Spopscript

Install-Module -Name SharePointPnPPowerShellOnline -Force

# Basic usage (Chrome is the default method)
.\NintexServerExport.ps1 -WebUrl "http://yourserver/sites/yoursite" -ListName "OnboardingList" -OutputPath "C:\Exports\NintexForms"

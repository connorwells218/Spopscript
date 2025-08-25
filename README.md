# Spopscript

Install-Module -Name SharePointPnPPowerShellOnline -Force

# Basic usage (Chrome is the default method)
.\NintexServerExport.ps1 -WebUrl "http://yourserver/sites/yoursite" -ListName "OnboardingList" -OutputPath "C:\Exports\NintexForms"

.\RobustNintexExport.ps1 -WebUrl "https://sp.safalo.com/sites/booth1/johnm" -ListName "New Employee Onboarding" -OutputPath "C:\Exports\NintexForms"


.\SimpleNintexExport.ps1 -WebUrl "https://sp.safalo.com/ConnorsWorkshop" -ListName "OnboardingList" -OutputPath "C:\Exports\NintexForms" -StartID 1 -EndID 10


.\ExportForms.ps1 -WebUrl "https://sp.safalo.com/ConnorsWorkshop" -ListName "OnboardingList" -StartID 1 -EndID 20 -OutputPath "C:\Exports\NintexForms"




https://sp.safalo.com/hr/Lists/OnboardingList/DispForm.aspx?ID=1

https://sp.safalo.com/hr/Lists/OnboardingList/DispForm.aspx?ID=3



.\PreAuthExport.ps1 -WebUrl "https://sp.safalo.com/hr" -ListName "OnboardingList" -StartID 1 -EndID 10 -OutputPath "C:\Exports\NintexForms"

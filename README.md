# Get-CatFacts

Get one (or more!) wonderful facts about cats!

EXAMPLE #1 - Just get one cat fact

	Get-CatFacts
   
EXAMPLE #2 - Get 10 cat facts!

	Get-CatFacts -Number 10
   
To be greeted with an amazing cat fact every time you open your PowerShell console, save a copy of Get-CatFacts.psm1 inside a folder named Get-CatFacts in your %userprofile%\Documents\WindowsPowerShell\Modules\ directory. Then add the following lines to your powershell profile:

	Import-Module Get-CatFacts

	Get-CatFacts

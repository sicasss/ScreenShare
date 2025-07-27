*Hola*
1. Ejecuta porwershell como admin
2. Ejecutas estos comandos dependiendo la herramienta que quieras usar

MiniSS

Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/sicasss/ScreenShare/refs/heads/main/MiniSS.ps1')

LogHazelMC

"Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass; Invoke-Expression (Invoke-RestMethod 'https://raw.githubusercontent.com/sicasss/ScreenShare/refs/heads/main/HazelMC.ps1')"


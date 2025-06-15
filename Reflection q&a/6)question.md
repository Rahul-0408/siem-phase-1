6. Describe how RDP lateral movement is tracked in event logs.

    Event ID 4624 with LogonType = 10 indicates successful RDP login

    Combine with Event ID 4625 for failed RDP attempts

    Sysmon Event ID 3 logs network connections (can show outbound RDP port 3389)

    Lateral tools like PsExec or WMI can also be seen via process logs (Event ID 1)
7. What is the risk of log tampering, and how can we detect it?

Risks: Attackers may delete or alter logs to hide their tracks.

Detection:

    Missing event sequences

    Sudden drop in logging volume

    Use of Windows commands like wevtutil cl

    Sysmon can detect clearing of logs if configured (Event ID 1102 in Security logs)
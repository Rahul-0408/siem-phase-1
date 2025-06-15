4. How does a brute-force attack appear in logs? Mention specific Event IDs.

    Event ID 4625 (Security Log): Shows failed login attempts.

    Repeated 4625 entries with LogonType = 10 indicate RDP brute force.

    Also detectable by source IP repetition, target account reuse, and short intervals between failures.
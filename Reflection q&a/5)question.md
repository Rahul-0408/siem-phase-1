5. How would you detect a login outside normal business hours?

    Use a SIEM query to find Event ID 4624 (successful login)

    Filter by timestamps before 8 AM or after 6 PM

    Correlate with host.name and user.name to check who and where
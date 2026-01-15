incident-handler-journal.md

Journal Entry 1

Date: 2026-01-10
Entry: 1
Description (50–80 words):
A user reported an email that looked like it came from Microsoft 365 asking them to “verify” their account. I captured the email details, checked sender domain spelling, inspected the return-path, and reviewed headers for spoofing clues. I treated this as a potential phishing attempt and documented evidence for escalation. I also noted immediate actions the user should take to avoid clicking links and sharing credentials.

The 5 W’s (4–6 bullets):

Who: Internal employee in finance reported it

What: Email requesting credential verification via a link

When: Reported on 10 January 2026, morning

Where: Corporate email inbox (M365 environment)

Why: Social engineering using urgency and a lookalike domain

Tool(s) used (optional for this entry):

Email header viewer / message details

Basic domain inspection (lookalike detection)

Journal Entry 2

Date: 2026-01-14
Entry: 2
Description (50–80 words):
I investigated repeated failed login attempts flagged by monitoring. I used a SIEM to pull authentication logs and filtered by time range, usernames, and source IP. I checked for password-spraying patterns by looking for many accounts targeted from the same IP and short time intervals between attempts. I documented findings and recommended next steps such as temporary blocks and stronger controls (MFA and lockout policy).

Tool(s) used (3–5 bullets):

SIEM: Queried authentication events (failed + successful logins)

Filtered by source IP, user, and timestamp

Looked for patterns across multiple accounts (spray vs single-user brute force)

Created a short incident timeline from log events

Journal Entry 3

Date: 2026-01-18
Entry: 3
Description (50–80 words):
Endpoint protection generated a malware alert on a workstation. I reviewed the alert details, file path, and detection name, then validated the file hash and whether the file executed. I checked if other endpoints reported the same hash to estimate spread. I documented impact and containment actions, including isolating the host and collecting basic indicators of compromise (IOC) for follow-up.

The 5 W’s (4–6 bullets):

Who: Corporate workstation user (helpdesk ticket raised)

What: Malware detection by endpoint security

When: Detected 18 January 2026, during monitoring

Where: User workstation on corporate network

Why: Suspicious download and execution attempt from an untrusted source

Journal Entry 4

Date: 2026-01-22
Entry: 4
Description (50–80 words):
I reviewed suspicious outbound network activity after an alert about unusual connections. I used packet capture data to inspect destination IPs, ports, and frequency of connections. I compared the traffic to a normal baseline and noted anomalies like rare destination regions or high-volume bursts. I documented the evidence and proposed containment steps: blocking destinations, validating the endpoint, and opening a case for deeper analysis.

Tool(s) used (3–5 bullets):

Packet capture / network analysis tool (pcap review)

Filtered outbound traffic by IP, port, and protocol

Checked connection frequency and data size patterns

Compared observed traffic to baseline expectations

2) Reflection/Notes (6–9 bullets)

I learned to write incident notes that are short but specific enough for another analyst to continue the work.

The 5 W’s format helps me stay structured and prevents missing key facts.

Logs and alerts don’t automatically mean compromise; I must validate evidence.

Tool outputs are only useful when I filter and correlate events properly.

Timelines help explain what happened and support escalation decisions.

I need to separate “what I know” from “what I suspect” in my notes.

Clear documentation reduces confusion during handover and reporting.

Next, I want to improve my speed with SIEM queries and packet filtering.

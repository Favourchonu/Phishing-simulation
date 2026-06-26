# Phishing-simulation
End-to-end phishing simulation built using GoPhish, conducted against  my own email account in a controlled environment. Includes full email  header forensics, tracking mechanism analysis, and a client-ready  security assessment report.

## This Project covers
- Building and launching a phishing campaign using GoPhish
- Cloning a legitimate login page for credential harvesting
- Email header analysis: SPF/DKIM/DMARC, Return-Path, X-Mailer
- Identifying tracking pixels and unique recipient URL parameters
- Mapping findings to defensice recommendations

## Tools Used
- GoPhish
- Gmail SMTP
- browser based email header analysis (Gmail "show original")

## Key Findings
Five technical indicators identified in email header forensics:
1.Return-Path mismatch exposing real sending address
2. Display name spoofing via X-Google-Original-From
3. Hidden tracking pixel for open-rate detection
4. X-Mailer identifier exposing GoPhish framework
5. Personalised tracking URL with unique recipient ID

## Report
Full security assessment report (executive summary, technical findings 
with severity ratings, defensive recommendations) available in /report.

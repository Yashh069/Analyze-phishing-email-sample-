# Analyze-phishing-email-sample-
Identify phishing characteristics in a suspicious email sample
Tools Used
Email Client: To access and extract email headers.
MXToolbox Header Analyzer: https://mxtoolbox.com/EmailHeaders.aspx Used to analyze the raw email headers and identify anomalies in SPF, DKIM, DMARC, and source IP.
Sample Phishing Email Details
From: Netflix Alert support@netfliix-billing.com
To: abcd123@gmail.com
Subject: Payment Failure – Account Suspension Alert
Date: Tue, 5 Aug 2025 20:15:00 +0530
Return-Path: support@netfliix-billing.com
SPF/DKIM/DMARC: All failed
IP Address: 45.77.120.3 (Not associated with Netflix)
Key Phishing Indicators
Domain spoofing (e.g., netfliix-billing.com)
Failed SPF, DKIM, and DMARC authentication
Urgent or threatening language
Unrecognized IP address origin
Suspicious message ID and return path
Outcome
Increased awareness of phishing traits and hands-on experience using header analysis tools.

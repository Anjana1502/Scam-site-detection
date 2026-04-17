# Scam Site Detection Tool

A lightweight tool for detecting potential scam, phishing, and fraudulent websites based on URL analysis, threat intelligence, and user reports.

## Overview

This tool analyzes submitted URLs to identify possible security threats such as lottery/prize scams, unsecured sites, and other malicious activities. It combines domain age analysis, real-time threat detection, and community-driven reporting.

## Features

- **URL Analysis** – Enter any website URL for instant risk assessment  
- **Domain Age Check** – Detects recently registered domains (suspicious indicator)  
- **Threat Classification** – Identifies specific scam types (Lottery/Prize Scam, Unsecured Site, etc.)  
- **Confidence Scoring** – Provides a threat level percentage (e.g., 25%, 100%)  
- **User Reporting System** – Submit and view community-reported scam sites  
- **HTTPS Security Warning** – Flags sites using unencrypted HTTP instead of HTTPS  

## Sample Output

### URL Detection
Entered URL: http://win-a-car-now.com
Domain Age: 6 months
Threat Level: 25%


### Security Warning
⚠️ Not secure: Uses HTTP instead of HTTPS!
⚠️ Scam or Phishing Site!

Confidence Score: 100.00%
Site Safety Warning: ❗️ Dangerous
Threat Type: Lottery/Prize Scam

## How It Works

1. User enters a URL (e.g., `http://example.com`)  
2. System checks domain age, SSL status, and known threat databases  
3. Confidence score and threat level are calculated  
4. Results are displayed with clear warnings and classifications  
5. Users can report suspicious sites to the community database  


Output Files
reported_sites.csv – Database of user-submitted scam reports

detection_log.json – Log of all analyzed URLs with timestamps

Disclaimer
This tool provides heuristic and community-based detection. Always exercise caution when visiting unfamiliar websites. Do not enter personal information on sites flagged as dangerous.

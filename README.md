# CrewCert — Marine Crew Certification Tracker

Track crew certifications, expiry dates, and STCW/Domestic compliance against Transport Canada Marine Personnel Regulations (SOR/2007-115).

**Live demo:** https://chilly-cobble-mg6f.here.now/

## Features

- **Rules Engine** — 10+ ranks x 2 voyage classes (Domestic/STCW) with required certificates per position
- **Dual Interfaces** — Coordinator dashboard for fleet-wide compliance + Crew self-service view
- **Expiry Tracking** — Color-coded: Valid, Warning (less than 30d), Expired. Medical cert validity adapts per voyage class (5yr domestic, 2yr STCW)
- **Regulation Watch** — Monitors Transport Canada, ISED, and IMO regulatory sources for changes
- **Certificate Matrix** — Certificate of Competency, Medical, MED (Domestic/STCW streams), First Aid, ROC-MC Radio, Fatigue Management, Tanker, Security
- **Fleet Compliance Dashboard** — Overall percentage, crew with expired certs, missing certificates, urgent gap list
- **CSV Export and Print Reports** — One-click reporting for audits and crewing decisions
- **Fully Client-Side** — Single HTML file, localStorage persistence, zero server dependencies
- **Mobile Responsive** — Works on phones, tablets, and desktops

## Regulatory Basis

- **Transport Canada** — Marine Personnel Regulations (SOR/2007-115)
- **Transport Canada** — Marine Medical Certificate Requirements
- **Transport Canada** — Marine Emergency Duties (MED) Training
- **ISED Canada** — ROC-MC Radio Operator Certificate
- **Canada Shipping Act, 2001** (S.C. 2001, c. 26)
- **IMO** — STCW Convention (Manila Amendments)
- **Transport Canada** — Fatigue Management at Sea

All rules are linked to their source URLs within the app.

## Certification Streams

| Stream | Applicable To | Medical Validity | Key MED |
|--------|--------------|------------------|---------|
| **Domestic** | Great Lakes / inland, 95 percent operations | 5 years | MED Domestic Vessel Safety |
| **STCW** | International / outside Anticosti, SOLAS-class vessels | 2 years | STCW Basic Safety (A1+B2), Survival Craft (B1), Advanced Firefighting (B2+C) |

## Getting Started

1. Open index.html in any browser
2. Sample fleet data loads automatically (6 crew members, full certificate set)
3. Switch between **Coordinator** and **Crew View** in the header
4. Run **Regulation Watch** scan to check for regulatory updates
5. Add your own crew members and certificates

## Project Structure

```
index.html    — Complete application (self-contained)
```

No build step. No npm. No framework. Just open and use.

---

**Created by Rubin Varghese** — June 13, 2026

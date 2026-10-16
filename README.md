# Vulnerability Assessment Report (Portfolio Sample)

A professionally formatted PDF demonstrating how to communicate web security observations in business-friendly language.

## Important disclaimer
This repository is an **illustrative training sample**. No live website was provided and no live scan was performed. Findings are examples, not verified vulnerabilities. Replace the placeholder target and findings with evidence from a website you own or are explicitly authorized to assess before presenting it as a real assessment.

## Tools represented
- Nmap — narrow, authorized host/service inventory
- OWASP ZAP in passive mode — review observed traffic and passive alerts
- Browser DevTools — inspect response headers, cookies, console/network behavior
- Canva — optional redesign / branding of the final report

## Files
- `Vulnerability_Assessment_Report.pdf` — report
- `findings.csv` — editable findings register
- `assets/` — original report graphics

## Safe workflow
1. Obtain written authorization and confirm scope, timing, rate limits, and contact.
2. Use Nmap only against approved hosts/IP ranges.
3. Configure ZAP scope and passive scanning; browse approved pages only.
4. Validate every alert manually and record sanitized evidence.
5. Classify risk based on likelihood and business impact.
6. Apply fixes and retest.

## Publish to GitHub
1. Create a public repository named `Vulnerability-Assessment-Report`.
2. Upload these files or push the folder with Git.
3. Review the PDF and CSV for secrets, cookies, personal data, and internal details before publishing.
4. Keep the disclaimer unless you replace the sample with a real, authorized assessment.

## Example Nmap command
`nmap -sV --top-ports 100 -oN nmap-results.txt TARGET_HOST`

Replace `TARGET_HOST` only with an authorized hostname or IP address. This command is not an instruction to scan arbitrary public systems.

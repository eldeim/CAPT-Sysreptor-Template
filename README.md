# Mobile Hacking Lab SysReptor Template

SysReptor report template for the **CAPT (Certified Android Penetration Tester)** & **CIPT (Certified iOS Penetration Tester)** exam by [Mobile Hacking Lab](https://www.mobilehackinglab.com). Covers Android & iOS attack surface findings classified with OWASP Mobile Top 10, OWASP MASVS and CVSS 3.1. Ready to import (just add your findings).

<img width="1882" height="895" alt="image" src="https://github.com/user-attachments/assets/887cd082-9ecc-4fb1-807a-46692bfce9d4" />

---

## What's included

- Full report structure: cover page, executive summary, scope, methodology, findings table and detailed finding sections
- Fields pre-configured for: title, severity (CVSS 3.1 score + vector), OWASP Mobile Top 10 category, OWASP MASVS control, description, proof of concept, steps to reproduce and remediation
- Vulnerability summary table with severity distribution (Critical / High / Medium / Low)
- MHL branding assets (logo, banner)
- CSS fix for `ffi` ligature rendering bug present in the original template

## How to import

1. Download `MHL-Template.tar.gz` from this repository
2. Open your SysReptor instance
3. Go to **Designs** → **Import**
4. Upload the `.tar.gz` file
5. The design will appear as **"Customization of MHL-Pentest-Template-Report"** (rename it as you like)
6. Create a new project and select this design

## NOTE! - WARNING

This template was exported directly from a completed CAPT & CIPT exam report. It may contain minor typos or placeholder text from the original submission. **The structure, fields, design and all report logic work perfectly** (just review the content sections before using it for your own report).

## Requirements

- Self-hosted [SysReptor](https://github.com/Syslifters/sysreptor) (Community or Professional)
- Tested on SysReptor `2026.25`

---

With love eldeim <3

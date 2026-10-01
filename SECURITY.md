<div align="center">

# 🔐 Security Policy — ScanPro

</div>

---

## Supported Versions

| Version | Supported |
|---|:---:|
| Latest (Google Play) | ✅ Active |
| Previous versions | ❌ No support |

Always use the latest version of ScanPro available on Google Play to
ensure you have the most recent security fixes and improvements.

---

## Reporting a Vulnerability

If you discover a security vulnerability in ScanPro, please report it
**responsibly** and **privately:**

> ⚠️ **Do not open a public GitHub issue for security vulnerabilities.**
> This could expose users before a fix is available.

### How to Report

1. Send an email to **[support@rdcapps.com](mailto:support@rdcapps.com)**
   with the subject line: `[SECURITY] ScanPro Vulnerability Report`
2. Include in your report:
   - A clear description of the vulnerability
   - Steps to reproduce the issue
   - Potential impact assessment
   - Your suggested fix (if any)
   - Your Android version and ScanPro version

### Response Timeline

| Step | Timeline |
|---|---|
| Acknowledgement | Within 72 hours |
| Assessment | Within 7 days |
| Fix release | Depends on severity |

We appreciate responsible disclosure and will credit researchers who help
keep ScanPro secure (with their permission).

---

## Scope

| In Scope ✅ | Out of Scope ❌ |
|---|---|
| ScanPro Android app | Google advertising services |
| In-app purchase integration | External website/file hosts |
| QR/barcode parsing and exports | Google Play / RevenueCat services |
| Local storage and consent integration | Physical device attacks |

---

## Known Security Practices

- ✅ Advertising and purchase SDKs use encrypted network transport
- ℹ️ QR content, including Wi-Fi details, can be stored in local history; clear sensitive entries when appropriate
- ✅ Google AdMob advertising with UMP privacy choices; Supporter disables AdMob initialization
- ✅ All preferences stored locally using Android SharedPreferences
- ✅ Purchase verification handled by RevenueCat (server-side)

---

*Thank you for helping keep ScanPro and its users safe. 🌤️*

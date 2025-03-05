# Test report

## Summary

This is test report about two peneration tests. First version of the app have some alerts, but second did not have anything alerts. Thought there is a mistake made by me, but after running app different ways and using different peneration settings, I am sure there is no alerts found in second version.

Noting that docker was broken before doing second test peneration and it had to be fixed and had to made a clear reinstallion for it. Error was that docker.service and docker.socket could not run properly. I did made test peneration to first version of the app to see if I get the same results like in the first report and yes got same.

## Findings and Categorization

First Test Results:
| Risk Level | Subject | Short Description |
| :---         |     :---:      |     :---:      |
| Medium | Content Security Policy (CSP) Wildcard Directive | Refers to the use of wildcard values just as: (*) in a CSP configuration, which can weaken security by allowing broader, potentially unsafe resource loading |
| Medium | Content Security Policy (CSP) Header Not Set | No header was used to prevent cross-site scripting (XSS), data injection attacks, and other malicious exploits by restricting the sources from which content (scripts, styles, images, etc.) can be loaded. |
| Medium | Missing Anti-clickjacking Header | No anti-clickjacking protection header was used, leaving application vulnerable to clickjacking attacks. That can lead users into malicious sites. |
| Low | Application Error Disclosure | Means that application is exposing internal error messages to users like: Server paths. |
| Low | X-Content-Type-Options Header Missing |  |
| Informational | User Controllable HTML Element Attribute (Potential XSS) |  |

Second Test Results: (Non was found)
| Risk Level | Subject | Short Description |
| :---         |     :---:      |     :---:      |
|  |  |  |

## Appendices (Liitteet)

- ZAP report: \Checkmarx ZAP report\ [Report.md](https://github.com/JuhaniPaananen/Juhani-s-Logbook/blob/main/Checkmarx%20ZAP%20report/Report.md)
- ZAP report: \Checkmarx ZAP report\ [Report2.md](https://github.com/JuhaniPaananen/Juhani-s-Logbook/blob/main/Checkmarx%20ZAP%20report/Report2.md)

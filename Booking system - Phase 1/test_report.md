# Test report

## Summary

This is test report about two peneration tests. First version of the app have some alerts, but second did not have anything alerts. Thought there is a mistake made by me, but after running app different ways and using different peneration settings, I am sure there is no alerts found in second version.

Noting that docker was broken before doing second test peneration and it had to be fixed and had to made a clear reinstallion for it. Error was that docker.service and docker.socket could not run properly. I did made test peneration to first version of the app to see if I get the same results like in the first report and yes got same.

## Findings and Categorization

First Test Results:
| Risk Level | Subject | Short Description |
| :---         |     :---:      |     :---:      |
| <span style="color:red">Medium</span> | Content Security Policy (CSP) Wildcard Directive |  |
| Medium | Content Security Policy (CSP) Header Not Set |  |
| Medium | Missing Anti-clickjacking Header |  |
| Low | Application Error Disclosure |  |
| Low | X-Content-Type-Options Header Missing |  |
| Informational | User Controllable HTML Element Attribute (Potential XSS) |  |

Second Test Results:
| Risk Level | Subject | Short Description |
| :---         |     :---:      |     :---:      |
|  |  |  |

## Appendices (Liitteet)

- ZAP report: Report.md
- ZAP report: Report2.md

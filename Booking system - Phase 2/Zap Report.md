<div>

# ZAP by Checkmarx Scanning Report

Generated with [![The ZAP
logo](2025-03-13-ZAP-Report-/zap32x32.png){.zap-logo}ZAP](https://zaproxy.org)
on Thu 13 Mar 2025, at 22:40:43

ZAP Version: 2.16.0

ZAP by [Checkmarx](https://checkmarx.com/)

</div>

::: {role="main"}
::: {#contents .section .contents}
## Contents

1.  [About this report](#about-this-report)
    1.  [Report parameters](#report-parameters)
2.  [Summaries](#summaries)
    1.  [Alert counts by risk and confidence](#risk-confidence-counts)
    2.  [Alert counts by site and risk](#site-risk-counts)
    3.  [Alert counts by alert type](#alert-type-counts)
3.  [Alerts](#alerts)
    1.  [Risk=[Medium]{.risk-level}, Confidence=[Low]{.confidence-level}
        (1)](#alerts--risk-2-confidence-1)
    2.  [Risk=[Informational]{.risk-level},
        Confidence=[High]{.confidence-level}
        (1)](#alerts--risk-0-confidence-3)
4.  [Appendix](#appendix)
    1.  [Alert types](#alert-types)
:::

::: {#about-this-report .section .about-this-report}
## About this report

::: {#report-parameters .section}
### Report parameters

::: report-parameters--container
#### Contexts

No contexts were selected, so all contexts were included by default.

#### Sites

The following sites were included:

-   [http://localhost:8000]{.site}

(If no sites were selected, all sites were included by default.)

An included site must also be within one of the included contexts for
its data to be included in the report.

#### Risk levels

Included: [[High]{.risk-level}, [Medium]{.risk-level},
[Low]{.risk-level}, [Informational]{.risk-level}]{.included-risk-codes}

Excluded: None

#### Confidence levels

Included: [[User Confirmed]{.confidence-level},
[High]{.confidence-level}, [Medium]{.confidence-level},
[Low]{.confidence-level}]{.included-confidence-codes}

Excluded: [ [User Confirmed]{.confidence-level},
[High]{.confidence-level}, [Medium]{.confidence-level},
[Low]{.confidence-level}, [False
Positive]{.confidence-level}]{.included-confidence-codes}
:::
:::
:::

::: section
:::

::: {#summaries .section .summaries}
## Summaries

::: {#risk-confidence-counts .section}
### Alert counts by risk and confidence

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                         Confidence                                                                                                                                                            
  ------ --------------- ---------------------------------------- ----------------------------------------- ---------------------------------------- ----------------------------------------- -----------------------------------------
                         User Confirmed                           High                                      Medium                                   Low                                       Total

  Risk   High            0\                                       0\                                        0\                                       0\                                        0\
                         [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}

         Medium          0\                                       0\                                        0\                                       1\                                        1\
                         [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}   [(50.0%)]{.additional-info-percentages}   [(50.0%)]{.additional-info-percentages}

         Low             0\                                       0\                                        0\                                       0\                                        0\
                         [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}

         Informational   0\                                       1\                                        0\                                       0\                                        1\
                         [(0.0%)]{.additional-info-percentages}   [(50.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(50.0%)]{.additional-info-percentages}

         Total           0\                                       1\                                        0\                                       1\                                        2\
                         [(0.0%)]{.additional-info-percentages}   [(50.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}   [(50.0%)]{.additional-info-percentages}   [(100%)]{.additional-info-percentages}
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  : This table shows the number of alerts for each level of risk and
  confidence included in the report.\
  (The percentages in brackets represent the count as a percentage of
  the total number of alerts included in the report, rounded to one
  decimal place.)
:::

::: {#site-risk-counts .section}
### Alert counts by site and risk

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                                 Risk                                                                                                                  
  ------ ----------------------- -------------------------------------- ---------------------------------------- ------------------------------------- -----------------------------------------------
                                 High\                                  Medium\                                  Low\                                  Informational\
                                 [(=                                    [(\>=                                    [(\>=                                 [(\>=
                                 High)]{.additional-info-percentages}   Medium)]{.additional-info-percentages}   Low)]{.additional-info-percentages}   Informational)]{.additional-info-percentages}

  Site   http://localhost:8000   0\                                     1\                                       0\                                    1\
                                 [(0)]{.additional-info-percentages}    [(1)]{.additional-info-percentages}      [(1)]{.additional-info-percentages}   [(2)]{.additional-info-percentages}
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  : This table shows, for each site for which one or more alerts were
  raised, the number of alerts raised at each risk level.\
  Alerts with a confidence level of \"False Positive\" have been
  excluded from these counts.\
  (The numbers in brackets are the number of alerts raised for the site
  at or above that risk level.)
:::

::: {#alert-type-counts .section}
### Alert counts by alert type

  ----------------------------------------------------------------------------------------------
  Alert type                   Risk                    Count
  ---------------------------- ----------------------- -----------------------------------------
  [Absence of Anti-CSRF        Medium                  1\
  Tokens](#alert-type-0)                               [(50.0%)]{.additional-info-percentages}

  [Authentication Request      Informational           1\
  Identified](#alert-type-1)                           [(50.0%)]{.additional-info-percentages}

  Total                                                2
  ----------------------------------------------------------------------------------------------

  : This table shows the number of alerts of each alert type, together
  with the alert type\'s risk level.\
  (The percentages in brackets represent each count as a percentage,
  rounded to one decimal place, of the total number of alerts included
  in this report.)
:::
:::

::: {#alerts .section .alerts}
## Alerts

1.  ::: {#alerts--risk-2-confidence-1}
    ### Risk=[Medium]{.risk-level}, Confidence=[Low]{.confidence-level} (1)

    1.  #### [http://localhost:8000]{.site} (1)

        1.  ##### [Absence of Anti-CSRF Tokens](#alert-type-0) (1)

            1.  [GET http://localhost:8000/login]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        | -   [OWASP_                       |
                |                                   | 2021_A01](https://owasp.org/Top10 |
                |                                   | /A01_2021-Broken_Access_Control/) |
                |                                   | -   [WSTG-v42-SESS-05](htt        |
                |                                   | ps://owasp.org/www-project-web-se |
                |                                   | curity-testing-guide/v42/4-Web_Ap |
                |                                   | plication_Security_Testing/06-Ses |
                |                                   | sion_Management_Testing/05-Testin |
                |                                   | g_for_Cross_Site_Request_Forgery) |
                |                                   | -   [OWASP_2017_A05](https://owas |
                |                                   | p.org/www-project-top-ten/2017/A5 |
                |                                   | _2017-Broken_Access_Control.html) |
                |                                   | -   [CWE-352](https://cwe.mit     |
                |                                   | re.org/data/definitions/352.html) |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | No Anti-CSRF tokens were found in |
                |                                   | a HTML submission form.           |
                |                                   |                                   |
                |                                   | A cross-site request forgery is   |
                |                                   | an attack that involves forcing a |
                |                                   | victim to send an HTTP request to |
                |                                   | a target destination without      |
                |                                   | their knowledge or intent in      |
                |                                   | order to perform an action as the |
                |                                   | victim. The underlying cause is   |
                |                                   | application functionality using   |
                |                                   | predictable URL/form actions in a |
                |                                   | repeatable way. The nature of the |
                |                                   | attack is that CSRF exploits the  |
                |                                   | trust that a web site has for a   |
                |                                   | user. By contrast, cross-site     |
                |                                   | scripting (XSS) exploits the      |
                |                                   | trust that a user has for a web   |
                |                                   | site. Like XSS, CSRF attacks are  |
                |                                   | not necessarily cross-site, but   |
                |                                   | they can be. Cross-site request   |
                |                                   | forgery is also known as CSRF,    |
                |                                   | XSRF, one-click attack, session   |
                |                                   | riding, confused deputy, and sea  |
                |                                   | surf.                             |
                |                                   |                                   |
                |                                   | CSRF attacks are effective in a   |
                |                                   | number of situations, including:  |
                |                                   |                                   |
                |                                   | \* The victim has an active       |
                |                                   | session on the target site.       |
                |                                   |                                   |
                |                                   | \* The victim is authenticated    |
                |                                   | via HTTP auth on the target site. |
                |                                   |                                   |
                |                                   | \* The victim is on the same      |
                |                                   | local network as the target site. |
                |                                   |                                   |
                |                                   | CSRF has primarily been used to   |
                |                                   | perform an action against a       |
                |                                   | target site using the victim\'s   |
                |                                   | privileges, but recent techniques |
                |                                   | have been discovered to disclose  |
                |                                   | information by gaining access to  |
                |                                   | the response. The risk of         |
                |                                   | information disclosure is         |
                |                                   | dramatically increased when the   |
                |                                   | target site is vulnerable to XSS, |
                |                                   | because XSS can be used as a      |
                |                                   | platform for CSRF, allowing the   |
                |                                   | attack to operate within the      |
                |                                   | bounds of the same-origin policy. |
                +-----------------------------------+-----------------------------------+
                | Other info                        | No known Anti-CSRF token          |
                |                                   | \[anticsrf, CSRFToken,            |
                |                                   | \_\_RequestVerificationToken,     |
                |                                   | csrfmiddlewaretoken,              |
                |                                   | authenticity_token,               |
                |                                   | OWASP_CSRFTOKEN, anoncsrf,        |
                |                                   | csrf_token, \_csrf, \_csrfSecret, |
                |                                   | \_\_csrf_magic, CSRF, \_token,    |
                |                                   | \_csrf_token\] was found in the   |
                |                                   | following HTML form: \[Form 1:    |
                |                                   | \"password\" \"username\" \].     |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (234 bytes)                       |
                |                                   |     GET htt                       |
                |                                   | p://localhost:8000/login HTTP/1.1 |
                |                                   |     host: localhost:8000          |
                |                                   |     user-agent: Mozilla/5.0       |
                |                                   | (Windows NT 10.0; Win64; x64) App |
                |                                   | leWebKit/537.36 (KHTML, like Geck |
                |                                   | o) Chrome/131.0.0.0 Safari/537.36 |
                |                                   |     pragma: no-cache              |
                |                                   |     cache-control: no-cache       |
                |                                   |                                   |
                |                                   | Request body (0 bytes)            |
                +-----------------------------------+-----------------------------------+
                | Response                          | Status line and header section    |
                |                                   | (324 bytes)                       |
                |                                   |     HTTP/1.1 200 OK               |
                |                                   |     content-type: text/html       |
                |                                   |     content-s                     |
                |                                   | ecurity-policy: default-src 'self |
                |                                   | '; script-src 'self'; style-src ' |
                |                                   | self'; img-src 'self'; frame-ance |
                |                                   | stors 'none'; form-action 'self'; |
                |                                   |     x-frame-options: DENY         |
                |                                   |                                   |
                |                                   |   x-content-type-options: nosniff |
                |                                   |     vary: Accept-Encoding         |
                |                                   |     content-length: 765           |
                |                                   |     da                            |
                |                                   | te: Thu, 13 Mar 2025 20:39:14 GMT |
                |                                   |                                   |
                |                                   | Response body (765 bytes)         |
                |                                   |     <!DOCTYPE html>               |
                |                                   |     <html lang="en">              |
                |                                   |     <head>                        |
                |                                   |         <meta charset="UTF-8">    |
                |                                   |         <met                      |
                |                                   | a name="viewport" content="width= |
                |                                   | device-width, initial-scale=1.0"> |
                |                                   |         <title>User Login</title> |
                |                                   |         <link rel="style          |
                |                                   | sheet" href="/static/styles.css"> |
                |                                   |     </head>                       |
                |                                   |     <body>                        |
                |                                   |         <div class="container">   |
                |                                   |             <h1>Login</h1>        |
                |                                   |             <fo                   |
                |                                   | rm action="/login" method="POST"> |
                |                                   |                 <la               |
                |                                   | bel for="username">Email:</label> |
                |                                   |                                   |
                |                                   |          <input type="email" id=" |
                |                                   | username" name="username" placeho |
                |                                   | lder="Enter your email" required> |
                |                                   |                                   |
                |                                   |                 <label            |
                |                                   |  for="password">Password:</label> |
                |                                   |                                   |
                |                                   |    <input type="password" id="pas |
                |                                   | sword" name="password" placeholde |
                |                                   | r="Enter your password" required> |
                |                                   |                                   |
                |                                   |                 <bu               |
                |                                   | tton type="submit">Login</button> |
                |                                   |             </form>               |
                |                                   |         </div>                    |
                |                                   |     </body>                       |
                |                                   |     </html>                       |
                +-----------------------------------+-----------------------------------+
                | Evidence                          |     <fo                           |
                |                                   | rm action="/login" method="POST"> |
                +-----------------------------------+-----------------------------------+
                | Solution                          | Phase: Architecture and Design    |
                |                                   |                                   |
                |                                   | Use a vetted library or framework |
                |                                   | that does not allow this weakness |
                |                                   | to occur or provides constructs   |
                |                                   | that make this weakness easier to |
                |                                   | avoid.                            |
                |                                   |                                   |
                |                                   | For example, use anti-CSRF        |
                |                                   | packages such as the OWASP        |
                |                                   | CSRFGuard.                        |
                |                                   |                                   |
                |                                   | Phase: Implementation             |
                |                                   |                                   |
                |                                   | Ensure that your application is   |
                |                                   | free of cross-site scripting      |
                |                                   | issues, because most CSRF         |
                |                                   | defenses can be bypassed using    |
                |                                   | attacker-controlled script.       |
                |                                   |                                   |
                |                                   | Phase: Architecture and Design    |
                |                                   |                                   |
                |                                   | Generate a unique nonce for each  |
                |                                   | form, place the nonce into the    |
                |                                   | form, and verify the nonce upon   |
                |                                   | receipt of the form. Be sure that |
                |                                   | the nonce is not predictable      |
                |                                   | (CWE-330).                        |
                |                                   |                                   |
                |                                   | Note that this can be bypassed    |
                |                                   | using XSS.                        |
                |                                   |                                   |
                |                                   | Identify especially dangerous     |
                |                                   | operations. When the user         |
                |                                   | performs a dangerous operation,   |
                |                                   | send a separate confirmation      |
                |                                   | request to ensure that the user   |
                |                                   | intended to perform that          |
                |                                   | operation.                        |
                |                                   |                                   |
                |                                   | Note that this can be bypassed    |
                |                                   | using XSS.                        |
                |                                   |                                   |
                |                                   | Use the ESAPI Session Management  |
                |                                   | control.                          |
                |                                   |                                   |
                |                                   | This control includes a component |
                |                                   | for CSRF.                         |
                |                                   |                                   |
                |                                   | Do not use the GET method for any |
                |                                   | request that triggers a state     |
                |                                   | change.                           |
                |                                   |                                   |
                |                                   | Phase: Implementation             |
                |                                   |                                   |
                |                                   | Check the HTTP Referer header to  |
                |                                   | see if the request originated     |
                |                                   | from an expected page. This could |
                |                                   | break legitimate functionality,   |
                |                                   | because users or proxies may have |
                |                                   | disabled sending the Referer for  |
                |                                   | privacy reasons.                  |
                +-----------------------------------+-----------------------------------+
    :::

2.  ::: {#alerts--risk-0-confidence-3}
    ### Risk=[Informational]{.risk-level}, Confidence=[High]{.confidence-level} (1)

    1.  #### [http://localhost:8000]{.site} (1)

        1.  ##### [Authentication Request Identified](#alert-type-1) (1)

            1.  [POST
                http://localhost:8000/login]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        |                                   |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | The given request has been        |
                |                                   | identified as an authentication   |
                |                                   | request. The \'Other Info\' field |
                |                                   | contains a set of key=value lines |
                |                                   | which identify any relevant       |
                |                                   | fields. If the request is in a    |
                |                                   | context which has an              |
                |                                   | Authentication Method set to      |
                |                                   | \"Auto-Detect\" then this rule    |
                |                                   | will change the authentication to |
                |                                   | match the request identified.     |
                +-----------------------------------+-----------------------------------+
                | Other info                        | userParam=username                |
                |                                   |                                   |
                |                                   | userValue=foo-bar@example.com     |
                |                                   |                                   |
                |                                   | passwordParam=password            |
                |                                   |                                   |
                |                                   | re                                |
                |                                   | ferer=http://localhost:8000/login |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (342 bytes)                       |
                |                                   |     POST htt                      |
                |                                   | p://localhost:8000/login HTTP/1.1 |
                |                                   |     host: localhost:8000          |
                |                                   |     user-agent: Mozilla/5.0       |
                |                                   | (Windows NT 10.0; Win64; x64) App |
                |                                   | leWebKit/537.36 (KHTML, like Geck |
                |                                   | o) Chrome/131.0.0.0 Safari/537.36 |
                |                                   |     pragma: no-cache              |
                |                                   |     cache-control: no-cache       |
                |                                   |     content-type:                 |
                |                                   | application/x-www-form-urlencoded |
                |                                   |     ref                           |
                |                                   | erer: http://localhost:8000/login |
                |                                   |     content-length: 43            |
                |                                   |                                   |
                |                                   | Request body (43 bytes)           |
                |                                   |     username=f                    |
                |                                   | oo-bar%40example.com&password=ZAP |
                +-----------------------------------+-----------------------------------+
                | Response                          | Status line and header section    |
                |                                   | (347 bytes)                       |
                |                                   |     HTTP/1.1 400 Bad Request      |
                |                                   |     conte                         |
                |                                   | nt-type: text/plain;charset=UTF-8 |
                |                                   |     content-s                     |
                |                                   | ecurity-policy: default-src 'self |
                |                                   | '; script-src 'self'; style-src ' |
                |                                   | self'; img-src 'self'; frame-ance |
                |                                   | stors 'none'; form-action 'self'; |
                |                                   |     x-frame-options: DENY         |
                |                                   |                                   |
                |                                   |   x-content-type-options: nosniff |
                |                                   |     vary: Accept-Encoding         |
                |                                   |     content-length: 25            |
                |                                   |     da                            |
                |                                   | te: Thu, 13 Mar 2025 20:39:14 GMT |
                |                                   |                                   |
                |                                   | Response body (25 bytes)          |
                |                                   |     Invalid email or password     |
                +-----------------------------------+-----------------------------------+
                | Parameter                         |     username                      |
                +-----------------------------------+-----------------------------------+
                | Evidence                          |     password                      |
                +-----------------------------------+-----------------------------------+
                | Solution                          | This is an informational alert    |
                |                                   | rather than a vulnerability and   |
                |                                   | so there is nothing to fix.       |
                +-----------------------------------+-----------------------------------+
    :::
:::

::: {#appendix .section .appendix}
## Appendix

::: {#alert-types .section .alert-types}
### Alert types

This section contains additional information on the types of alerts in
the report.

1.  ::: {#alert-type-0}
    #### Absence of Anti-CSRF Tokens

    +-----------------------------------+-----------------------------------+
    | Source                            | raised by a passive scanner       |
    |                                   | ([Absence of Anti-CSRF            |
    |                                   | Tokens](https://www               |
    |                                   | .zaproxy.org/docs/alerts/10202/)) |
    +-----------------------------------+-----------------------------------+
    | CWE ID                            | [352](https://cwe.mit             |
    |                                   | re.org/data/definitions/352.html) |
    +-----------------------------------+-----------------------------------+
    | WASC ID                           | 9                                 |
    +-----------------------------------+-----------------------------------+
    | Reference                         | 1.  <htt                          |
    |                                   | ps://cheatsheetseries.owasp.org/c |
    |                                   | heatsheets/Cross-Site_Request_For |
    |                                   | gery_Prevention_Cheat_Sheet.html> |
    |                                   | 2.  <https://cwe.mit              |
    |                                   | re.org/data/definitions/352.html> |
    +-----------------------------------+-----------------------------------+
    :::

2.  ::: {#alert-type-1}
    #### Authentication Request Identified

    +-----------------------------------+-----------------------------------+
    | Source                            | raised by a passive scanner       |
    |                                   | ([Authentication Request          |
    |                                   | Identified](https://www           |
    |                                   | .zaproxy.org/docs/alerts/10111/)) |
    +-----------------------------------+-----------------------------------+
    | Reference                         | 1.  <https://www.z                |
    |                                   | aproxy.org/docs/desktop/addons/au |
    |                                   | thentication-helper/auth-req-id/> |
    +-----------------------------------+-----------------------------------+
    :::
:::
:::
:::

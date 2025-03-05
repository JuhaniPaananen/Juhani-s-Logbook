<div>

# ZAP by Checkmarx Scanning Report

Generated with [![The ZAP
logo](2025-02-19-ZAP-Report-/zap32x32.png){.zap-logo}ZAP](https://zaproxy.org)
on Wed 19 Feb 2025, at 13:05:38

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
    1.  [Risk=[Medium]{.risk-level},
        Confidence=[High]{.confidence-level}
        (2)](#alerts--risk-2-confidence-3)
    2.  [Risk=[Medium]{.risk-level},
        Confidence=[Medium]{.confidence-level}
        (1)](#alerts--risk-2-confidence-2)
    3.  [Risk=[Low]{.risk-level}, Confidence=[Medium]{.confidence-level}
        (2)](#alerts--risk-1-confidence-2)
    4.  [Risk=[Informational]{.risk-level},
        Confidence=[Low]{.confidence-level}
        (1)](#alerts--risk-0-confidence-1)
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

-   [http://127.0.0.1:40297]{.site}
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

  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                         Confidence                                                                                                                                                             
  ------ --------------- ---------------------------------------- ----------------------------------------- ----------------------------------------- ----------------------------------------- -----------------------------------------
                         User Confirmed                           High                                      Medium                                    Low                                       Total

  Risk   High            0\                                       0\                                        0\                                        0\                                        0\
                         [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}

         Medium          0\                                       2\                                        1\                                        0\                                        3\
                         [(0.0%)]{.additional-info-percentages}   [(33.3%)]{.additional-info-percentages}   [(16.7%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(50.0%)]{.additional-info-percentages}

         Low             0\                                       0\                                        2\                                        0\                                        2\
                         [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(33.3%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(33.3%)]{.additional-info-percentages}

         Informational   0\                                       0\                                        0\                                        1\                                        1\
                         [(0.0%)]{.additional-info-percentages}   [(0.0%)]{.additional-info-percentages}    [(0.0%)]{.additional-info-percentages}    [(16.7%)]{.additional-info-percentages}   [(16.7%)]{.additional-info-percentages}

         Total           0\                                       2\                                        3\                                        1\                                        6\
                         [(0.0%)]{.additional-info-percentages}   [(33.3%)]{.additional-info-percentages}   [(50.0%)]{.additional-info-percentages}   [(16.7%)]{.additional-info-percentages}   [(100%)]{.additional-info-percentages}
  ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  : This table shows the number of alerts for each level of risk and
  confidence included in the report.\
  (The percentages in brackets represent the count as a percentage of
  the total number of alerts included in the report, rounded to one
  decimal place.)
:::

::: {#site-risk-counts .section}
### Alert counts by site and risk

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
                                  Risk                                                                                                                  
  ------ ------------------------ -------------------------------------- ---------------------------------------- ------------------------------------- -----------------------------------------------
                                  High\                                  Medium\                                  Low\                                  Informational\
                                  [(=                                    [(\>=                                    [(\>=                                 [(\>=
                                  High)]{.additional-info-percentages}   Medium)]{.additional-info-percentages}   Low)]{.additional-info-percentages}   Informational)]{.additional-info-percentages}

  Site   http://127.0.0.1:40297   0\                                     1\                                       0\                                    1\
                                  [(0)]{.additional-info-percentages}    [(1)]{.additional-info-percentages}      [(1)]{.additional-info-percentages}   [(2)]{.additional-info-percentages}

         http://localhost:8000    0\                                     2\                                       2\                                    0\
                                  [(0)]{.additional-info-percentages}    [(2)]{.additional-info-percentages}      [(4)]{.additional-info-percentages}   [(4)]{.additional-info-percentages}
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

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
  [CSP: Wildcard               Medium                  5\
  Directive](#alert-type-0)                            [(83.3%)]{.additional-info-percentages}

  [Content Security Policy     Medium                  1\
  (CSP) Header Not                                     [(16.7%)]{.additional-info-percentages}
  Set](#alert-type-1)                                  

  [Missing Anti-clickjacking   Medium                  1\
  Header](#alert-type-2)                               [(16.7%)]{.additional-info-percentages}

  [Application Error           Low                     1\
  Disclosure](#alert-type-3)                           [(16.7%)]{.additional-info-percentages}

  [X-Content-Type-Options      Low                     2\
  Header                                               [(33.3%)]{.additional-info-percentages}
  Missing](#alert-type-4)                              

  [User Controllable HTML      Informational           1\
  Element Attribute (Potential                         [(16.7%)]{.additional-info-percentages}
  XSS)](#alert-type-5)                                 

  Total                                                6
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

1.  ::: {#alerts--risk-2-confidence-3}
    ### Risk=[Medium]{.risk-level}, Confidence=[High]{.confidence-level} (2)

    1.  #### [http://127.0.0.1:40297]{.site} (1)

        1.  ##### [CSP: Wildcard Directive](#alert-type-0) (1)

            1.  [GET http://127.0.0.1:40297/]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        | -   [CWE-693](https://cwe.mit     |
                |                                   | re.org/data/definitions/693.html) |
                |                                   | -   [OWASP_2021                   |
                |                                   | _A05](https://owasp.org/Top10/A05 |
                |                                   | _2021-Security_Misconfiguration/) |
                |                                   | -                                 |
                |                                   | [OWASP_2017_A06](https://owasp.or |
                |                                   | g/www-project-top-ten/2017/A6_201 |
                |                                   | 7-Security_Misconfiguration.html) |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | Content Security Policy (CSP) is  |
                |                                   | an added layer of security that   |
                |                                   | helps to detect and mitigate      |
                |                                   | certain types of attacks.         |
                |                                   | Including (but not limited to)    |
                |                                   | Cross Site Scripting (XSS), and   |
                |                                   | data injection attacks. These     |
                |                                   | attacks are used for everything   |
                |                                   | from data theft to site           |
                |                                   | defacement or distribution of     |
                |                                   | malware. CSP provides a set of    |
                |                                   | standard HTTP headers that allow  |
                |                                   | website owners to declare         |
                |                                   | approved sources of content that  |
                |                                   | browsers should be allowed to     |
                |                                   | load on that page --- covered     |
                |                                   | types are JavaScript, CSS, HTML   |
                |                                   | frames, fonts, images and         |
                |                                   | embeddable objects such as Java   |
                |                                   | applets, ActiveX, audio and video |
                |                                   | files.                            |
                +-----------------------------------+-----------------------------------+
                | Other info                        | The following directives either   |
                |                                   | allow wildcard sources (or        |
                |                                   | ancestors), are not defined, or   |
                |                                   | are overly broadly defined:       |
                |                                   |                                   |
                |                                   | frame-ancestors, form-action      |
                |                                   |                                   |
                |                                   | The directive(s):                 |
                |                                   | frame-ancestors, form-action are  |
                |                                   | among the directives that do not  |
                |                                   | fallback to default-src,          |
                |                                   | missing/excluding them is the     |
                |                                   | same as allowing anything.        |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (471 bytes)                       |
                |                                   |     GET                           |
                |                                   |  http://127.0.0.1:40297/ HTTP/1.1 |
                |                                   |     host: 127.0.0.1:40297         |
                |                                   |     User-Agent: Mozi              |
                |                                   | lla/5.0 (X11; Linux x86_64; rv:12 |
                |                                   | 8.0) Gecko/20100101 Firefox/128.0 |
                |                                   |     Accept: text/html,            |
                |                                   | application/xhtml+xml,application |
                |                                   | /xml;q=0.9,image/avif,image/webp, |
                |                                   | image/png,image/svg+xml,*/*;q=0.8 |
                |                                   |                                   |
                |                                   |   Accept-Language: en-US,en;q=0.5 |
                |                                   |     Connection: keep-alive        |
                |                                   |     Upgrade-Insecure-Requests: 1  |
                |                                   |     Sec-Fetch-Dest: document      |
                |                                   |     Sec-Fetch-Mode: navigate      |
                |                                   |     Sec-Fetch-Site: cross-site    |
                |                                   |     Sec-Fetch-User: ?1            |
                |                                   |     Priority: u=0, i              |
                |                                   |                                   |
                |                                   | Request body (0 bytes)            |
                +-----------------------------------+-----------------------------------+
                | Response                          | Status line and header section    |
                |                                   | (520 bytes)                       |
                |                                   |     HTTP/1.1 200 OK               |
                |                                   |     Pragma: no-cache              |
                |                                   |     Cache-Control: no             |
                |                                   | -cache, no-store, must-revalidate |
                |                                   |                                   |
                |                                   |   Content-Security-Policy: defaul |
                |                                   | t-src 'none'; script-src 'self';  |
                |                                   | connect-src 'self'; child-src 'se |
                |                                   | lf'; img-src 'self' data:; font-s |
                |                                   | rc 'self' data:; style-src 'self' |
                |                                   |     Access-Contro                 |
                |                                   | l-Allow-Methods: GET,POST,OPTIONS |
                |                                   |     Access-                       |
                |                                   | Control-Allow-Headers: ZAP-Header |
                |                                   |     X-Frame-Options: DENY         |
                |                                   |                                   |
                |                                   |   X-XSS-Protection: 1; mode=block |
                |                                   |                                   |
                |                                   |   X-Content-Type-Options: nosniff |
                |                                   |     X-Cla                         |
                |                                   | cks-Overhead: GNU Terry Pratchett |
                |                                   |     Content-Length: 1420          |
                |                                   |     Content-Type: text/html       |
                |                                   |                                   |
                |                                   | Response body (1420 bytes)        |
                |                                   |     <!DOCTYPE html>               |
                |                                   |     <html lang="en">              |
                |                                   |     <head>                        |
                |                                   |                                   |
                |                                   | <title>Welcome to the HUD</title> |
                |                                   |                                   |
                |                                   |      <link href="tutorial.css" re |
                |                                   | l="stylesheet" type="text/css" /> |
                |                                   |         <sc                       |
                |                                   | ript src="Tutorial.js"></script>  |
                |                                   |     </head>                       |
                |                                   |     <body>                        |
                |                                   |     <div class="roundContainer">  |
                |                                   |                                   |
                |                                   |       <h1>Welcome to the HUD</H1> |
                |                                   |         The HUD is a completely   |
                |                                   | new way to interact with ZAP.<br> |
                |                                   |         It overlays security i    |
                |                                   | nformation on top of the applicat |
                |                                   | ion you are testing and allows yo |
                |                                   | u to access key ZAP features.<br> |
                |                                   |         It is easier for p        |
                |                                   | eople new to security to understa |
                |                                   | nd but it also allows experienced |
                |                                   |  penetration testers to focus on  |
                |                                   | the application they are testing. |
                |                                   |         <p>                       |
                |                                   |                                   |
                |                                   |        By default, the HUD is inj |
                |                                   | ected into all of the HTML pages  |
                |                                   | proxied through the ZAP desktop.  |
                |                                   |         You can turn i            |
                |                                   | t on and off easily using the <im |
                |                                   | g src="radar.png" alt="[green rad |
                |                                   | ar]"> button on the ZAP toolbar.  |
                |                                   |         It i                      |
                |                                   | s not injected by default into pa |
                |                                   | ges proxied through ZAP when it i |
                |                                   | s running in headless/daemon mode |
                |                                   |  as that could break unit tests.  |
                |                                   |         This behaviour ca         |
                |                                   | n be changed via the HUD options. |
                |                                   |         <p>                       |
                |                                   |         This tutorial will t      |
                |                                   | ake you through the HUD features  |
                |                                   | and explain how you can use them. |
                |                                   |         <p>                       |
                |                                   |                                   |
                |                                   |                                   |
                |                                   |         <!-- TASK -->             |
                |                                   |         <div class="buttonsDiv">  |
                |                                   |     <div class="indexDiv">        |
                |                                   |     <a href="Index"><bu           |
                |                                   | tton id="index-button">Index <img |
                |                                   |  src="exclamation-red.png" title= |
                |                                   | "New content added"></button></a> |
                |                                   |     </div>                        |
                |                                   |     <div class="prevNextDiv">     |
                |                                   |     <a href=                      |
                |                                   | "Warning"><button id="next-button |
                |                                   | ">Next:&nbsp;Warning</button></a> |
                |                                   |     </div>                        |
                |                                   |     </div>                        |
                |                                   |                                   |
                |                                   |                                   |
                |                                   |     </div>                        |
                |                                   |                                   |
                |                                   |     </body>                       |
                |                                   |     </html>                       |
                +-----------------------------------+-----------------------------------+
                | Parameter                         |     Content-Security-Policy       |
                +-----------------------------------+-----------------------------------+
                | Evidence                          |     defaul                        |
                |                                   | t-src 'none'; script-src 'self';  |
                |                                   | connect-src 'self'; child-src 'se |
                |                                   | lf'; img-src 'self' data:; font-s |
                |                                   | rc 'self' data:; style-src 'self' |
                +-----------------------------------+-----------------------------------+
                | Solution                          | Ensure that your web server,      |
                |                                   | application server, load          |
                |                                   | balancer, etc. is properly        |
                |                                   | configured to set the             |
                |                                   | Content-Security-Policy header.   |
                +-----------------------------------+-----------------------------------+

    2.  #### [http://localhost:8000]{.site} (1)

        1.  ##### [Content Security Policy (CSP) Header Not Set](#alert-type-1) (1)

            1.  [GET
                http://localhost:8000/register]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        | -   [CWE-693](https://cwe.mit     |
                |                                   | re.org/data/definitions/693.html) |
                |                                   | -   [OWASP_2021                   |
                |                                   | _A05](https://owasp.org/Top10/A05 |
                |                                   | _2021-Security_Misconfiguration/) |
                |                                   | -                                 |
                |                                   | [OWASP_2017_A06](https://owasp.or |
                |                                   | g/www-project-top-ten/2017/A6_201 |
                |                                   | 7-Security_Misconfiguration.html) |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | Content Security Policy (CSP) is  |
                |                                   | an added layer of security that   |
                |                                   | helps to detect and mitigate      |
                |                                   | certain types of attacks,         |
                |                                   | including Cross Site Scripting    |
                |                                   | (XSS) and data injection attacks. |
                |                                   | These attacks are used for        |
                |                                   | everything from data theft to     |
                |                                   | site defacement or distribution   |
                |                                   | of malware. CSP provides a set of |
                |                                   | standard HTTP headers that allow  |
                |                                   | website owners to declare         |
                |                                   | approved sources of content that  |
                |                                   | browsers should be allowed to     |
                |                                   | load on that page --- covered     |
                |                                   | types are JavaScript, CSS, HTML   |
                |                                   | frames, fonts, images and         |
                |                                   | embeddable objects such as Java   |
                |                                   | applets, ActiveX, audio and video |
                |                                   | files.                            |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (237 bytes)                       |
                |                                   |     GET http:/                    |
                |                                   | /localhost:8000/register HTTP/1.1 |
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
                |                                   | (141 bytes)                       |
                |                                   |     HTTP/1.1 200 OK               |
                |                                   |     conte                         |
                |                                   | nt-type: text/html; charset=UTF-8 |
                |                                   |     vary: Accept-Encoding         |
                |                                   |     content-length: 1145          |
                |                                   |     da                            |
                |                                   | te: Wed, 19 Feb 2025 09:19:18 GMT |
                |                                   |                                   |
                |                                   | Response body (1145 bytes)        |
                |                                   |     <!DOCTYPE html>               |
                |                                   |     <html lang="en">              |
                |                                   |                                   |
                |                                   |     <head>                        |
                |                                   |         <meta charset="UTF-8">    |
                |                                   |         <met                      |
                |                                   | a name="viewport" content="width= |
                |                                   | device-width, initial-scale=1.0"> |
                |                                   |                                   |
                |                                   |  <title>User Registration</title> |
                |                                   |         <link rel="st             |
                |                                   | ylesheet" href="/static/styles.cs |
                |                                   | s"> <!-- Link to external CSS --> |
                |                                   |     </head>                       |
                |                                   |                                   |
                |                                   |     <body>                        |
                |                                   |         <div class="container">   |
                |                                   |             <h1>Register</h1>     |
                |                                   |             <form                 |
                |                                   | action="/register" method="POST"> |
                |                                   |                 <label            |
                |                                   |  for="username">Username:</label> |
                |                                   |                                   |
                |                                   | <input type="text" id="username"  |
                |                                   | name="username" required><br><br> |
                |                                   |                 <label            |
                |                                   |  for="password">Password:</label> |
                |                                   |                 <inp              |
                |                                   | ut type="password" id="password"  |
                |                                   | name="password" required><br><br> |
                |                                   |                 <label f          |
                |                                   | or="birthdate">Birthdate:</label> |
                |                                   |                 <i                |
                |                                   | nput type="date" id="birthdate" n |
                |                                   | ame="birthdate" required><br><br> |
                |                                   |                                   |
                |                                   |   <label for="role">Role:</label> |
                |                                   |                                   |
                |                                   |    <select id="role" name="role"> |
                |                                   |                     <option v     |
                |                                   | alue="reserver">Reserver</option> |
                |                                   |                     <option val   |
                |                                   | ue="admin">Administrator</option> |
                |                                   |                 </select><br><br> |
                |                                   |                 <butto            |
                |                                   | n type="submit">Register</button> |
                |                                   |             </form>               |
                |                                   |         </div>                    |
                |                                   |     </body>                       |
                |                                   |                                   |
                |                                   |     </html>                       |
                +-----------------------------------+-----------------------------------+
                | Solution                          | Ensure that your web server,      |
                |                                   | application server, load          |
                |                                   | balancer, etc. is configured to   |
                |                                   | set the Content-Security-Policy   |
                |                                   | header.                           |
                +-----------------------------------+-----------------------------------+
    :::

2.  ::: {#alerts--risk-2-confidence-2}
    ### Risk=[Medium]{.risk-level}, Confidence=[Medium]{.confidence-level} (1)

    1.  #### [http://localhost:8000]{.site} (1)

        1.  ##### [Missing Anti-clickjacking Header](#alert-type-2) (1)

            1.  [GET
                http://localhost:8000/register]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        | -   [                             |
                |                                   | WSTG-v42-CLNT-09](https://owasp.o |
                |                                   | rg/www-project-web-security-testi |
                |                                   | ng-guide/v42/4-Web_Application_Se |
                |                                   | curity_Testing/11-Client-side_Tes |
                |                                   | ting/09-Testing_for_Clickjacking) |
                |                                   | -   [OWASP_2021                   |
                |                                   | _A05](https://owasp.org/Top10/A05 |
                |                                   | _2021-Security_Misconfiguration/) |
                |                                   | -                                 |
                |                                   | [OWASP_2017_A06](https://owasp.or |
                |                                   | g/www-project-top-ten/2017/A6_201 |
                |                                   | 7-Security_Misconfiguration.html) |
                |                                   | -   [CWE-1021](https://cwe.mitr   |
                |                                   | e.org/data/definitions/1021.html) |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | The response does not protect     |
                |                                   | against \'ClickJacking\' attacks. |
                |                                   | It should include either          |
                |                                   | Content-Security-Policy with      |
                |                                   | \'frame-ancestors\' directive or  |
                |                                   | X-Frame-Options.                  |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (237 bytes)                       |
                |                                   |     GET http:/                    |
                |                                   | /localhost:8000/register HTTP/1.1 |
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
                |                                   | (141 bytes)                       |
                |                                   |     HTTP/1.1 200 OK               |
                |                                   |     conte                         |
                |                                   | nt-type: text/html; charset=UTF-8 |
                |                                   |     vary: Accept-Encoding         |
                |                                   |     content-length: 1145          |
                |                                   |     da                            |
                |                                   | te: Wed, 19 Feb 2025 09:19:18 GMT |
                |                                   |                                   |
                |                                   | Response body (1145 bytes)        |
                |                                   |     <!DOCTYPE html>               |
                |                                   |     <html lang="en">              |
                |                                   |                                   |
                |                                   |     <head>                        |
                |                                   |         <meta charset="UTF-8">    |
                |                                   |         <met                      |
                |                                   | a name="viewport" content="width= |
                |                                   | device-width, initial-scale=1.0"> |
                |                                   |                                   |
                |                                   |  <title>User Registration</title> |
                |                                   |         <link rel="st             |
                |                                   | ylesheet" href="/static/styles.cs |
                |                                   | s"> <!-- Link to external CSS --> |
                |                                   |     </head>                       |
                |                                   |                                   |
                |                                   |     <body>                        |
                |                                   |         <div class="container">   |
                |                                   |             <h1>Register</h1>     |
                |                                   |             <form                 |
                |                                   | action="/register" method="POST"> |
                |                                   |                 <label            |
                |                                   |  for="username">Username:</label> |
                |                                   |                                   |
                |                                   | <input type="text" id="username"  |
                |                                   | name="username" required><br><br> |
                |                                   |                 <label            |
                |                                   |  for="password">Password:</label> |
                |                                   |                 <inp              |
                |                                   | ut type="password" id="password"  |
                |                                   | name="password" required><br><br> |
                |                                   |                 <label f          |
                |                                   | or="birthdate">Birthdate:</label> |
                |                                   |                 <i                |
                |                                   | nput type="date" id="birthdate" n |
                |                                   | ame="birthdate" required><br><br> |
                |                                   |                                   |
                |                                   |   <label for="role">Role:</label> |
                |                                   |                                   |
                |                                   |    <select id="role" name="role"> |
                |                                   |                     <option v     |
                |                                   | alue="reserver">Reserver</option> |
                |                                   |                     <option val   |
                |                                   | ue="admin">Administrator</option> |
                |                                   |                 </select><br><br> |
                |                                   |                 <butto            |
                |                                   | n type="submit">Register</button> |
                |                                   |             </form>               |
                |                                   |         </div>                    |
                |                                   |     </body>                       |
                |                                   |                                   |
                |                                   |     </html>                       |
                +-----------------------------------+-----------------------------------+
                | Parameter                         |     x-frame-options               |
                +-----------------------------------+-----------------------------------+
                | Solution                          | Modern Web browsers support the   |
                |                                   | Content-Security-Policy and       |
                |                                   | X-Frame-Options HTTP headers.     |
                |                                   | Ensure one of them is set on all  |
                |                                   | web pages returned by your        |
                |                                   | site/app.                         |
                |                                   |                                   |
                |                                   | If you expect the page to be      |
                |                                   | framed only by pages on your      |
                |                                   | server (e.g. it\'s part of a      |
                |                                   | FRAMESET) then you\'ll want to    |
                |                                   | use SAMEORIGIN, otherwise if you  |
                |                                   | never expect the page to be       |
                |                                   | framed, you should use DENY.      |
                |                                   | Alternatively consider            |
                |                                   | implementing Content Security     |
                |                                   | Policy\'s \"frame-ancestors\"     |
                |                                   | directive.                        |
                +-----------------------------------+-----------------------------------+
    :::

3.  ::: {#alerts--risk-1-confidence-2}
    ### Risk=[Low]{.risk-level}, Confidence=[Medium]{.confidence-level} (2)

    1.  #### [http://localhost:8000]{.site} (2)

        1.  ##### [Application Error Disclosure](#alert-type-3) (1)

            1.  [POST
                http://localhost:8000/register]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        | -   [WSTG-v4                      |
                |                                   | 2-ERRH-02](https://owasp.org/www- |
                |                                   | project-web-security-testing-guid |
                |                                   | e/v42/4-Web_Application_Security_ |
                |                                   | Testing/08-Testing_for_Error_Hand |
                |                                   | ling/02-Testing_for_Stack_Traces) |
                |                                   | -   [WSTG-v42-ERRH-01](           |
                |                                   | https://owasp.org/www-project-web |
                |                                   | -security-testing-guide/v42/4-Web |
                |                                   | _Application_Security_Testing/08- |
                |                                   | Testing_for_Error_Handling/01-Tes |
                |                                   | ting_For_Improper_Error_Handling) |
                |                                   | -   [OWASP_2021                   |
                |                                   | _A05](https://owasp.org/Top10/A05 |
                |                                   | _2021-Security_Misconfiguration/) |
                |                                   | -                                 |
                |                                   | [OWASP_2017_A06](https://owasp.or |
                |                                   | g/www-project-top-ten/2017/A6_201 |
                |                                   | 7-Security_Misconfiguration.html) |
                |                                   | -   [CWE-200](https://cwe.mit     |
                |                                   | re.org/data/definitions/200.html) |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | This page contains an             |
                |                                   | error/warning message that may    |
                |                                   | disclose sensitive information    |
                |                                   | like the location of the file     |
                |                                   | that produced the unhandled       |
                |                                   | exception. This information can   |
                |                                   | be used to launch further attacks |
                |                                   | against the web application. The  |
                |                                   | alert could be a false positive   |
                |                                   | if the error message is found     |
                |                                   | inside a documentation page.      |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (348 bytes)                       |
                |                                   |     POST http:/                   |
                |                                   | /localhost:8000/register HTTP/1.1 |
                |                                   |     host: localhost:8000          |
                |                                   |     user-agent: Mozilla/5.0       |
                |                                   | (Windows NT 10.0; Win64; x64) App |
                |                                   | leWebKit/537.36 (KHTML, like Geck |
                |                                   | o) Chrome/131.0.0.0 Safari/537.36 |
                |                                   |     pragma: no-cache              |
                |                                   |     cache-control: no-cache       |
                |                                   |     content-type:                 |
                |                                   | application/x-www-form-urlencoded |
                |                                   |     refere                        |
                |                                   | r: http://localhost:8000/register |
                |                                   |     content-length: 57            |
                |                                   |                                   |
                |                                   | Request body (57 bytes)           |
                |                                   |     username=ZAP&password=ZA      |
                |                                   | P&birthdate=2025-02-19&role=admin |
                +-----------------------------------+-----------------------------------+
                | Response                          | Status line and header section    |
                |                                   | (159 bytes)                       |
                |                                   |     H                             |
                |                                   | TTP/1.1 500 Internal Server Error |
                |                                   |     conten                        |
                |                                   | t-type: text/plain; charset=UTF-8 |
                |                                   |     vary: Accept-Encoding         |
                |                                   |     content-length: 25            |
                |                                   |     da                            |
                |                                   | te: Wed, 19 Feb 2025 09:19:18 GMT |
                |                                   |                                   |
                |                                   | Response body (25 bytes)          |
                |                                   |     Error during registration     |
                +-----------------------------------+-----------------------------------+
                | Evidence                          |     H                             |
                |                                   | TTP/1.1 500 Internal Server Error |
                +-----------------------------------+-----------------------------------+
                | Solution                          | Review the source code of this    |
                |                                   | page. Implement custom error      |
                |                                   | pages. Consider implementing a    |
                |                                   | mechanism to provide a unique     |
                |                                   | error reference/identifier to the |
                |                                   | client (browser) while logging    |
                |                                   | the details on the server side    |
                |                                   | and not exposing them to the      |
                |                                   | user.                             |
                +-----------------------------------+-----------------------------------+

        2.  ##### [X-Content-Type-Options Header Missing](#alert-type-4) (1)

            1.  [GET
                http://localhost:8000/static/styles.css]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        | -   [CWE-693](https://cwe.mit     |
                |                                   | re.org/data/definitions/693.html) |
                |                                   | -   [OWASP_2021                   |
                |                                   | _A05](https://owasp.org/Top10/A05 |
                |                                   | _2021-Security_Misconfiguration/) |
                |                                   | -                                 |
                |                                   | [OWASP_2017_A06](https://owasp.or |
                |                                   | g/www-project-top-ten/2017/A6_201 |
                |                                   | 7-Security_Misconfiguration.html) |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | The Anti-MIME-Sniffing header     |
                |                                   | X-Content-Type-Options was not    |
                |                                   | set to \'nosniff\'. This allows   |
                |                                   | older versions of Internet        |
                |                                   | Explorer and Chrome to perform    |
                |                                   | MIME-sniffing on the response     |
                |                                   | body, potentially causing the     |
                |                                   | response body to be interpreted   |
                |                                   | and displayed as a content type   |
                |                                   | other than the declared content   |
                |                                   | type. Current (early 2014) and    |
                |                                   | legacy versions of Firefox will   |
                |                                   | use the declared content type (if |
                |                                   | one is set), rather than          |
                |                                   | performing MIME-sniffing.         |
                +-----------------------------------+-----------------------------------+
                | Other info                        | This issue still applies to error |
                |                                   | type pages (401, 403, 500, etc.)  |
                |                                   | as those pages are often still    |
                |                                   | affected by injection issues, in  |
                |                                   | which case there is still concern |
                |                                   | for browsers sniffing pages away  |
                |                                   | from their actual content type.   |
                |                                   |                                   |
                |                                   | At \"High\" threshold this scan   |
                |                                   | rule will not alert on client or  |
                |                                   | server error responses.           |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (287 bytes)                       |
                |                                   |     GET http://localhos           |
                |                                   | t:8000/static/styles.css HTTP/1.1 |
                |                                   |     host: localhost:8000          |
                |                                   |     user-agent: Mozilla/5.0       |
                |                                   | (Windows NT 10.0; Win64; x64) App |
                |                                   | leWebKit/537.36 (KHTML, like Geck |
                |                                   | o) Chrome/131.0.0.0 Safari/537.36 |
                |                                   |     pragma: no-cache              |
                |                                   |     cache-control: no-cache       |
                |                                   |     refere                        |
                |                                   | r: http://localhost:8000/register |
                |                                   |                                   |
                |                                   | Request body (0 bytes)            |
                +-----------------------------------+-----------------------------------+
                | Response                          | Status line and header section    |
                |                                   | (140 bytes)                       |
                |                                   |     HTTP/1.1 200 OK               |
                |                                   |     cont                          |
                |                                   | ent-type: text/css; charset=utf-8 |
                |                                   |     vary: Accept-Encoding         |
                |                                   |     da                            |
                |                                   | te: Wed, 19 Feb 2025 09:19:18 GMT |
                |                                   |     content-length: 1239          |
                |                                   |                                   |
                |                                   | Response body (1239 bytes)        |
                |                                   |     body {                        |
                |                                   |                                   |
                |                                   |   font-family: Arial, sans-serif; |
                |                                   |                                   |
                |                                   |        background-color: #f4f4f9; |
                |                                   |         display: flex;            |
                |                                   |         justify-content: center;  |
                |                                   |         align-items: center;      |
                |                                   |         height: 100vh;            |
                |                                   |         margin: 0;                |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     .container {                  |
                |                                   |         background-color: white;  |
                |                                   |         padding: 2rem;            |
                |                                   |         border-radius: 8px;       |
                |                                   |         box-shad                  |
                |                                   | ow: 0 4px 8px rgba(0, 0, 0, 0.1); |
                |                                   |         width: 100%;              |
                |                                   |         max-width: 400px;         |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     h1 {                          |
                |                                   |         text-align: center;       |
                |                                   |         color: #333;              |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     label {                       |
                |                                   |         font-weight: bold;        |
                |                                   |         color: #555;              |
                |                                   |         display: block;           |
                |                                   |         margin-bottom: 0.5rem;    |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     input,                        |
                |                                   |     select {                      |
                |                                   |         width: 100%;              |
                |                                   |         padding: 0.8rem;          |
                |                                   |         margin-bottom: 1rem;      |
                |                                   |         border: 1px solid #ccc;   |
                |                                   |         border-radius: 4px;       |
                |                                   |         box-sizing: border-box;   |
                |                                   |         font-size: 1rem;          |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     button {                      |
                |                                   |         width: 100%;              |
                |                                   |                                   |
                |                                   |        background-color: #007bff; |
                |                                   |         color: white;             |
                |                                   |         padding: 0.8rem;          |
                |                                   |         border: none;             |
                |                                   |         border-radius: 4px;       |
                |                                   |         font-size: 1rem;          |
                |                                   |         cursor: pointer;          |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     button:hover {                |
                |                                   |                                   |
                |                                   |        background-color: #0056b3; |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     .error {                      |
                |                                   |         color: red;               |
                |                                   |         font-size: 0.9rem;        |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     .success {                    |
                |                                   |         color: green;             |
                |                                   |         font-size: 0.9rem;        |
                |                                   |     }                             |
                |                                   |                                   |
                |                                   |     /* Respon                     |
                |                                   | sive design for mobile screens */ |
                |                                   |     @media (max-width: 600px) {   |
                |                                   |         .container {              |
                |                                   |             padding: 1.5rem;      |
                |                                   |             width: 100%;          |
                |                                   |         }                         |
                |                                   |     }                             |
                +-----------------------------------+-----------------------------------+
                | Parameter                         |     x-content-type-options        |
                +-----------------------------------+-----------------------------------+
                | Solution                          | Ensure that the application/web   |
                |                                   | server sets the Content-Type      |
                |                                   | header appropriately, and that it |
                |                                   | sets the X-Content-Type-Options   |
                |                                   | header to \'nosniff\' for all web |
                |                                   | pages.                            |
                |                                   |                                   |
                |                                   | If possible, ensure that the end  |
                |                                   | user uses a standards-compliant   |
                |                                   | and modern web browser that does  |
                |                                   | not perform MIME-sniffing at all, |
                |                                   | or that can be directed by the    |
                |                                   | web application/web server to not |
                |                                   | perform MIME-sniffing.            |
                +-----------------------------------+-----------------------------------+
    :::

4.  ::: {#alerts--risk-0-confidence-1}
    ### Risk=[Informational]{.risk-level}, Confidence=[Low]{.confidence-level} (1)

    1.  #### [http://127.0.0.1:40297]{.site} (1)

        1.  ##### [User Controllable HTML Element Attribute (Potential XSS)](#alert-type-5) (1)

            1.  [POST
                http://127.0.0.1:40297/Frames]{.request-method-n-url}
                +-----------------------------------+-----------------------------------+
                | Alert tags                        | -   [OWASP_2017_A01](             |
                |                                   | https://owasp.org/www-project-top |
                |                                   | -ten/2017/A1_2017-Injection.html) |
                |                                   | -   [CWE-20](https://cwe.mi       |
                |                                   | tre.org/data/definitions/20.html) |
                |                                   | -   [OWASP_2021_A03](https://owa  |
                |                                   | sp.org/Top10/A03_2021-Injection/) |
                +-----------------------------------+-----------------------------------+
                | Alert description                 | This check looks at user-supplied |
                |                                   | input in query string parameters  |
                |                                   | and POST data to identify where   |
                |                                   | certain HTML attribute values     |
                |                                   | might be controlled. This         |
                |                                   | provides hot-spot detection for   |
                |                                   | XSS (cross-site scripting) that   |
                |                                   | will require further review by a  |
                |                                   | security analyst to determine     |
                |                                   | exploitability.                   |
                +-----------------------------------+-----------------------------------+
                | Other info                        | User-controlled HTML attribute    |
                |                                   | values were found. Try injecting  |
                |                                   | special characters to see if XSS  |
                |                                   | might be possible. The page at    |
                |                                   | the following URL:                |
                |                                   |                                   |
                |                                   | http://127.0.0.1:40297/Frames     |
                |                                   |                                   |
                |                                   | appears to include user input in: |
                |                                   |                                   |
                |                                   | a(n) \[input\] tag \[value\]      |
                |                                   | attribute                         |
                |                                   |                                   |
                |                                   | The user input found was:         |
                |                                   |                                   |
                |                                   | anticsrf=630                      |
                |                                   | 595c4-9100-4432-9315-1548680daa6b |
                |                                   |                                   |
                |                                   | The user-controlled value was:    |
                |                                   |                                   |
                |                                   | 630                               |
                |                                   | 595c4-9100-4432-9315-1548680daa6b |
                +-----------------------------------+-----------------------------------+
                | Request                           | Request line and header section   |
                |                                   | (622 bytes)                       |
                |                                   |     POST http:                    |
                |                                   | //127.0.0.1:40297/Frames HTTP/1.1 |
                |                                   |     host: 127.0.0.1:40297         |
                |                                   |     User-Agent: Mozi              |
                |                                   | lla/5.0 (X11; Linux x86_64; rv:12 |
                |                                   | 8.0) Gecko/20100101 Firefox/128.0 |
                |                                   |     Accept: text/html,            |
                |                                   | application/xhtml+xml,application |
                |                                   | /xml;q=0.9,image/avif,image/webp, |
                |                                   | image/png,image/svg+xml,*/*;q=0.8 |
                |                                   |                                   |
                |                                   |   Accept-Language: en-US,en;q=0.5 |
                |                                   |     Content-Type:                 |
                |                                   | application/x-www-form-urlencoded |
                |                                   |     Content-Length: 51            |
                |                                   |                                   |
                |                                   |   Origin: https://127.0.0.1:40297 |
                |                                   |     Connection: keep-alive        |
                |                                   |     Refere                        |
                |                                   | r: https://127.0.0.1:40297/Frames |
                |                                   |     Upgrade-Insecure-Requests: 1  |
                |                                   |     Sec-Fetch-Dest: document      |
                |                                   |     Sec-Fetch-Mode: navigate      |
                |                                   |     Sec-Fetch-Site: same-origin   |
                |                                   |     Sec-Fetch-User: ?1            |
                |                                   |     Priority: u=0, i              |
                |                                   |                                   |
                |                                   | Request body (51 bytes)           |
                |                                   |     anticsrf=630595c4-            |
                |                                   | 9100-4432-9315-1548680daa6b&key=o |
                +-----------------------------------+-----------------------------------+
                | Response                          | Status line and header section    |
                |                                   | (520 bytes)                       |
                |                                   |     HTTP/1.1 200 OK               |
                |                                   |     Pragma: no-cache              |
                |                                   |     Cache-Control: no             |
                |                                   | -cache, no-store, must-revalidate |
                |                                   |                                   |
                |                                   |   Content-Security-Policy: defaul |
                |                                   | t-src 'none'; script-src 'self';  |
                |                                   | connect-src 'self'; child-src 'se |
                |                                   | lf'; img-src 'self' data:; font-s |
                |                                   | rc 'self' data:; style-src 'self' |
                |                                   |     Access-Contro                 |
                |                                   | l-Allow-Methods: GET,POST,OPTIONS |
                |                                   |     Access-                       |
                |                                   | Control-Allow-Headers: ZAP-Header |
                |                                   |     X-Frame-Options: DENY         |
                |                                   |                                   |
                |                                   |   X-XSS-Protection: 1; mode=block |
                |                                   |                                   |
                |                                   |   X-Content-Type-Options: nosniff |
                |                                   |     X-Cla                         |
                |                                   | cks-Overhead: GNU Terry Pratchett |
                |                                   |     Content-Length: 2087          |
                |                                   |     Content-Type: text/html       |
                |                                   |                                   |
                |                                   | Response body (2087 bytes)        |
                |                                   |     <!DOCTYPE html>               |
                |                                   |     <html lang="en">              |
                |                                   |     <head>                        |
                |                                   |                                   |
                |                                   |     <title>The HUD Frames</title> |
                |                                   |                                   |
                |                                   |      <link href="tutorial.css" re |
                |                                   | l="stylesheet" type="text/css" /> |
                |                                   |     </head>                       |
                |                                   |     <body>                        |
                |                                   |     <div class="roundContainer">  |
                |                                   |         <h1>The HUD Frames</H1>   |
                |                                   |         The                       |
                |                                   | HUD overlays a set of frames on t |
                |                                   | op of the target application, whi |
                |                                   | ch in this case is this tutorial. |
                |                                   |         <p>                       |
                |                                   |         You can see 2             |
                |                                   |  of the HUD frames on the left- a |
                |                                   | nd right-hand sides of this page. |
                |                                   |         T                         |
                |                                   | hese contain a set of tools that  |
                |                                   | we will explain in this tutorial. |
                |                                   |         <p>                       |
                |                                   |                                   |
                |                                   |     If you hover over any of the  |
                |                                   | tools then you will see that they |
                |                                   |  expand to show more information. |
                |                                   |         <p>                       |
                |                                   |         T                         |
                |                                   | he tools are designed to take up  |
                |                                   | as little space as is practical,  |
                |                                   |                                   |
                |                                   |      but they could still obscure |
                |                                   |  information that you want to see |
                |                                   |         on the target page.       |
                |                                   |         <p>                       |
                |                                   |         If that happens           |
                |                                   | then you can hide these 2 frames  |
                |                                   | by clicking on the green HUD icon |
                |                                   |         <img src="ra              |
                |                                   | dar.png" alt="[green radar]"> nea |
                |                                   | r the bottom right of this page.  |
                |                                   |         <p>                       |
                |                                   |         The icon will chang       |
                |                                   | e to a grey colour <img src="rada |
                |                                   | r-grey.png" alt="[grey radar]">   |
                |                                   |         and the HUD s             |
                |                                   | ide frames will stay hidden until |
                |                                   |  you click on that button again,  |
                |                                   |         eve                       |
                |                                   | n if you navigate to a new page.  |
                |                                   |                                   |
                |                                   |             <h2>Task</h2>         |
                |                                   |                                   |
                |                                   | Enter the key that&apos;s shown o |
                |                                   | n the left-hand side of this page |
                |                                   |  (underneath the HUD frame) in or |
                |                                   | der to progress to the next page. |
                |                                   |                                   |
                |                                   |        Remember to re-enable the  |
                |                                   | HUD frames after copying the key. |
                |                                   |         <fo                       |
                |                                   | rm action="Frames" method="post"> |
                |                                   |         <input type="hidd         |
                |                                   | en" name="anticsrf" value="630595 |
                |                                   | c4-9100-4432-9315-1548680daa6b"/> |
                |                                   |         <table border=0>          |
                |                                   |             <tr>                  |
                |                                   |                 <td>Key:</td>     |
                |                                   |                                   |
                |                                   |            <td><input type="key"  |
                |                                   | id="key" name="key"></input></td> |
                |                                   |                                   |
                |                                   |       <td><input type="submit" id |
                |                                   | ="submit" value="Submit" /> </td> |
                |                                   |             <tr>                  |
                |                                   |         </table>                  |
                |                                   |         </form>                   |
                |                                   |         <p>&nbsp;<p>              |
                |                                   |                                   |
                |                                   |         <div class="buttonsDiv">  |
                |                                   |     <div class="indexDiv">        |
                |                                   |     <a href="Index"><bu           |
                |                                   | tton id="index-button">Index <img |
                |                                   |  src="exclamation-red.png" title= |
                |                                   | "New content added"></button></a> |
                |                                   |     </div>                        |
                |                                   |     <div class="prevNextDiv">     |
                |                                   |     <a href="Upgrade"><but        |
                |                                   | ton id="previous-button">Previous |
                |                                   | :&nbsp;HTTPS Upgrade</button></a> |
                |                                   |     <bu                           |
                |                                   | tton-disabled id="next-button">Ne |
                |                                   | xt:&nbsp;Alerts</button-disabled> |
                |                                   |     </div>                        |
                |                                   |     </div>                        |
                |                                   |                                   |
                |                                   |                                   |
                |                                   |     </div>                        |
                |                                   |                                   |
                |                                   |     <div class="frameskey">       |
                |                                   |     98959120                      |
                |                                   |     </div>                        |
                |                                   |                                   |
                |                                   |                                   |
                |                                   |     </body>                       |
                |                                   |     </html>                       |
                +-----------------------------------+-----------------------------------+
                | Parameter                         |     anticsrf                      |
                +-----------------------------------+-----------------------------------+
                | Solution                          | Validate all input and sanitize   |
                |                                   | output it before writing to any   |
                |                                   | HTML attributes.                  |
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
    #### CSP: Wildcard Directive

    +-----------------------------------+-----------------------------------+
    | Source                            | raised by a passive scanner       |
    |                                   | ([CSP](https://www                |
    |                                   | .zaproxy.org/docs/alerts/10055/)) |
    +-----------------------------------+-----------------------------------+
    | CWE ID                            | [693](https://cwe.mit             |
    |                                   | re.org/data/definitions/693.html) |
    +-----------------------------------+-----------------------------------+
    | WASC ID                           | 15                                |
    +-----------------------------------+-----------------------------------+
    | Reference                         | 1.  <https://www.w3.org/TR/CSP/>  |
    |                                   | 2.  <https://caniuse.com          |
    |                                   | /#search=content+security+policy> |
    |                                   | 3.  <http                         |
    |                                   | s://content-security-policy.com/> |
    |                                   | 4.  <https://                     |
    |                                   | github.com/HtmlUnit/htmlunit-csp> |
    |                                   | 5.  <https:/                      |
    |                                   | /developers.google.com/web/fundam |
    |                                   | entals/security/csp#policy_applie |
    |                                   | s_to_a_wide_variety_of_resources> |
    +-----------------------------------+-----------------------------------+
    :::

2.  ::: {#alert-type-1}
    #### Content Security Policy (CSP) Header Not Set

    +-----------------------------------+-----------------------------------+
    | Source                            | raised by a passive scanner       |
    |                                   | ([Content Security Policy (CSP)   |
    |                                   | Header Not                        |
    |                                   | Set](https://www                  |
    |                                   | .zaproxy.org/docs/alerts/10038/)) |
    +-----------------------------------+-----------------------------------+
    | CWE ID                            | [693](https://cwe.mit             |
    |                                   | re.org/data/definitions/693.html) |
    +-----------------------------------+-----------------------------------+
    | WASC ID                           | 15                                |
    +-----------------------------------+-----------------------------------+
    | Reference                         | 1.  <https://developer.mozilla.or |
    |                                   | g/en-US/docs/Web/Security/CSP/Int |
    |                                   | roducing_Content_Security_Policy> |
    |                                   | 2.  <https://cheatsheetseri       |
    |                                   | es.owasp.org/cheatsheets/Content_ |
    |                                   | Security_Policy_Cheat_Sheet.html> |
    |                                   | 3.  <https://www.w3.org/TR/CSP/>  |
    |                                   | 4.  <http                         |
    |                                   | s://w3c.github.io/webappsec-csp/> |
    |                                   | 5                                 |
    |                                   | .  <https://web.dev/articles/csp> |
    |                                   | 6.  <https://caniuse              |
    |                                   | .com/#feat=contentsecuritypolicy> |
    |                                   | 7.  <http                         |
    |                                   | s://content-security-policy.com/> |
    +-----------------------------------+-----------------------------------+
    :::

3.  ::: {#alert-type-2}
    #### Missing Anti-clickjacking Header

    +-----------------------------------+-----------------------------------+
    | Source                            | raised by a passive scanner       |
    |                                   | ([Anti-clickjacking               |
    |                                   | Header](https://www               |
    |                                   | .zaproxy.org/docs/alerts/10020/)) |
    +-----------------------------------+-----------------------------------+
    | CWE ID                            | [1021](https://cwe.mitr           |
    |                                   | e.org/data/definitions/1021.html) |
    +-----------------------------------+-----------------------------------+
    | WASC ID                           | 15                                |
    +-----------------------------------+-----------------------------------+
    | Reference                         | 1.  <https://                     |
    |                                   | developer.mozilla.org/en-US/docs/ |
    |                                   | Web/HTTP/Headers/X-Frame-Options> |
    +-----------------------------------+-----------------------------------+
    :::

4.  ::: {#alert-type-3}
    #### Application Error Disclosure

      --------- -----------------------------------------------------------------------------------------------------------
      Source    raised by a passive scanner ([Application Error Disclosure](https://www.zaproxy.org/docs/alerts/90022/))
      CWE ID    [200](https://cwe.mitre.org/data/definitions/200.html)
      WASC ID   13
      --------- -----------------------------------------------------------------------------------------------------------
    :::

5.  ::: {#alert-type-4}
    #### X-Content-Type-Options Header Missing

    +-----------------------------------+-----------------------------------+
    | Source                            | raised by a passive scanner       |
    |                                   | ([X-Content-Type-Options Header   |
    |                                   | Missing](https://www              |
    |                                   | .zaproxy.org/docs/alerts/10021/)) |
    +-----------------------------------+-----------------------------------+
    | CWE ID                            | [693](https://cwe.mit             |
    |                                   | re.org/data/definitions/693.html) |
    +-----------------------------------+-----------------------------------+
    | WASC ID                           | 15                                |
    +-----------------------------------+-----------------------------------+
    | Reference                         | 1.  <https://learn.microsoft.     |
    |                                   | com/en-us/previous-versions/windo |
    |                                   | ws/internet-explorer/ie-developer |
    |                                   | /compatibility/gg622941(v=vs.85)> |
    |                                   | 2.  <https://owasp.or             |
    |                                   | g/www-community/Security_Headers> |
    +-----------------------------------+-----------------------------------+
    :::

6.  ::: {#alert-type-5}
    #### User Controllable HTML Element Attribute (Potential XSS)

    +-----------------------------------+-----------------------------------+
    | Source                            | raised by a passive scanner       |
    |                                   | ([User Controllable HTML Element  |
    |                                   | Attribute (Potential              |
    |                                   | XSS)](https://www                 |
    |                                   | .zaproxy.org/docs/alerts/10031/)) |
    +-----------------------------------+-----------------------------------+
    | CWE ID                            | [20](https://cwe.mi               |
    |                                   | tre.org/data/definitions/20.html) |
    +-----------------------------------+-----------------------------------+
    | WASC ID                           | 20                                |
    +-----------------------------------+-----------------------------------+
    | Reference                         | 1.  <https://cheatsh              |
    |                                   | eetseries.owasp.org/cheatsheets/I |
    |                                   | nput_Validation_Cheat_Sheet.html> |
    +-----------------------------------+-----------------------------------+
    :::
:::
:::
:::

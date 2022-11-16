# DNS-practice

## mariasefue.tech 

## Run Flask Application on a VM
 1. Created a VM on GCP
 2. Go to GCP terminal and insert:
 3. Sudo apt-get update
 4. Sudo apt install python3-pip
 5. Sudo apt install python3-flask
 6. git clone https://github.com/MariaLozano01/flask-html.git
 7. Navigate to files using --> ls into files
 8. insert 'cd' to log into flask-html file
 9. run the command 'sudo python3 app.py' to run application 

## Run Flask Application on Domain Service 

 1. Browse to Domain Service Provider (https://get.tech/)
 2. Log in
 3. Add a new A Record
 4. Give a name to the domain (@ can be used as a wildcard)
 5. Insert our External IP Address from our VM
 6. 7200 for the TTL Value
 7. Add Record

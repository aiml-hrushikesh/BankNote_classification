# BankNote_classification
BankNote_classification, FastAPI,ML
conda create -n myenv python=3.9
conda activate myenv

conda install package_name

uvicorn main:app --reload

# run app on EC2 instance
create AWS account
create EC2 instance>download and save .pem file in folder
Download putty and puttygen
Generate private key with putty generator
in putty key generator load .pem file and save private key by extension of .ppk
go in EC2 connect>copy DNS>open WinSCP paste hostname>write username from ec2 connect below DNS hostname
click on advance option in winSCP> in Aunthentication upload .ppk file
click on login of winSCP>accept>drag requirements.txt,pkl,app.py files
go in puttycpaste hostname>click on SSH>Auth>put private key .ppk file>session>save
then on terminal login as: username
write command:
for ubuntu:sudo apt-get update && sudo apt-get install python3-pip
for fedora:sudo yum install python3-pip
update the port in fastapi code to 0.0.0.0 8080
install libraries by connecting putty
python main.py






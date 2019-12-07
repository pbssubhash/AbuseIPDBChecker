# Abuse IP DB Checker
This is a Python Script to query the ABUSE IP DB with an IP or a list of IPs.

# Usage 

## Getting started
```
git clone https://github.com/pbssubhash/AbuseIPDBChecker # need git for getting this done, alternatively download a zip!!
cd AbuseIPDBChecker
python AbuseIPDBChecker.py # will print the help
```

## Let's get rolling!
### From a File:
Use the parameter `--file` to specify the location of the file with the IPs. Format: 1 IP per line. Check example_ip.txt
```
python AbuseIPDBChecker.py --format=csv --file=ips.txt # output in CSV format
python AbuseIPDBChecker.py --format=readable --file=ips.txt # output in readable format
python AbuseIPDBChecker.py --format=json --file=ips.txt # output in json format
```
### To check a single IP:
Use the parameter `--ip` to specify a single IP.
```
python AbuseIPDBChecker.py --format=csv --ip=1.1.1.1 # output in CSV format
python AbuseIPDBChecker.py --format=readable --ip=1.1.1.1 # output in readable format
python AbuseIPDBChecker.py --format=json --ip=1.1.1.1 # output in json format
```

## Need Help? 
Open an issue if you require any help or any new feature (Pull request is much appreciated too!)

# A CLI for Kenna Platform

Command line interface for Kenna API. This application is created for the one who wants to get quick informaiton from Kenna platform. 

## The Kenna Modules Implemented with The API

 - [x] Vulnerabilities
 - [x] Assets
 - [x] Asset Tagging
 - [x] Asset Groups
 - [ ] Asset group reporting
 - [ ] Connectors
 - [ ] Connector Runs
 - [ ] Users
 - [ ] Roles
 - [x] Fixes
 - [ ] Applications
 - [ ] Application Reporting
 - [ ] Dashboard Groups
 - [ ] Data export
 - [x] CVEs 
 - [ ] Kenna VI+
 - [ ] Inference

## Usage

Show a brief information based on a search pattern
```sh
python3 kenna.py summary <kenna-search pattern>
```

Show vulnerabilities based on a search pattern
```sh
python3 kenna.py assets <kenna-search pattern>
```

Show vulnerabilities based on a search pattern
```sh
python3 kenna.py assets <kenna-search pattern>
```

Get vulnerability score history: 
```sh
python3 kenna.py cvehistory cve-2020-1472
```

## Kenna Library 



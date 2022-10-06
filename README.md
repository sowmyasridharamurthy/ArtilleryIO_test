# ArtilleryIO_test
Artillery is node based performance testing tool that. They are the only tool who support native load testing for aws. 
Artillery also has integration with playwright which makes developers to run existing E2E scripts for load testing. This file contains a basic test file which gives you a good understanding of how to write simple test scripts. 

# Installation
### Pre-requisites: Node
- Clone the repository
- Execute npm i
- run the command  : artillery run 1.name-api/test.yml 

# Generate report
- artillery run --output report.json  <filename>
- artillery report  report.json  

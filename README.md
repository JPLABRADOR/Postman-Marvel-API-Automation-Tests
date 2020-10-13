# Postman-Marvel-API-Automation-Tests
Automated testing for the Marvel API using Postman and Newman.

Marvel API website: https://developer.marvel.com/docs \
base url: https://gateway.marvel.com

#### Testing Focus:
Valid and invalid input data is used to test the "characters" endpoint functionality.

#### Tested using:
* System: Windows 10
* API version: Cable
* Postman for Windows Version 7.34.0 win32 10.0.18363 / x64
* Newman 5.1.0


#### Instructions:
Install Postman: https://www.postman.com/downloads/

Install NodeJS (includes npm): https://nodejs.org/en/download/

Open a terminal or command line and install Newman:
```
npm install -g newman
```
Navigate to your local project folder. Clone the following repository:
```
git clone https://github.com/JPLABRADOR/Postman-Marvel-API-Automation-Tests.git
```
Navigate to the newly cloned directory:
```
cd Postman-Marvel-API-Automation-Tests
```
From the "Postman-Marvel-API-Automation-Tests" directory, Execute the Postman tests using Newman:
```
newman run Marvel.postman_collection.json -e Marvel.postman_environment.json
```

<p align="center"><img width=12.5% src="http://sudirlaycoders.com/files/sclogo.png"></p>
<p align="center"><h1>awsdomainapi - v1.0.1</h1></p>
<p align="center"><i>Query Domain Name availability with node.js via Amazon Web Services SDK. Compatible with any Node.js app, just integrate this into your application.
<br />This is great for use with dns management, domain reservation services, or more advanced logic.</i></p>


## Basic Overview
[![Awsdomainapi License](https://img.shields.io/badge/Licensed-Matt%20Trotter-orange.svg)](https://github.com/sudir/awsdomainapi/blob/master/LICENSE.txt)
[![awsdomainapi](https://img.shields.io/badge/awsdomainapi-npm-blue.svg)](https://www.npmjs.com/package/awsdomainapi)
[![SudirlayCoders](https://img.shields.io/badge/SudirlayCoders-Experts-brightgreen.svg)](http://www.sudirlaycoders.com)

<br />
Using awsdomainapi is easy, simply export IAM environment variables for route53 access. 
<br>Then integrate/install package into your app, then simply run this app by typing below:
<br>This is developed from scratch, meaning your chances of finding something opensource out there that mirrors this atm is slim to none.

## Setup IAM Access for runtme environment: 
<i>See here for instaling pip - https://pip.pypa.io/en/stable/installing/</i>
```
pip install awscli
aws configure
```

##### Install awsdomainapi, in the same directory where awsdomainapi is located type:
```
npm install awsdomainapi
```

## How to start running App, these are all various ways to run the app. 
<i>See more on forever - https://github.com/foreverjs/forever</i>
```
node index.js
forever start index.js
```
<br>

## How to test Domain availability?

#### 
During testing, simply use curl to generate post request only specifying the domain name with top level domain. <i>"domainname.tld"</i>. 
<br />You can add sanitization around this from your application UI side once running. Contributors to this project should also be looking
forward to oauth integration coming soon, in the mean-time security is on you to sanitize for the time being.

```
curl -d "DomainName=domain.com" localhost:8135
```

<i>More to come soon....</i>
<br />Invented By: <i>Matthew Trotter {C.E.O SudirlayCoders}</i>

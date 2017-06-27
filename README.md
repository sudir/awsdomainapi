<p align="center"><img width=12.5% src="http://sudirlaycoders.com/files/sclogo.png"></p>
[![Chrome Web Store](https://img.shields.io/chrome-web-store/stars/nimelepbpejjlbmoobocpfnjhihnpked.svg)](http://www.sudirlaycoders.com)
[![npm (scoped)](https://img.shields.io/npm/v/@cycle/core.svg)](https://www.npmjs.com/package/awsdomainapi)


<p align="center"><h1>awsdomainapi - v1.0.1</h1></p>
<p align="center"><i>Query Domain Name availability with node.js via Amazon Web Services SDK. Compatible with any Node.js app, just integrate this into your application.
<br />This is great for use with dns management, domain reservation services, or more advanced logic.</i></p>


## Basic Overview
[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)](https://github.com/sudir/awsdomainapi/blob/master/LICENSE.txt)

Using awsdomainapi is easy, simply export IAM environment variables for route53 access. 
<br>Then integrate/install package into your app, then simply run this app by typing below:
<br>

## Setup IAM Access for runtme environment, see here for instaling pip: 
<i>https://pip.pypa.io/en/stable/installing/</i>
```
pip install awscli
aws configure
```

##### Install awsdomainapi, in the same directory where awsdomainapi is located type:
```
npm install awsdomainapi
```

## How to start running App, these are all various ways to run the app. See more on forever: https://github.com/foreverjs/forever
```
node index.js
forever start index.js
```
<br>

## How to test Domain availability?

#### 
During testing, enter only the <i>"domainname.tld"</i>. You can add sanitization around this from your application UI side.
Once running

```
curl -d "DomainName=domain.com" localhost:8135
```
The End - Invented By: Matthew Trotter {C.E.O SudirlayCoders}

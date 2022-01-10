---
id: doc8
title: BT Access Guidelines
sidebar_label: BT Access Guidelines
---

## Raising Access in NTT IT Support

This portal is about raising the request for software, admin access, VPN, network, system issues etc.. Login with your NTT provided portal ID and password. Below is the snapshot of the portal home page.

![alt text](/img/access/1.png)

## Slack, EE JIRA and WIKI Access:

https://wiki.intdigital.ee.co.uk/display/CP/3.f.i.+%5B%5D+-+CPCI+Phase+3+CPCI+P3+-+Web+-+Epics+and+User+Stories+Summary

https://jira.intdigital.ee.co.uk/secure/RapidBoard.jspa?rapidView=1216&projectKey=EEID

A Person who wants EE JIRA and EE WIKI access, please request your squad scrum master to get the access and log in.

![alt text](/img/access/2.png)

## BT Email Access:

A Person has to check with his/her respective LM(Line Manager) in setting up a SAP ID, BT UIN and BT Email Address. Once set, you will be receiving an email to login with temporary password. After logged in, you will be requesting to reset for a permanent password and ask your LM to change for permanent password and there you go with.

## BT JIRA Access:

You can login to this portal by using your IUSER/BT email and password.

- Step 1: Login using above said
- Step 2: Verify the OTP received in your registered mobile number
- Step3: After Verification, JIRA board is displayed.
  ![alt text](/img/access/3.png)
  ![alt text](/img/access/4.png)

## BT wiki Access:

You have to raise BT VPN access to access this website. In order to get BT VPN, you have to set Pulse Secure Client. Please raise request in NTT It Support portal to get the pulse secure client installed in your system.

## Mural/Figma Access:

Firstly, you have to register using NTT credentials and ask the respective person (board owner) to get the board launched.  

![alt text](/img/access/5.png)

## BT Git Issues and Solution for developers:

Make sure that your ip address is provided in your team for whitelisting. Create your git account using NTT email and share your git details with your scrum master to get project repo access. After that you have to generate personal token with the following steps.  

### Method for creating a personal token

- Go to https://github.com/settings/tokens, and generate the Personal access token. Be sure to save it.

Run Code using Command line:

Execute the below lines of code to set registry for your account to proceed further.

```
$ npm login --registry=https://npm.pkg.github.com --scope=@btplc
Username: <your git username>
Password: <TOKEN generated above>
Email: <your git email>
```

Once you get into your project repo, if you are facing issue with `npm install` then give the line `npm config set strict-ssl false` and run again.

---
title: "API key registration"
date: 2018-01-28T21:58:09+01:00
#anchor: "API"
menuTitle: "Developer guide - API Registration"
disableToc: true
weight: 10
---

To access certain API's you need to request the keys via email, see below. The information you provide will be used for statistical purposes and for reaching out to you in case of scheduled downtime, bug reporting etc. In a second phase, we will use this information to create an account where you will be able to manage your keys directly.
### Authentication

Once the keys are acquired, the authentication to the services is done using two query parameters client_id and client_secret. These are required on all requests. Below is a sample of how query parameters are used:
```
<https://apier.arbetsformedlingen.se/yrkesinfo/publik/raf/v1/yrken?client_id=123&client_secret=123>
```
By requesting the API Key, you are authorizing the data you are providing, to be stored for as long as you will have access to this API.
Request Access API Console

You can request access to this API via email to apirequest@jobtechdev.se. Please include the following in your request:
{{% notice info %}}
Email Subject: API request – "Name of the API"
Name:
Surname:
Company name (if applicable):
Application name:
Application description (please be short):
{{% /notice %}}

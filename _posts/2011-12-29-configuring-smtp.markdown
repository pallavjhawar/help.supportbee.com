---
layout: default
title: Configure a SMTP Server
description: Learn how to use a SMTP server for relaying emails to customers
categories: email.setup
---

Is it necessary to configure a SMTP Server?
-------------------------------------------

No. In fact, out of the box we can deliver emails to your customers without any configuration. However to ensure delivery, we sign emails as supportbeemail.com and some clients show a via supportbeemail.com string when showing emails. If you want to avoid this, you can use your own SMTP server. Using your own SMTP server also has the added benefit that all your emails are backed up on your own server.

How do I configure a SMTP Server?
---------------------------------

First of all, you need to know your SMTP settings. Different providers have different settings. For example, here are the settings that you need for [Gmail/Outlook.com](http://www.arclab.com/products/amlc/list-of-smtp-and-pop3-servers-mailserver-list.html). Please use the port for StartTLS (587 for Outlook/Gmail). Once you have the settings, proceed as follow

1. Visit Admin > Email Setup. Scroll down to the SMTP section SMTP section. Click 'Setup SMTP Server'.  
2. Fill in the SMTP Settings.
3. Click 'Save'. This may take upto 60 seconds as we verify your settings and attempt to contact your SMTP server


A note on monitoring SMTP
-------------------------

Please note that we cannot monitor your SMTP server for any issues. If you configure SMTP, you will have to worry about deliveries etc. This is clearly an advanced setting and not recommended unless you know what you are doing.

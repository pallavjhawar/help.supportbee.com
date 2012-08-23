---
layout: default
title: Email address in replies to customers
description: What email address is used in replies to the customers
categories: email.setup
---

{% include setup %}

When I reply from SupportBee, what is the 'From' email address? 
---------------------------------------------------------------

This depends on the source of the customer's request

1. If you are replying to an email that was [forwarded]({{ BASE_PATH }}/forwarding-your-support-emails) to SupportBee from your support inbox, we set the 'From' to the original email's 'To'. This would be the address of your support inbox forwarding emails to SupportBee.
2. If the request is a web ticket (submitted using the Widget or API), the 'From' is set to the [Primary Support Email Address]({{ BASE_PATH }}/primary-support-email-address)

---
layout: default
title: Working with Filters
description: How do work with filters
categories: filters
---

What are Filters?
-----------------

Much like [Gmail's filters](http://support.google.com/mail/bin/answer.py?hl=en&answer=6579), Filters in SupportBee allow you perform certain tasks (like adding a label/assigning to a user etc) on an new ticket if certain pre-defined conditions are met. For example, you may want to assign a ticket coming to support@company.com to 'Support Group' or you may want to add the label 'urgent' to tickets with 'downtime' in the subject.

How do I create a filter?
-------------------------

After you login as an admin,

1. Click on Admin link in the top right corner of the screen
2. Select the Filters tab
3. Click 'Add New Filter'
4. You can specify any (or all) four conditions. See the question below for details on different conditions
5. Click 'Preview Matches' to see what tickets match.
6. Once you are happy with the conditions, click 'Next'
7. Check the actions that you want to be performed on matching tickets after they are imported
8. Click 'Create Filter'

You filter would be created and applied to every new ticket

What are the different conditions that I can match?
---------------------------------------------------

*   ***From Email*** Matches the sender of the ticket. Enter the name or email address of a customer. You can use this to identify tickets from a particular customer.
*   ***Delivered-To*** Matches the address that the ticket was delivered to. If you are forwarding from different inboxes, you can use this filter to route tickets to different groups or adding a label based on the mailbox the ticket was delivered to. 
*   ***Subject with keywords*** Matches the subject. If you put more than one word, all of them will have to match for filter to be applies. The matching is case insensitive. 
*   ***Body with keywords*** Matches the body. If you put more than one word, all of them will have to match for filter to be applies. The matching is case insensitive.


If you fill in more than one condition, all of the conditions will have to match for the filter to be applied.

Can I use wildcards?
------------------------------

Yes, you can use wildcards when matching From and Delivered-To. For example \*@importantclient.com will match any importantclient.com email address.

How many filters can I create?
------------------------------

You can create as many filters as you want. However, there are a few points to remember

1. Applying the filters introduces a small delay in importing the ticket. More filters you have, higher the delay.
2. More than one filter may match for a given ticket. In case you have conflicting actions (like Assigning to a certain user in one and a different user in the other), only one will be performed. However, if you are adding different labels in both actions, both labels will be added.


How do I delete a filter?
-------------------------

After you login as an admin,

1. Click on Admin link in the top right corner of the screen
2. Select the Filters tab
3. In the listing, find the filter that you want and click 'Delete'






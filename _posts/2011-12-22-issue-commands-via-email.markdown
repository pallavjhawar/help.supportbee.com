---
layout: default
title: Reply and Issue Commands via Email
description: How to act on your tickets without leaving your email client
categories: handling.tickets
---

Can I reply to tickets from Email notifications?
---------------------------------------------------

Yes, you can. Not just that, you can even reply inline and/or copy commands like assign.me etc! 

Is there way to avoid multiple agents replying to the same email notification?                 
---------------------------------------------------------------------------------

No. Currently we don't have a feature to avoid this. However, we do relay the first agent reply to everyone that received the original notification so they know the ticket has been picked up. 


If I reply to a ticket from the notification, is it marked answered in the web app?
-----------------------------------------------------------------------------------

Yes. Tickets are moved to the answered section once you reply to them whether from the email notifications or from within the web app.

How do I issue commands via the email
-------------------------------------

You can star, assign, archive and do anything else you are used to doing via our web interface (a complete list of commands follows). You can do all of them simply by cc'ing to the right email address when replying to the ticket email you have received. For example if you want to star a ticket just cc ``star@supbee.com`` in your reply email and it will be starred. As an added bonus, the next time you want to copy a command, your email client should auto-complete it for you.

List of commands
----------------

Issuing a command is super easy. While replying to your ticket email just cc the right @supbee.com email.

* Star a ticket: CC `star@supbee.com`
* Unstar a ticket: CC `unstar@supbee.com`
* Assign yourself to the ticket: CC `assign.me@supbee.com`
* Assign another user to the ticket: CC `assign.name@supbee.com`. You can just use the first name of the user (assign.prateek@supbee.com) or use the full name. If you want to use the full name you can do it this way: assign.Firstname.Lastname@supbee.com (eg. assign.prateek.dayal@supbee.com). You can also use the name of a group (for example assign.tech@supbee.com).
* Archive the ticket: CC `archive@supbee.com`
* Trash the ticket: CC `trash@supbee.com` , if you trash the ticket a reply will not be sent.
* Mark the ticket as spam: CC `spam@supbee.com`, if you mark it as spam a reply will not be sent
* Do not send the reply to the user: CC `noreply@supbee.com`. While a reply is not sent if your reply is empty, using this command a reply will not be sent no matter of the content of the email. We recommend using this if you are using Outlook or another email client that does not stick to any standards for signatures etc.

What about comments?
--------------------

You can comment on your ticket as well. Doing so is very simple, just add your comment inside the square brackets (these: ``[]``) in the ### area of your reply. The ### area is in the quoted part (original message area) of your reply.

Will my customers see any of this?
----------------------------------

Of course not, both comments and commands will *never* and in no way be included in your ticket response. The user will only receive your reply to his ticket. If there is no reply in your message but only commands and/or a comment a response will not be sent. We also handle the case where the only new thing in your reply is your signature (in a standard signature format).

What if I only want to issue a command and not reply to the ticket?
-------------------------------------------------------------------

Again, if your email does not have a response, your user will not receive an empty email. You can just assign the ticket with a cc'd command to someone else and go on with your work.
Notice: In case your email client includes a signature to your email, and your email only has an extra signature, we will still treat your reply as if it was empty. Once again, this might not work for some email clients like Outlook so you can always copy `noreply@supbee.com`.



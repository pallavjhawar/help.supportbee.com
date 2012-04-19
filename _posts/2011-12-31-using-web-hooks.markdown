---
layout: default
title: Using Web Hooks
description: How to create web hooks
categories: web_hooks
---

What are Web Hooks?
-------------------

Web Hooks let us post data directly to your servers whenever something happens that you might want to know about.  

Web Hooks allows you to integrate SuppotBee deeply with your support work flow.  

Whenever an event like 'ticket.created' happens a HTTP POST call is made to an URL provided by you with the data about the event. 

How do I create a Web Hooks?
----------------------------

After you login as an admin,

1. Click on Admin link in the top right corner of the screen
2. Select the 'Web Hooks' tab
3. Click 'Add a New Web Hook'
4. Specify the URL to which the HTTP POST call will be made.
5. Click 'Add Web Hook'

Your web hook would be created and triggered every time an event happens on your help desk.

You can also create web hooks using our [API]()

How do I test/develop Web Hooks?
--------------------------------

You can test/develop your webh ook using the Web hook Console.

After you login as an admin,

1. Click on Admin link in the top right corner of the screen
2. Select the Web Hooks tab
3. Click 'Test Web Hook'
4. Specify the URL to which the HTTP POST call will be made.
5. Specify the event to be triggered
6. Click 'Test'

A HTTP POST request will be made to the URL you have specified with the data corresponding to the event you selected.

What events are currently supported?
------------------------------------

A HTTP POST call will be made to all the web hook URLs registered by you when

1. Ticket is created
2. Customer Reply is created
3. Agent Reply is created
4. Comment is created

How do I delete a Web Hook?
---------------------------

After you login as an admin,

1. Click on Admin link in the top right corner of the screen
2. Select the Web Hooks tab
3. In the listing, find the web hook that you want and click 'Delete'

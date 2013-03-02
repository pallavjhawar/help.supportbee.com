---
layout: default
title: Using Web Hooks
description: How to create web hooks
categories: using.webhooks
---

What are Web Hooks?
-------------------

[Web Hooks](http://www.webhooks.org/) let you push notifications for certain events ( like a new ticket creation ) that happen in your SupportBee to other programs. Coupled with our [API](https://developers.supportbee.com/api), webhooks can help you [automate certain tasks](/features/automation) that involve talking to other services. This push notification is simply an HTTP POST triggered by that event. This call contains data about the event and is made to the URL provided by you.

This feature is intended for businesses that want to integrate SupportBee deeply with their support work-flow.
 

How do I create a Web Hook?
----------------------------

The permission to create and manage webhooks is restricted to the admins in the system. If you are an admin, here's how you can do it:

1.Click on the Admin link in the top right corner of the main page after logging in
2.Choose the 'Web Hooks' tab
3.Click on 'Add a New Web Hook'
4.Specify the URL to which the HTTP POST call has to be made.
5.Click on 'Add Web Hook'

Your web hook will be created and triggered every time the event that you created it for happens in your help desk. You can also create web hooks using our [API](http://developer.supportbee.com/)

How do I test/develop Web Hooks?
--------------------------------

The permission to test or develop webhooks is restricted to the admins in the system. If you are an admin, you can use our webhook console by following the steps below: 

1.Click on the Admin link in the top right corner of the main page after logging in
2.Choose the 'Web Hooks' tab
3.Click on 'Test Web Hook'
4.Specify the URL to which the HTTP POST call has to be made.
5.Specify the event for which the call has to be triggered
6.Click on 'Test'

An HTTP POST request will be made to the URL you have specified along with the data corresponding to the event you selected. The response for the POST call should be a success (HTTP Status Code 200). If the response is a failure, the call will be re-tried 3 times at an interval of an hour. 
You can test/develop your web hook using the Web hook Console.


What events are currently supported?
------------------------------------

An HTTP POST call will be made to all the web hook URLs registered by you for the following events

1.New Ticket creation
2.New Customer Reply creation
3.New Agent Reply creation
4.New Comment creation

How do I delete a Web Hook?
---------------------------

The permission to delete webhooks is restricted to the admins in the system. If you are an admin, here's how you can do it:

1.Click on the Admin link in the top right corner of the screen after logging in
2.Choose the Web Hooks tab
3.In the listing, find the web hook that you want to delete  and click on 'Delete'


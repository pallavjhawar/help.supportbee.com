---
layout: default
title: Contact Support Widget
description: How do setup the contact support widget
categories: widget
---

If you want to collect customer service requests on your website or web product, you should use the contact support widget. It is easy to set it up and it works on desktop, tablets and mobile.

How do I put up the 'Contact Support' Widget on my website?
-----------------------------------------------------------

After logging in as an Admin,

1. Click on 'Admin' link in the top right of the scren
2. Select the 'Widget' tab
3. Select the email address, position and language and copy the code 
4. Put it in your webpage below the </body> tag

How do I hide the 'Contact Support' tab and load the widget on clicking a link?
-------------------------------------------------------------------------------

If you don't want to use our 'Contact Support' tab, you have to edit the code and change position to none,

`position: none`

Then, on your webpage, put up a link (with the text that you want)

`<a data-controls-modal="sb-overlay">Contact Us</a>`

The data-controls-modal property binds the form to this link.

How do I prefill the Name/Email/Subject field? 
----------------------------------------------

If you already know the name or email address of your customer (for example when they are already signed in), you can prefill the contact form with these details. Edit the code to add one or more of these fields when you initialize the form

`name: "Awesome Customer"`
 
`email: "awesome@example.com"`

`subject: "Awesome Question"`

Can I embed the form on my page without using the overlay?
----------------------------------------------------------

Absolutely! You can use the iframe version. Please use the code below and replace _your-subdomain_ with your company's SupportBee subdomain. You can also replace the _locale_ with another supported locale

`<iframe src="https://your-subdomain.supportbee.com/web_tickets/new?embed=true&locale=en" style="width:500px; height: 500px; border:none"></iframe>`


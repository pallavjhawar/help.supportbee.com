---
layout: default
title: Contact Support Widget
description: How do setup the contact support widget
categories: widget
---

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

_position: none_

Then, on your webpage, put up a link (with the text that you want)

_&lt;a data-controls-modal='sb-overlay'&gt;Contact Us&lt;/a&gt;_

The data-controls-modal property binds the form to this link.

How do I prefill the Name/Email/Subject field? 
----------------------------------------------

If you already know the name or email address of your customer (for example when they are already signed in), you can prefill the contact form with these details. Edit the code to add one or more of these fields when you initialize the form

_name: 'Awesome Customer'_
 
_email: 'awesome@example.com'_
 
_subject: 'Awesome Question'_


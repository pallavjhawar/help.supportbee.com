---
layout: default
title: Ticket States
description: What are the different ticket states in SupportBee
categories: handling.tickets
---

{% include setup %}

Answered - Unanswered?
----------------------

Unlike traditional ticekting systems, tickets in SupportBee have only two states - Answered & Unanswered. Also, they can be Unassigned or Assigned to a user or a group.

When you reply to a ticket or archive it, it is marked Answered and it goes off all Unanswered sections. If the customer replies back, it is marked as Unanswered again.

What is the default state of a new ticket?
------------------------------------------

A new ticket by default is Unassigned and Unanswered. However, there are a few exceptions

1. If you [create a filter]({{ BASE_PATH }}/working-with-filters) that when matched assigns the ticket to a user or agent, the ticket would be assigned and not show up in Unassigned screen
2. If you [create a filter]({{ BASE_PATH }}/working-with-filters) that when matched archives the ticket, the ticket would be marked as answered and it will not show up in Unanswered section of any screen. You can still find it in All Tickets

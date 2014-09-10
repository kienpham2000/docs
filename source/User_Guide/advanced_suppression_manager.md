---
title: Advanced Suppression Manager Guide
weight: 50
layout: page
navigation:
  show: true
---

{% info %}
ASM is in Beta and is not currently available for use with our [Marketing Email]({{root_url}}/Marketing_Emails/index.html) tool. 
{% endinfo %}

{% anchor h2 %}
Overview
{% endanchor %}

Advanced Suppression Manager (ASM) gives you the ability to create
groups that represent types of email that you regularly send to your
recipients, for example _receipts_, _social notifications_, and _account
alerts_. You can then give your recipients more control over the types of
emails they want to receive by letting them opt out of messages from a
certain group. This means getting the right messages to your recipient's inbox, resulting in a stronger relationship with your recipients and a better sending reputation.

{% anchor h2 %}
Group Suppressions vs. Global Unsubscribes
{% endanchor %}

Before ASM, when a recipient unsubscribed from emails, it was a global
unsubscribe, meaning that recipient would no longer get any emails at
all, including potentially important emails like password resets. This
is still the default behavior if you do not specify a suppression group
when sending an email.

When using ASM, a recipient clicking an unsubscribe link can choose which groups to unsubscribe from (group suppression) or may choose to opt out of all emails (global unsubscribe).

You can manage your global unsubscribes via the UI under "Global Unsubscribes."

{% anchor h2 %}
Suppression Groups and Categories
{% endanchor %}

While both suppression groups and [categories]({{root_url}}/API_Reference/SMTP_API/categories.html) can represent types of email, they are used for different but complementary purposes. Categories are used to organize emails together for analytics, while suppression groups organize emails together for the purpose of allowing recipients to opt out of receiving those types of emails.

{% anchor h2 %}
Getting Started
{% endanchor %}
After logging in to your SendGrid account, click on the beta invitation banner at the top of the page Once in the beta SendGrid site, click on the clipboard icon on the left navigation bar and select "Advanced Suppression Manager."

From here you can begin creating suppression groups to define the types
of emails for which you would like your recipients to be able to opt
out.

And of course there's [Advanced Suppression Manager API endpoints]({{root_url}}/API_Reference/Web_API_v3/Advanced_Suppression_Manager/index.html) as well.

{% anchor h2 %}
Unsubscribe Links and Email Preferences
{% endanchor %}
---
layout: post
title:  "Marketing Software Creation!"
date:   2023-11-04 01:11:53 -0400
categories: jekyll update
---

### Marketing software
Antonio and I finally had a meeting to describe all the contents for what he wanted from the marketing software. To achieve the goals like viewing if the emails bounce and using the email templates, its probably best to use the Hubspot API. Linking to the hubspot api I was able to connect to all the emails of the current CRM list and get the list of all emails, but will eventually want to add status for alumni vs current students but that might take a long time manually. I should figure out how to automate.

Choosing to reuse Antonios sankey chart to display the visual information for the Hubspot API emails to show where our emails drop off. The API gives the data for sent, bounced, opened, and dropped so it should be a good way to display the information that we get from the chart. 

Using the hubspot API turned out to be more difficult than I thought, the API doesnt allow for email sending, so current workaround might be to both create an email for hubspot so I can view the statistics for the marketing emails, and just send them manually after creating all the information with our custom front-end. Confused on what the goal is with this product is though if all its needed for is to allow ease of access. I believe everything is from and to Hubspot so the API is only useful for so much. 

I'm currently struggling with getting a proper CSRF token with the template that Antonio gave me. He linked a hackathon starter file that already uses Lusca, but reading all the documentation and other aids like Stack Overflow dont help fix the errors. CSRF tokens might be the last thing. 

Its been a few days now but coming back to the project, it looks like they have changed the Hubspot API since the documentation and don't allow free access to the MarketingEmails API so i will no longer have access to the statistics of who bounced and who read each email. I think Im just gonna suggest to Antonio we use hubspot straight up.

I've come across a lot of total problems with the creation of the Email Templating method. I think Hubspot free tools may be enough but it has been a valuable learning experience to work with APIS and learn. 

### Time spent:
- Meeting times: 6 hours
- Email website coding : 15 hours
- total: 21 hours
---
unique-page-id: 14352482
description: How Reply Tracking Works - Marketo Docs - Product Documentation
title: How Reply Tracking Works
---

# How Reply Tracking Works {#how-reply-tracking-works}

How Reply Tracking Works - Marketo Docs - Product Documentation

Reply Tracking is done by looking at a message ID that's in every email you send. Every email contains a unique message ID that allows us to have some of the best reply tracking around.

>[!NOTE]
>
>**Prerequisites**
>
>**Connection with Email Server:** `Sales Connect` `must be connected` `with your inbox so we know when a new reply has arrived. You'll need to have your Sales Connect account` [connected to Gmail](http://docs.marketo.com/x/kYMOAQ) `. If you're using Outlook, we'll need to integrate with your` [ `exchange server`](http://toutapp.com/next#settings/exchange_settings) `.`

If Sales Connect can't track your prospect's reply to your email, it won't be able to stop a campaign based on reply detection or log that reply to Salesforce.  

##### What do we mean any email address can reply? {#howreplytrackingworks-whatdowemeananyemailaddresscanreply?}

`This means that if you email [ `[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#044e6b6a576a6b73444c6b717761577065766f2a676b69) and he responds with [ `[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#dc96b3b28fb2b3ab9c88b4b992b5bbb4a8af8bbda8bfb4f2bfb3b1), we're able to track the reply. Additionally, if you email` [ `[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#f8b29796ab96978fb8b0978d8b9dab8c998a93d69b9795) `and CC` [ `[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#2b4a474a456b4e4548444605484446) `, and Alan writes you back, it will also detect the reply and end the campaign.`
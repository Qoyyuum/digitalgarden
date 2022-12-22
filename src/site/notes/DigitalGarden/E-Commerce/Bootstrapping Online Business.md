---
{"dg-publish":true,"permalink":"/digital-garden/e-commerce/bootstrapping-online-business/"}
---

Start a Business as Cheap as Possible and Scale

# OVERVIEW

This document serves as a proposal and recommendation to anyone who wants to get a working and functioning service to the public without spending too much money. Eventually with enough pre-sales or actual sales of launching a bootstrapped online service, the business/project may consider using paid commercial options with professional support of each service or transition to other services.

# GOALS

1.  To build a bootstrapped technology stack;
    
2.  To gain maximum exposure with minimal operation cost for a startup.
    

# SPECIFICATIONS

As it is understood that business handles virtual seminars/hosted online events that don't happen too frequently, it is safe to use the following technology stack as a start. Each of these are free. Paid options are also available for extra features.

## Jitsi - [https://meet.jit.si](https://meet.jit.si) 

This is an alternative to Zoom or Google Meet. 

TL;DR video: [Jitsi Meet vs Zoom and Google Meet](https://www.youtube.com/watch?v=AgCpsb_KHuM)

### Pros:

-   It allows a way to set up an online meeting with screen sharing and presentation options.
    
-   Participants can join without installing another app/software on any of their devices and can freely join via their browser.
    
-   Participants don't need to register to access but they do need to know that they have the link to the hosted event.
    
-   Can record the event for free and upload the recorded stream to Dropbox (must have Dropbox account).
    
-   Integrate with Google Calendar or Microsoft Calendar is available to schedule meeting URLs.
    

![](https://lh6.googleusercontent.com/sSta7LnNunVFonHYzskFWDuU0nSCk6ADQbiQFz3zgZ9gFEEc7OkoXg7hgxsIQGltaZEpHoJJ1RUZE6TU8asTq3UMrMgrLZHhU1CMYwSF1gA8KPPURjtfO-7ap6Aktq6m9FmjdQz7UOjD7gXA2fVhrUDzdgdqkHhnwp9JxoTqrCqutgor8N277Qbu4je6OA)

### Cons:

-   If recording is enabled and uploaded to Dropbox, keep in mind how much diskspace there is on Dropbox. A general free default is 2GB. Personal experience of recording a stream for roughly 6 hours was 8GB. Else, look into recording the stream directly on the laptop (See below for OBS Studio).
    
-   Can’t make the Jitsi meet link as password protected/private. Once the URL is set, it's open to the public. This can be prevented by creating a custom URL on your own, and privately sending that URL to the registered participants/attendees. If this is not a problem, it should be fine.
    

## Softr Studio - [https://www.softr.io/](https://www.softr.io/) 

Softr Studio is a very quick and easy straight-to-the-point website builder.

Pros:

-   No coding required
    
-   Content is saved to Airtable (see below)
    
-   Site turned into a mobile app instantly.
    
-   Integration to various other services available. [https://www.softr.io/integrations](https://www.softr.io/integrations) 
    

Cons:

-   Limited customization.
    

## FreeNom - [https://www.freenom.com/](https://www.freenom.com/)

A free domain name for a year. Can also be renewed for free but only up to a year, every year.

Pros:

-   It’s free for a year
    

Cons:

-   Have to remind self to renew it 2 weeks before it expires to continue another free year, every year.
    
-   Ending top-level domain names aren’t very attractive and very limited:
    

-   .tk
    
-   .ml
    
-   .gq
    
-   .ga
    
-   .cf
    

-   Have to be creative to make the ending domain name making sense. Example:  
    ![](https://lh5.googleusercontent.com/zhQl3MXJhRthTbgkcQ97FqsPpW9AzCaENp1-vSlpaQ9IEUbF7c6hS9TLnYvgZSur8JCiQBiMsBDXgPLiopSgZvNYejZ-putNRXnf5JIn--7EYzPAvDrop_f0W5tPBwYV1_18a4xiMrnVXOjkwU4r11s0yG__jMLpm05US5ujOcxaC-xoQW3HvuwJX1lGRQ)
    
-   This will be time-consuming to obtain a free domain name through multiple searches (and slow loading response from Freenom servers).
    
-   Not ideal for actual business. Recommended to use the popular top-level domain names like .com or .net, etc. Professional branding is everything. Consider this service for testing purposes.
    
-   Domain name is not secure by default. Can be fixed by routing the domain name to Cloudflare (See below).
    

## Cloudflare - [https://www.cloudflare.com/](https://www.cloudflare.com/)

Cloudflare is where a lot of developers go for free SSL and protection against [DDoS attacks](https://www.youtube.com/watch?v=ilhGh9CEIwM).

Pros:

-   Free SSL
    
-   Free Protection
    

Cons:

-   Some learning curve required to understand how DNS, NameServers and Internet works.
    
-   May need to fiddle the settings a bit to ensure that it either passes through Cloudflare DNS or not.
    

## ImprovMX - [https://improvmx.com/](https://improvmx.com/)

ImprovMX is an email service. Once a domain name is registered (either through FreeNom or other), email service is required to have an email sent from the official domain name or have a customer send an email to the official domain name email address.

Pros:

-   Will send those emails to your personal email
    
-   Will be able to reply emails from the official email address, from your personal email.
    

Cons:

-   Limited to 25 email aliases
    
-   10MB file attachment
    

## Mailchimp - [https://mailchimp.com/](http://eepurl.com/hauwHz)

Mailchimp is a free email marketing service.

Pros:

-   Can create marketing email campaigns
    
-   Can segment email lists
    
-   Can send email broadcasts on a schedule.
    
-   Can send an [automatic email](https://mailchimp.com/help/classic-automation-types/) based on categories/tags.
    

Cons:

-   Limited to store up to 2,000 contacts on the free plan.
    

## OBS Studio - [https://obsproject.com/](https://obsproject.com/)

OBS Studio is a popular tool for twitch streamers/youtubers.

Pros:

-   Has plenty of resources online (youtube especially) on how to use OBS Studio to record events.
    

Cons:

-   A bit of a learning curve.
    

## AirTable - [https://airtable.com/](https://airtable.com/invite/r/eKK2sffC)

AirTable will be used as a database. See pricing for limitations on the free plan: [https://www.airtable.com/pricing](https://www.airtable.com/pricing) 

Pros:

-   Available for up to 5 users accessing AirTable at once
    

Cons:

-   Can only store up to 1,200 records
    

  

## Google Groups - [https://groups.google.com/](https://groups.google.com/)

Quick and easy group mail that allows multiple users to share the same inbox. Customers can send in their query and all subscribed users that have access to a Google group mail will receive that email. It can be as easy as setting up a support email address and let customers know where to send their info query.

Pros:

-   Free.
    
-   Secured by Google.
    
-   Can hold as many users as you want at no additional cost.
    

Cons:

-   Data is stored at Google. Won’t be able to export all data in
    

# Operations

Operation flow would look like this after signing up to each service above and connected.

## Customer Story for Live Event Hosting/Management

1.  Business posts a new Instagram post (potentially easier with [Meta Business Suite](https://business.facebook.com/) app ([Android](https://play.google.com/store/apps/details?id=com.facebook.pages.app&hl=en_US&gl=US) | [iOS](https://apps.apple.com/us/app/meta-business-suite/id514643583)) for scheduled posts). And cross-post to Facebook Page.
    
2.  A customer discovers the Instagram post or Facebook page. Navigates to Instagram’s Bio link or Facebook’s content link.
    
3.  Gets directed to the business website (powered by Softr Studio).
    
4.  Browse through all of the events and sees a Form.
    
5.  Customer fills the form. Data gets saved into AirTable. Data submitted is also copied to Mailchimp and tagged as “Pending Invoice” for example. 
    
6.  Mailchimp automatically sends an email instructing how to make payment (bank transfers will be the current go-to or have them CDM the money to an account number, then send a screenshot to a whatsapp number or email).
    
7.  Business staff verifies payment for each customer. Change the customer’s tag/category as “Pending join event” for example.
    
8.  Business staff creates a specific URL on Jitsi and sends an email to those tagged as “Pending join event” with details of when the event will take place and instructions on how to join said event.
    
9.  Before starting the scheduled event, check laptop storage or dropbox storage for enough disk space, else free up disk space (move it to an external hard disk) before recording. Test audio and video. Then start the event.
    
10.  Record the stream.
    
11.  Ask customers for referrals for the next event.
    
12.  Repeat.
    

# Total Cost

Free. None of the above will cost anything except the time to set them up and connect them altogether. If getting that free domain name is too difficult via Freenom, please consider namecheap.com as a proper alternative.

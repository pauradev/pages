---
title: 'Integrate with Woocommerce - Updated for Printaura Plugin V4.0.1'
media_order: 'woo.jpg,woo2.PNG,woo4.PNG,woo5.PNG,woo6.PNG,woo8.PNG,woo7.PNG,woo3.PNG,woo9.PNG,woo10.PNG,woo1.PNG'
published: true
date: '29-01-2019 19:36'
publish_date: '29-01-2019 11:59'
taxonomy:
    category:
        - tutorial
hide_git_sync_repo_link: true
external_links:
    process: true
    target: _self
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
hide_from_post_list: false
content:
    items: '- ''@self.children'''
    limit: '5'
    order:
        by: date
        dir: desc
    pagination: '1'
    url_taxonomy_filters: '1'
bricklayer_layout: '1'
display_post_summary:
    enabled: '0'
author: denise
post_id: 9693944
comment_status: open
post_name: understanding-white-label-branding-your-products
status: publish
---

[![](woo.jpg)](/blog/tutorials/integrate-with-woocommerce)

#### __**Having trouble setting up Woocomerce?**__ 

Please Take a look through this handy guide that details the installation steps and trouble shoots some common problems you may have. This article is for you is you have previously tried to setup a store but can't get orders to go through, orders were working but aren't now or if you went through the installation guide and are still having problems. 
 
===

---
>#### Step 1:
Logon to your PrintAura account and navigate to My Stores > Woocommerce Shops.
Click the link titled "click here" to begin.

---
![](woo1.PNG)

---
>#### Step 2:
Under the field "Woocommerce Shop" enter the URL of your Woocommerce store it the text block, starting with "http://" or "https://". Do not click install yet.

---
![](woo2.PNG)

---
>#### Step 3:
In a new tab go to your Woocommerce Store Admin panel and navigate to Plugins > Add New. In the search box type 'Printaura'. The Printaura-Woocomerce plugin will show up. Install and activate it.

---
![](woo11@3x.jpg)

---
>#### Step 4:
Return to the Woocommerce Store Installation tab.
Click Install to continue.**
You will be directed to your Woocommerce Shop. You will be asked to connect with PrintAura, simply click approve to let PrintAura setup your Woocommerce Store and begin setting up products.

---
![](woo3.PNG)

---
#### __**Troubleshooting**__
___
Depending on the version of Woocommerce and word press you are using you may have to enable legacy webhooks complete the following actions if you are able to see orders in Woocommerce but are unable to view them in PrintAura*
___
>#### Navigate to Webhooks
Navigate to Woocommerce > Settings > Advanced > Webhooks

___
![](woo5.PNG)

---
>#### Select each installed Webhook
In the Webhooks menu edit both PrintAura Webhooks one at a time.

---
![](woo6.PNG)

___
>#### Select Legacy API v3
In the "Webhook data" menu select "Legacy API v3" and click save. Do this for both webhooks.

___
![](woo7.PNG)

---
#### __**Re-Link**__ 

---

##### If you are still unable to view woocommerce orders on the printaura site the links between the site may be broken. to re-generate new links please follow the rest of the trouble shooting walkthrough to remove and re-install your Woocommerce shop on PrintAura.

---
> #### Delete Webhooks    
In the Woocommerce > Settings > Advanced "Webhooks" menu, described above, select all webhooks and Apply the "Delete permanently" action.

---
![](woo9.PNG)

---
>#### Delete API Keys
Navigate to the "REST API" tab select all API Keys and apply the "Revoke" Action.

---
![](woo10.PNG)

---
>#### Remove Shop on PrintAura My Shops
In your PrintAura My Shops > Woocommerce Shops select the remove action to uninstall the current shop.

---
![](woo8.PNG)

---
>#### Clear Cookies and Cache
At this point clear your browser cookies and cache from the browser settings menu.

* [Chrome](https://support.google.com/accounts/answer/9098093?co=GENIE.Platform=Desktop&hl=en&visit_id=636843775705401342-2310875799&rd=1)
* [FireFox](https://support.mozilla.org/en-US/kb/clear-cookies-and-site-data-firefox)
* [Netscape](http://www.allaboutcookies.org/manage-cookies/netscape-6-plus.html)

___
>#### Relink Shop

**To Relink follow steps 1-5 and if necessary the steps outlined in trouble shooting to relink your store.** 

---
---
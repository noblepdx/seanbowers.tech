---
title: "Nextcloud Woes"
date: 2022-11-19T15:13:02-08:00
draft: false
tags: ['tech', 'cloud'] 
---

So a number of years back, I realized that Google took up way too much of the cloud-based digital real estate in my life and the lives of everybody around me. Now, I feel that I have to stress that I am *not* anti-Google. While I loathe a number of business and tech practices of Google, as well as their parent company Alphabet, I must admit that they have made extraordinary progress in tech since their advent as a goofy-named search engine. And a lot of what they create is really well constructed. But with that progress came oversaturation and wide spread use. With the world becoming overly dependant on their seemingly free resources, coupled with their terrifying implementation of data mining, they were quickly collecting mass amounts of data from every connected person. This sort of centralization of the world's data, coupled with the capacity to analyze and predict human behavior through machine learning has wide-reaching implications of ethical issues far surpassing our outmoded simple human understanding to date. This had me searching frantically for a new solution. 

Enter: [Nextcloud](https://nextcloud.com/).

Nextcloud describes themselves as a suite of client-server software for creating and using file hosting services. In the beginning, for me, it was just an open source alternative to the Google, Apple, & Microsoft ecosystems, and chance at having more control over my data. I had a slight fraction of the knowledge and experience than I do now, so my best option at the time was to pay one of Nextcloud's hosting providers to host my cloud storage for me. However, this came with none of the extensibility that had initially drawn me to Nextcloud. But being excited to just wrestle some control away from Big Tech was enough for me for a number of years. But as I upskilled and learned more, I was slowly becoming more and more willing to self-host. I was waiting for the opportunity to host on my own physical server that time and funding just never gave me the chance to build.

So last week I decided it was finally time to move toward having even more control. So I got an Ubuntu 22.04.1 server through [Linode](https://www.linode.com/). I bought a domain for ease of use,set up [PHP](https://www.php.net/) and [Apache2](https://httpd.apache.org/), configured the server, setup Nextcloud, did a little debugging, and even went ahead and got the [LetsEncrypt](https://letsencrypt.org/) certificate. This was my first time doing anything like this, and as I was following Nextcloud's documentation for setup, it felt like I was defusing a bomb the whole time. But in an hours time, I successfully set everything up. 

This was a long overdue, and now I look forward to seeing where my new found freedom, and quickly growing skill set will take me.  

---
layout: post
title:  "Nulled WordPress Themes and Plugins"
date:   2018-08-01 18:41:47 -0700
categories: WordPress
---
## Introduction

Nulled WordPress themes and plugins can be tempting. After all, why pay for a GPL2 licensed product if you can get it for free. If the people who make the plugins want money, maybe they should get a real job! WordPress is a free platform, therefore everything on it should be free as well!

If the preceding paragraph sounds like you, keep reading. Nulled WordPress themes and plugins are not a good thing for your website and I'll tell you why. I'm not going to repeat what others have said about the subject, I'm only going to cite my own research.

## My Experiment

I downloaded a nulled copy of the hugely popular and highly recommended SEO plugin Yoast. It's $89 regular price. Seems like a good bargain to get it for free.

Now, I'd read that nulled WordPress themes and plugins can be home to trojans and worms so I uploaded my copy of nulled Yoast to VirusTotal. The analysis came back clean. The uploader didn't load the plugin with worms and trojans; maybe I'd found a gem!

I'm not stupid though ... I didn't immediately go to my production website and load up my nulled Yoast plugin. First, I loaded it in my XAMPP test environment after backing everything up.

Exploit Scanner is a tool published by Automattic, the developers behind Jetpack, WooCommerce and a load of other plugins. While the plugin hasn't been updated in over a year, the exploits that nulled plugin distributors employ don't seem to have evolved much either, according to my research.

This is where things started to get interesting. According to Exploit Scanner, the plugin had many instances of the PHP function base64_decode. This function is used legitimately sometimes, but most of the time it shows up in nulled plugins and it's used to steal your data. Therefore, I nuked my test environment and started over ... good thing that installing WordPress is a trivial amount of work!

## Conclusion

If I had installed the nulled plugin on my production site, who knows how I would have been affected ... I probably would be cleaning an infected website up and not writing a blog post about why you shouldn't use nulled WordPress themes and plugins. Or worse, I wouldn't notice a thing and my site would be stealing my data from me.

It's not perfect logic to steal from the developers who make the themes and plugins we love because there are free versions available for most of them and there's always an alternative to using a paid theme or plugin. If you want to use a paid plugin, pay for it. Supposing you don't, it's possible that the plugin developers will stop making their superb tools and do something else with their time.

If you decide to use nulled WordPress themes and plugins, be prepared to do an equal amount of work to the amount of money you've saved by employing pirated software on your WordPress site because cleaning an infected WordPress installation is time consuming due to the many places infections can hide. In fact, it can be so challenging that you might have to hire someone to do it for you.

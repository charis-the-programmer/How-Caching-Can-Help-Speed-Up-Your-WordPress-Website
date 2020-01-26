# How Caching Can Speed Up Your WordPress Website

In this article I will explain how you can make us of caching to efficiently optimize and improve the speed of your WordPress website. Now, in order for you to fully appreciate the concept of caching, let us first look at the growing importance of your website’s load speed.

## Importance of a Fast Website

The goal of every business or site owner is to deliver a great user experience. Here are a few factors to consider that are affected by the speed of your website:

### User Retention

Nowadays, because of the increasing reliability in technology performance, web users have come to expect faster page loads.When a user visits your site and the overall site performance is low, you risk losing that user.The attention span from the user is increasing getting shorter and shorter, which means just a few seconds can literally make the difference between keeping visitors on your website or driving traffic them away at an alarming rate.
In those few seconds you are able to convince your visitor whether your website is worthy of their valuable time or not. So, if your web site loads faster you have a good chance at retaining the current users as well as impress new visitors. 

### Search Engine Ranking 

There are a lot of factors that go into where your webpage will ultimately appear on the search results page, and quite recently speed has become a top factor among others.Top search engines like Google considers this factor under what is known as “usability metrics” and it is significant to the search rank bots that determine your website’s search rank. If your website is running on WordPress, it is important that you focus on choosing a reliable web hosting partner.
 
> Tip: Check out managed WordPress Hosting because their services are well optimized for speed.

With that said, maintaining a page load score of 80or better is crucial for reaching the top of the search engine ladder.

### Sales and Conversions

For every online business, converting browsers to buyers and visitors tofollowers is a very important metric. Now, if your site loads slow and it drives people away, then that means it also drives your sales away.

> A test was conducted at Amazon and it revealed that every 100-microsecond increase in load timetranslates into a 1 percent decrease in sales.Furthermore, it went on to show that they would potentially lose $1.6 BILLION every year if their website slowed down by just one second.

This research makes it difficult to ignore the need for speed. Therefore, it is extremely important to try to achieve the fastest page load time as much as possible, so that conversion percentages begin to increase and bounce rates to decrease.

### General Web Statistics

The following statistics are from [MOZ](https://moz.com/blog/site-speed-are-you-fast-doesit-matter) and they give a general guideline of how your website load speeds compare to other sites on the web. 

* 5 second load time: faster than 25% of websites
* 2.9 seconds load time: faster than 50% of websites
* 1.7 seconds load time: faster than 75% of websites
* 0.08 seconds load time: faster than 94% of websites

If you want to measure your website’s load speeds you can use any of the following tools [GTmetrix](www.gmetrix.net), [Pingdom](www.pingdom.com) or [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/). At this point we can now look at what is caching and how it can speed up your WordPress website. 

## What Is Caching 

From its definition, caching is a temporary storage of data that is frequentlyaccessed on a website so as to allow for quick and easy retrieval of that data. By using caching your website can avoid taking longer trips when fetching your data throughout the internet. Instead your site reuses the data from your website that is tapped into on a regular basisin order to save time.

### Caching Basics

The way caching works can be better understood if we first understand what happens when a web user visits your website.
When a user types in your website’s address and presses enter, the user’s browser first requests your web server in for your website.  The WordPress site then contacts the host (which is on some other computer, possibly far, far away) using specialized PHP code. The host then accesses the main database (usually MySQL) where all of your website’s content is stored. This database then takes that request, compiles it into a readable HTML page, and then sends it back to your browser where the user can actively see it.
Now, the problem with this process is that it can potentially take a long time to retrieve the visitor’s information thus slowing down the speed of your website. That is where caching comes into play.
Caching helps to increase you WordPress site’s speed in several ways, for example by creating static, or unchanging, HTML files and saving them for reuse later. Cachinghelps to avoid delays in retrieving information to your visitors, decreases server load and lowers the bandwidth used.
There are different kinds of Caching but for our purposes, we are going to look at just two: namely Browser and WordPress Caching.

### Browser Caching



In this kind of caching web browsers download HTML files on a given website and keep them in a local cache. When theuser requeststo visit the site again, the browser simply enquires from your WordPress server whether the files being requested have changed since they were lastdownloaded. If the files haven’t been changed, the web browser simply retrieves the information from the local cached copy.
The perfect files to be cached on your site are your basic images, headers, footers, and sidebars because they are static, which means the usually remain unchanged. Browser Caching will help to decrease your site’s load time and reduce the overall burden on your server by reducing the number of requests per page.

### WordPress Caching

![Wordpress Caching Picture](images/wordpress-caching.jpg "Wordpress Caching")


This type of caching uses a caching plugin which is configured on your WordPress server. Essentially, when using a caching plugin, HTML pages are saved entirely in the cache where they are already constructed and quickly deliverable rather than trying to retrieve parts of the website stored on different parts in the main database.
There are different ways in which you can customize your chosen plugin to meet your site’s requirements. An example would be to configure the caching plugin to save popular query results on you site such as “About Us” and “Contact” pages. That way when a user visits your site, the cache holds the results of these queries and provides them to the reader quickly and efficiently.
Caching works for dynamic, or ever-changing files as well. Using your caching plugin, there is an option to set an expiration date which tells your cache storage that for that set amount of time e.g. 1 week that particular file will remain unchanged, therefore it is safe to cache and use for future requests. In this way your cache can refresh itself after the expiration date passes and update its contents; displaying the new and relevant information as quickly as possible to your users. 
There are several different choices when it comes to deciding which caching plugin to use on your WordPress site. We will now take a look at a few popular caching plugins for WordPress.

## Wordpress Caching Plugins

### W3 Total Cache 

![W3 Total Cache Logo](images/w3-total-cache.jpg "W3 Total Cache Logo")

W3Total Cache plugin is one of the most popular free caching plugins for WordPress. It has over a million active installs and a user review rating of 4.3 out of 5 stars.  It is frequently updated and is used many major sites such as Mashable, GoDaddy, and AT&T.W3Total Cache Plugin boosts your overall site performance by 10 times and saves 80% bandwidth. It caches browsers, pages, objects, databases, feeds, search results, and much more. You can easily set expiration dates for each type of caching your website employs. The plugin has 16 individual pages of configuration choices but luckily, its default settings are fairly optimal and easy to access. For more information about this plugin visit [W3 Total Cache plugin](https://wordpress.org/plugins/w3-total-cache/)


## WP Super Cache Plugin 

![WP Super Cache Logo](images/wp-super-cache.png "WP Super Cache Logo")

WP Super Cache is another highly popular free caching plugin for WordPress. WP Super Cache has over two million active installs and a user rating of 4.2 out of 5 stars. It is highly effective at keeping your server from slowing or even overloading during the large traffic spikes that can.This plugin is simple and the recommended settings are easy to configure and set up. For more information about this plugin visit [WP Super Cache Plugin](https://wordpress.org/plugins/wp-super-cache/)

### WP Rocket

![WP Rocket Logo](images/wp-rocket.png "WP Rocket Logo")

WP Rocket is one popular premium caching plugin for WordPress websites. It is currently installed on over 100,000 websites. One of its key selling points is that it is one of the easiest caching plugins you can use on your website. Therefore if you want a faster website, and don’t mind paying a little extra for that convenience, then WP rocket is the best choice for you. For more information about WP Rocket visit [WP Rocket](http://wp-rocket.me/)

Other note worthy caching Plugins for WordPress include: [WP Fastest Cache](https://wordpress.org/plugins/wp-fastest-cache/),  [Hyper Cache](https://wordpress.org/plugins/hyper-cache/), [Comet Cache](https://wordpress.org/plugins/comet-cache/),  [Cachify](https://wordpress.org/plugins/cachify/),  [Simple Cache](https://wordpress.org/plugins/simple-cache/)

A performance test was conducted among these top caching plugins and the results can be found at [best performing plugin article](https://athemes.com/performance/best-wordpress-caching-plugins/).  

## Conclusion

Overall, all caching plugins improve your website’s load speed but however it is important to note that different websites might require a different variety of caching. Therefore try out a few of the available options mentioned above and test them one at a time. You can use tools like [GTmetrix](www.gmetrix.net), [Pingdom](www.pingdom.com) or [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) to conduct your own tests and find out which caching plugin works best for you. 

## References

* WordPress Plugins - [WordPress Website](https://wordpress.org/plugins/)
 


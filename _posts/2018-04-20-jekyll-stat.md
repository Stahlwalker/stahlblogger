---
title: Jekyll Static Blogs
date: 2018-04-23 15:30
image: https://ymatuhin.ru/assets/img/jekyll/jekyll-logo.png
lead: "Benefits of using static blog posts through Jekyll." 
subtitle: Tips for building a blog using Jekyll.
tags: footer privacy 
---
#### Experience with the terminal is a must:
 
I had prior experience with blog sites, such as Blogger and WordPress, but the recent launch of ![Stahlwalker.org]( https://stahlwalker.org/) was my first attempt and creating a blog from scratch and Jekyll worked great. Tips to know before attempting to use Jekyll.

* Be familiar with the command line as you will use it to run your server and if you don’t have ruby gems install on your computer will have to do so. After Jekyll is installed there are a number of tutorials on YouTube that can help guide you through, but the one that I found to be the most helpful is on Udemy, called Jekyll: make fast, secure sties and blogs with Jekyll. This course has 29 lectures under 3 hours of material and afterwards you will have a working Jekyll blog. 

* Have a GitHub account. One of the best features with Jekyll is its integration with GitHub. Since, Jekyll works with GitHub you can publish your blog for free instead of going through Digital Ocean, Amazon S3, or Heroku. 

* Additionally, Cloudflare works with GitHub and Jekyll pages in order to help make domains secure. Creating an account with Cloudflare and then changing the DNS of the custom domain that you purchased to reflect GitHub can turn any “Username.github.io/appName” into a secure website. I spent a lot of time looking into SSL keys through Digital Ocean and Let’s Encrypt only to find this capability with Cloudflare. The best part about it, it’s free. With Digital Ocean, I was creating droplets that would charge roughly 10 cents a day on top of a $5 a month fee.  It also required way more knowledge of the command line because it integrated Nginx, but that is a tale for another time. Long story short, Cloudflare integrated with GitHub and Jekyll can help build advance your blog past the initial publishing GitHub has to offer. Sure, there are ways of publishing with a CNAME on GitHub, however you’ll notice your site isn’t secure and you have an “!” prior to your URL. With the way web servers are cracking down on sites that are not secure, it’s important to make sure yours is from the beginning. Imagine all your hard work to build a blog site and publish 2-3 years’ worth of content only for you to have to either shut it down or purchase an SSL Key for $75 a year. Save yourself the hassle and get it through Cloudflare, protect your site right out of the gates. ![Some Title]( https://lesniakswann.com/app/uploads/2017/01/more-secure-1920x700.jpg){:style="float: left;margin-left: 7px;margin-top: 7px; position: relative"}{:class="img-responsive"}

Here are couple links to help get you started on creating your first Jekyll Blog.
[Jekyll Install and Walkthrough]( https://jekyllrb.com/)
[Github](https://github.com/)
[Cloudflare]( https://www.cloudflare.com/)
[Udemy Jekyll Tutorial](https://www.udemy.com/static-website-generator-fast-secure-sites-blogs-with-jekyll/learn/v4/overview)

I hope this was helpful and feel free to comment with suggestions or questions.  

- **<span style="color:rgb(254, 57, 30)">-Man of Stahl</span>**

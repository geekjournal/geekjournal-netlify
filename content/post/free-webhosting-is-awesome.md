---
title: "Free Webhosting Is AWESOME!"
date: 2018-01-08T23:19:19-06:00
---

It's true. I've been squatting on several domain names for a while, including this one, which means I've been a bad internet citizen.  I hope to correct that in 2018 starting with this post. 

One of the items blocking me from doing something with my internet properties sooner is that it costs money to host custom web content.  At least, that's how it used to be!  I don't need dynamic content (no database hosting)... I just need a place to serve static HTML.  Last year, \_bam!\_, I learned about Github Pages.  This is exactly what I was looking for.  This would allow me to create a site using simple HTML, or better yet use a static site generator (like Jekyll or Hugo), and host my site for free on Github.  I could even point my custom domain name to the site.  Other nice goodies include version control, the ability to collaborate with others, and nifty features like a web-based editor if I need to change something on the go.  I was ready to hit the ground running... and then, my twins were born.  Sleepless nights would keep me from doing anything until now. 

Fast forward to just recently, and as I redid my search for static site generators and Github web hosting, I learned about Hugo and Netlify.  Hugo is similar to Jeklly, but appears to be lighter weight, templating made more sense to me immediately, and should I ever need to mess with the code it is in Go vs. Ruby (not that anything is wrong with Ruby, Go is just becoming more popular). 

The real magic for me was Netlify.  I have tech skills, but I'm also a pointy-haired manager type, so I don't practice my computer engineering kung-fu as often as most of you.  Setting up a Github page, while super simple in tech terms, still always felt slightly labored.  Netlify made things super simple!  `hugo ; netlify deploy` after some very minor setup on Netlify's website.  Netlify walked me through the entire setup of custom domain name records, CI/CD integration (including pull request preview) for my domain, and their documentation is SPOT on.  I never even had to think about getting hung up on a step, as their documentation was concise yet dead-on.  Kudos to whoever writes their docs!  Actually, I don't ever need to `netlify deploy` anymore.  All I do is write a post in Markdown, then `git push -u origin master`.  BAM!!

If you are a techie looking for a way to start a blog or host a static website, checkout Netlify (and Hugo -- or Jekyll).  You'll be glad you did. 

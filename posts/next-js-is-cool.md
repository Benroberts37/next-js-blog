---
title: 'Why Next.js is really cool'
date: '2022-07-20'
---

I recently started learning about Next.js and going through their intro course on how to use Next.js and Vercel. There are tons of really cool benefits of using Next.js and I wanted to list some of my favorites. 

First, your app can be blazing fast thanks to pre-rendering and static site generation. If the content on your site doesn't have to update super often (such as a blog, e-commerce site, restaurant menu, etc), then, by default, Next.js will pre-render the pages on your site. This means that the pages have basically already been rendered on other servers such as a CDN network, and now it just shows up extremely fast when a user hits your site.

Another benefit to pre-rendering is the SEO advantages. React isn't great for SEO because the content on your site doesn't render until a user request it. With Next.js, you can pre-render which means web crawlers can access the content on  your site and use that for SEO.

The pages routing is also very cool an intuitive. Anything inside of your pages directory automatically becomes available as a route on your app. Files named index will route to the root of the directory. You can also create nested routes and files will automatically be routed the same way as the file structure. You can lso create dynamic routes using bracket syntax. To me, this form of routing is very intuitive and fun to use once you figure it out. 

I also thought the way that Next.js handles global vs component level CSS is really cool. The auto-generation of class names to avoid class collisions is super cool. I have always worried about potentially naming a class the same as another class in my app, so this takes away that worry.

The fast refresh is also super cool while building and testing your app. The fact that it keeps your current state is very helpful and allows for quick testing and debugging while your are building out new pages or features in your app. 

Next.js has more capabilities but these are some of the things I learned my first day learning Next.js. It seems like a great fit for a lot of businesses that are looking to provide a super fast and positive user experience, and want great SEO. 
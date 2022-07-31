---
Title: "How my website works"
date: 2022-06-18
draft: false
tags: ["this site"]
description: "(almost) all the tools that power my website"
---

I've been meaning to do this post for a while, so here it is.

## The base site

The site itself is made with [hugo](https://gohugo.io). It's a really cool static site generator that lets me write posts in markdown. I write my post, plop it in `/content/posts/whatever.md`, run `hugo`, and the site gets built into `/public` in less than a second.

I can even run `hugo serve --navigateToChanged` and it will host my site on localhost port 1313, rebuilding every time I save a file, and redirect my already open window to whatever page was saved last. Totally beats using wordpress.

### The theme

I use the hugo theme [coder](https://github.com/luizdepra/hugo-coder/). It's a nice minimalist theme that has everything I need.

## Comments

So this is really cool, in my opinion. Comments on blog posts are done with a platform called [utterances](https://utteranc.es). While a normal comments solution would just store the comments in a database, utterances converts them into github issues. This was it is 100% free. You can see all of the comments/issues on [my site's github repo](https://github.com/mrhappyma/userexedotme/issues?q=label%3A%22on-site+comments%22+).

## Hosting the site itself

The site is hosted by [Netlify](netlify.com/) on their free tier. I just commit my changes to [my site's github repo](https://github.com/mrhappyma/userexedotme), and Netlify automatically deploys my site in like half a minute. It's insane.

Netlify also deploys a preview of any PRs made, so I don't have to clone the repo and deal with build it locally to get a feal for what the PR looks like.

## The contact form

My site's [contact form](/contact) is powered by [Netlify forms](https://www.netlify.com/products/forms/). It takes responses and sends them to a private channel in my Discord server. Pretty cool, not too much more to be said about that.

## Conclusion third heading here

Yep, there it is. How I made my site for free and pretty much without coding everything because I don't know html and css and all that stuff. Yay, hooray, **the end.**

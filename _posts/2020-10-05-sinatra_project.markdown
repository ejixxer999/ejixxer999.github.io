---
layout: post
title:      "Sinatra Project "
date:       2020-10-06 02:19:46 +0000
permalink:  sinatra_project
---


The title for my sinatra project is Car_Blog. the purpose of my build is to bring a community of car enthusiast together by allowing them to write blogs about their favorite cars. Also it is to bring non- car enthusiast to a place where they can learn more about cars. Usig sinatra I was able to make a website that can create new author accounts, allow each author to create a blog post, and allow other authors to view blog posts made by other authors without having the ability to edit or delete the post from the site. In my opinion, building the security for each authors blog post was the most intersting parts. For someone who has never done this before having that level of authentication was tricky to think about but thanks to active record majority of the code can be simplified.  Being able to authenticate an author and assigning the blog post to that author using a belongs_to relation played a big part in securing the posts published, and using active record made it very simple. The active record library allowed for this site to be built with easy with many of its short cuts and simple methods that are pre programmed into its gem. Helper methods also simplified a lot of my code because I was able to assign reoccurring code to a helper method, and call on the method when the time came. the most challenging part of this project was building the destroy function, or delete button. This part in CRUD may seem as the easiest to do but for a beginner it wasn't. eventually understanding how a post form works,  using method paird with Rack::MethodOverride, and the abilities of rack in general made building a destory button alot eaiser. All in all what we have here is a functioning blog website where car lovers, and non-car lovers can share a space and discuss a similar interest. 

Please enjoy Car_Blog!

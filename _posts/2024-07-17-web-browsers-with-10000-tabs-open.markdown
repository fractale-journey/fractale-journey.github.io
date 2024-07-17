---
layout: post
title:  "Web browsers should support 10,000 tabs open"
---

# TL;DR

Modern web browsers struggle with performance issues when too many tabs are open, forcing users to close tabs and lose their workflow.
While solutions like tab suspension and tab groups exist, they aren't sufficient.
A better approach would treat unused tabs more like bookmarks.
This would allow users to open thousands of tabs without performance issues.
This user-centric approach would greatly enhance productivity and exploration on the internet.
Let's push for browsers to adopt this more efficient tab paradigm.

# The problem

Creativity and life in general are messy, when exploring ideas you always explore one thing, then another, then come back to the original idea with a slightly different angle.
You also prepare your next vacation after work, do a Gamejam on the weekend, and find articles you want to read on the way back to work.
If you are like me, you have a thousand tasks and ideas that you are currently exploring and one web browser to do all of them.
But here is the problem, mainstream web browsers support a limited number of tabs open at the same time before becoming extremely slow or even unusable,
forcing you to close tabs and new ideas when life makes you switch tasks. That temple you maybe wanted to go on your next vacation is now gone because you need to free some tabs for work!

# The current solution

Web browsers have started to realize the user's need for a large number of tabs, many web browsers offer Tab Groups and a way to search open tabs.

There are also, many extremely popular extensions that "suspend tabs" allowing you to increase the limit of open tabs at the same time.

You can use a lot of services to add "for later" and you can always bookmark all open tabs in a folder with the date and continue exploring.

I would like to mention the best multi-platform/browsers I have found so far: OneTab.
It is similar to bookmarking all the currently open tabs in a folder with the date but do this in its own list.
I like the separation between my bookmarks (organized and selected website) and my search and creative process.

But you might realize that all of this is managing a list of previously open tabs because our "modern web browsers" can't have a lot of tabs open at the same time. 

# A better Solution

You can have 100,000 bookmarks in a web browser without any issue but you can't have a lot of tabs open, why?

Modern web browsers have the wrong approach when it comes to the concept of what a tab is.
They consider a tab to be a fully rendered webpage that needs to be in RAM at all times and execute code in the background, but I believe this is the wrong approach.
All tabs have a usage history and tabs that are no longer visited can be "suspended".
Their content and state will be saved to disk, this greatly increases the number of tabs that can be opened at the small cost of waiting for disk read when the user clicks back to a suspended tab.
But SSD has been so cheap and fast, this is a small tradeoff for a lot of browsing comfort.
A lot of modern web browsers rely on extensions for this but others have realized how important it is for users and include this now by default.

But I think Web browsers need to push this concept further. 
Most websites can have their state recreated by just downloading again the webpage at the same URL and scrolling back to the right paragraph.
For those websites that have dynamic content like Facebook, Instagram, TikTok, Reddit, or Hackernews, only the main feed is dynamic and I don't expect to see the exact same page when I click on my Facebook tab if I haven't clicked on any photo (that would change the URL) if it's been a week I haven't click there.

Therefore, tabs can be just a URL like a bookmark when the tab usage history is low and the suspended approach starts to show its limit.

# Conclusion

I think the users should have the possibility to open as many tabs as they want and that the browser should serve the user.

I don't think there should be a "proper way" to use a web browser that comes from its historical and current limitations.

I'm glad modern web browsers have started to integrate the suspended tabs feature and that many developers have written extensions to solve this issue.

But I think it is time for a more elegant solution and I hope to see a web browser able to open 10,000 tabs soon because men need to explore ideas and not be limited by how much RAM they have.

If you would like to see this reality happen too, I encourage you to share this post with others, because the internet is the modern way to spread ideas.

Good luck with your internet exploration!

Fractale

---
title: "Goodreads shutters all APIs, breaking my open source app"
subtitle: "Some subtitle"
date: 2020-12-10T13:30:58-07:00
draft: true
featured_image: "/yonderbook_logo.png"
tags:
- ruby
- yonderbook
- Goodreads
---


Last night I got a very bad, no good email from [Goodreads](https://goodreads.com).

![Goodreads email to me](/goodreads_email.png)

It read:

> Your Goodreads developer API key has been deactivated
>
> Goodreads has deactivated the Goodreads developer API key associated with your Goodreads account as it has not been used in more than 30 days. As of December 8th 2020, Goodreads will no longer issue new developer keys for our public developer API and plans to retire these tools.

I launched an app called [Yonderbook](https://yonderbook.com) in 2016. It is completely dependent on the Goodreads API as an auth provider and data source.

In the last four years, over 4,792 people have used Yonderbook. They've analyzed reading habits, downloaded books to read, and swapped hardbacks with other readers.

In 2013, [Amazon bought Goodreads](https://www.theguardian.com/books/2013/apr/02/amazon-purchase-goodreads-stuns-book-industry) Many in the reader community were worried about what Amazon would do with its new acquisition, but they retained the status quo for a while. Until now, apparently.

They've given notice that they will shut down their APIs, effectively shutting down outside interaction with Goodreads data. In addition, the developer terms and conditions don't allow storing of any Goodreads data, so users won't be able to pull their data from Goodreads for use in other arenas.

Now, I'm pondering the future of Yonderbook. Over the years, I've had a ton of fun talking with users and developing new features. It's sad that Amazon has made this decision, although not surprising, given their company ethos. But I'm glad to have been able to make a useful tool to help readers on their journey.

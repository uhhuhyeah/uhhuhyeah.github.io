---
title: "Do you know what problem you are trying to solve?"
date: 2016-02-12 09:00:00 -7000
layout: post
author: David A McClain
published: true
location: "San Francisco, CA"
author_url: 'http://linkedin.com/in/davidamcclain'
original_url: 'http://multithreaded.stitchfix.com/blog/2016/02/12/do-you-know-what-problem-you-are-trying-to-solve'
---

{% include stitchfix.html %}

This is a story I will one day tell my grandchildren. But as I have no grandchildren, you, dear reader, will have to do. Now sit down, pop this hard candy in your mouth and look interested.

The year was 2016. The first non-Terran President was something few of us had dreamed of, cars were still mostly driven by humans, email was still a thing (though it was on our wrists by now) and software was still being written. Yep! By fallible humans working with clicky keyboards and screens on desks.

At Stitch Fix I worked with the Merchandise (meaning clothing) team supporting the types of things a Merchandise team did at a fashion company, like placing Purchase Orders with Vendors. I was asked by one of the Buying Directors, Amanda, to give her insight into Purchase Order changes. "I want to know how many times a Purchase Order was revised."

If I had built what she had asked for, I would have given her something like a history view so that she could pick any Purchase Order and see a history of the revisions. When the revision was made, who made it, what the nature of the revision was et cetera. I understood a lot about how buying works at Stitch Fix. I could understand why they would want to have this. I figured I knew how to represent this "history" in a compelling way that would aid understanding. I was excited to get started.

Being able to see the edit history of a Purchase Order is useful to have and if I had given her that she would have said "thank you, this is great" and I would have felt like I had done well in solving her problem. After all, she came to me with a problem and I delivered a solution. But maybe a week later she would have come back to me with "is there a way to download this history of a PurchaseOrder as a CSV?". Easy. Here you go. Now I would be feeling really good about how much use she was getting from this feature. Then she'd ask, "is there a way to download this data for *all* Purchase Orders across a week, month or quarter?". That would have been a little more involved, it probably would have taken a while but I would have built a CSV report downloader tool. "Great!" she would have said, and I wouldn't have heard from her again as she buried her head in her pivot tables, or whatever it was they did in Excel, as she tried to use this data to answer the question of how much time her buyers were spending making revisions to Purchase Orders.

In this allegory, Amanda applied her knowledge of the engineering tools available (we've given them hundreds of CSV downloads) to her problem and came up with an elegant solution. "If I can get all the revision data from all our Purchase Orders into a CSV, I can find the Purchase Orders that required the most revising". Perfectly sound and perfectly rational and it would have done the job.

But I didn't do any of this. Instead I asked her "what problem are you trying to solve" and found that she was trying to build some metrics around the time and effort involved in the back and forth the Buyers were having with their Vendors. She was actually asking for some data to help give her some insight. I suggested that we could skip this "history view" completely and I could give her a report by Vendor showing the average number of revisions per Purchase Order. Vendors near the top of the report require more revisions per Purchase Order and require more time on our part to manage. We could even create a metric from this and make some sort of comparative analysis between Vendors and maybe work with them on uncovering what underlying issues were driving all these revisions.

In retelling the story to you now, you probably assume that your beloved Grandfather had some prophetic ability and somehow knew what Amanda was *really* asking for. Sadly not. At Stitch Fix we worked hard to ensure that we were working on the "right" thing. There was no end to the things we could do, nor things we wanted to do. There are not many *"sure things"* in life. Let alone in software engineering at a young, ambitious company.

One of the most powerful ways we had to do that is the simple question Jeff, our CTO, taught us to ask; "what problem are we trying to solve?". 

You can't know how every bet will pan out, or even know what bets to make. But you can do a reasonable job of making sure that *at this moment in time, knowing what you know today* that you're working on the most right thing. Jeff's question, which became my mantra, helped to guide us to knowing as much about the problem as we can. In the process stripping away everybody's assumptions and preconceived notions about what we ought to do and allowing everyone the ability to see the bigger picture.

Do you know what problem *you* are trying to solve?

---
layout: post
title: Understand What You Want
---

It is not uncommon for a client to request a feature without having to ask many questions immediately following the request to clarify scope.  It is possible for clients to interpret this as the developer trying to get out of having to build exactly what they want, the developer pushing their ideas onto the client, or the developer introducing complexity to what is a simple request.  These mis-understandings come from somewhere it is easy to complain about them and wish them away, but we still have to deal with them.

The root of the cause seems to be buried deep in the differences of client experiences with other people they interface with regularly and the expectations of a programmer focused in on efficiently completing a job so they can continue to unashamedly earn their (often perceived as 'high') hourly rates.

Both parties have good intentions, but both parties need to know what the wants in order to move forward.  Just as importantly, in order to convey your intentions to the other party, you need to truly *understand* what you want.

### Just copy this!

A project I'm working on has an element that shows a map with local businesses of whatever type you are looking for with details about each business listed underneath the map:

![duckduckgo pizza locations](/public/duckduckgo_pizza.png "DuckDuckGo Pizza Locations")

I didn't create this element, and I didn't create the requirements for the element either, the element existed before I was hired to help with the project.  The client told me they were not happy with the element.

The client told me that they told the developers they wanted, "windowshades just like DuckDuckGo," and didn't understand why it wasn't built just like DuckDuckGo's.

The list of things that were *broken* wasn't easy to get (first problem), the client had some thoughts in their head about how it should 'be better' but had to literally show me in a browser features that they did not like. . .  over several meetings. . . with several different people.

They had a feature on their website that they felt was incomplete but noone had taken the time to explain why it wasn't incomplete - they were stuck on the, "it doesn't work like DuckDuckGo," part and hadn't moved beyond their initial frustration try to actually resolve the issues.

### Understanding

A client doesn't know what a developer needs to build the thing they want (if they knew those details they probably wouldn't need to hire someone in the first place).  Unless they're a mind-reader, a developer doesn't know exactly what a client wants either.  It is the developer's job to solve this problem - not the client's.

In my work I tell my clients I try to put myself in their shoes.  I try to *take ownership* of whatever project I'm working on and proceed as if the project was my own pet project and my carreer depends on it as much as theirs does.  To get to this point, I need to know the following:

* What problem is the client trying to solve?
* Why are they trying to solve that problem?
* What other problems are they trying to solve?
* What resources are available to resolve that problem?


#### What problem is the client trying to solve?

I don't want to hear what the client thinks they want.  Due to what results from things like [priming](http://en.wikipedia.org/wiki/Priming_%28psychology%29) and [groupthink](http://en.wikipedia.org/wiki/Groupthink) I only want to hear what problem the client is trying to solve.  

Part of the reason someone hires a web developer is because they need someone who understands web development.  If you take the ideas of someone who doesn't understand web development build what they say they want, you can end up with a monstrosity that does not actually help the client.  If a developer listen to what the client says they want, their thought process may be spoiled by these ideas and they could build something poor for the client because they did not take the time to creatively solve the problem.

The client's original proposed solution:

With the example client's situation, I rapidly learned that they don't actually want the DuckDuckGo feature replicated as many details the client cared about were non-existant on the DuckduckGo product (as a web developer this may stand out as an obvious reason why the client's product did not work exactly like the reference product, but our clients are commonly not web developers)  We'll pick one specific problem from the list of problems with the element and focus on it:

There are buttons to browse the businesses listed on the map, when clicking through the elements the user would occsaionally accidentally highlight large blocks of text within the element.

#### Why are they trying to solve that problem?

This is taking the thought process back another step.  Part of understand the client is understanding what their problem actually is.  They may think their problem is, "clicking the buttons to browse the businesses listed on the map, when clicking through the elements the user would occsaionally accidentally highlight large blocks of text within the element," but the real problem may very well be, "my users become frustrated with my carousel."  There is a difference between the two.

After understanding what problem the client is trying to solve, take the time and understand why they are trying to solve that problem because they may simply not understand what the problem actually is.  Spending a few extra minutes in dialogue with your client can save hours of development time later (in addition to more time spent talking about requirements with the client later).

If you took the time and fixed irratic movement with the carousel you may have found that you end up removing the carousel anyway because the problem wasn't that the carousel moved irratically, it's that carousels are []typically irritating anyway](http://shouldiuseacarousel.com/) -- If you spent time reading further about the problem you may have realized that the correct solution was to remove the carousel, not fix an irrelevant bug within the carousel.

In our particular case, I didn't get set on the path to the appropriate solution until I got through the full list of questions, you as a reader will have to wait too.

#### What other problems are they trying to solve?

Before you start working on a solution, it is worth trying to get a bigger picture of what's going on.  What other problems is the client facing?

Someone hiring a web developer probably doesn't know exactly what a web developer does.  It takes work to discover a specific problem a client may have, and this is based off of the assumption that the client knows what the web developer can do for them.  Web applications are big projects, there's a lot going on.  It is possible that the client doesn't understand that other issues may be related to the problem they are assigning you.  It could be beneficial to spend time to get to know a little more about the project beyond what is understood to be your assigned scope.

Beyond other usability problems with the website I learned the client was trying to solve a grander problem of a desire to merge-with or acquire similar companies within their industry.  They were using this web application as a proposed solution to many common problems businesses in this industry face.

What?!  We went from buggy switch to business mergers in no time.

This client was chatty about the specifics, but many clients may be close mouthed about some things.  The context of the problem you're working on matters if you want to do the best work you can for your client.  This client had a meeting in a few days to showcase their new web app and they wanted specific features working bug free because they looked good in the context of a meeting.

This is important to know because now I could frame my work.

I have 3 days to fix the problem, while I may disagree with their use of a carousel / slider in this situation (for many reasons) they don't have time to redesign the ui, and honestly it is not important.

What is important is that they have some shiny features to show off in a meeting in a few days in order to help close a deal that is larger than the web application itself.  I now know that my ultimate audience isn't actually users of a web application in daily use -- it's people watching someone show off a demo of this application.

I don't need the application to actually behave in a manner that encourages users to accomplish a given call to action, it just needs to look like it can do the kinds of things that people running a company, who have little knowledge of the science of getting users to benefit from your website, think a website needs to do.  And I have a short amount of time to do it.

This may feel like an aside, but it's directly related to this subject:

Obviously you want to do no harm.  When I work with my clients I always advise them to the best of my abilities.  If I see a client about to hurt themselves with a feature I understand to be built incorrectly, I will do what I can to stop them from hurting themselves.  But this is not one of those times.

In practice you build what you need to build to solve a very specific problem.  I am being genuine here when I explained what the problem actually is.  It sincerely is important to build this feature to look its best for those watching a demo of it during a meeting.  The best for this situation may not be the best for the live product, but, given the circumstances, I did not have the time to rebuild the feature to work well enough to serve both purposes: serving end-users actually using the web application and having the application look great in a showcase situation.

My understanding of the above details were sealed when I saught the answer to the final question. . .

#### What resources are available to resolve that problem?

This one is simple but often overlooked.  Once you know what the problem is, you need to solve it, but some solutions take longer to create than others.  Discuss these possibilities with the client before you tackle the solution.  If you did your work in fully understanding the problem in the above steps, you probably already have a good idea, but it is better to not assume when you could know.

Simply ask them, "what resources are available to resolve this problem?"

Don't be afraid to ask questions that may involve money, money is a large discussion point for our line of work and we should never be afraid to discuss it.

I'm not saying every problem and solution needs an accurate time estimate, but someone who's paying for your services may be able to pour a ridiculous amount of resources into a given problem, or they may have no money left in the budget at all.  It is a developer's responsibility to learn if the problem being faced is so important to the client that they are willing to hire extra help to solve it more quickly, and the opposite is true - you do not want to drain your client's  budget on a feature that they truly don't find important.

At first, to me, it seemed that my client would be willing to move Earth itself to get this problem solved as the results of this meeting could make a huge difference in the future of their company.  But as I learned about the situation, they really weren't willing to pour infinite resources into the problem.

I learned:

* The previous team that was working on the project was a low-budget outsourced team from a non-English speaking country.
* They were very weary of spending money on anything related to web-development as they have very limited in-house experience in web development and are just begginning to get accustomed to having anything resembling an IT department with the development of this application.

So on one hand, the client is basing their entire future on the success of a meeting which is largely dependant on modifying the behavior of one element on a web page.

On the other hand, the client doesn't want to spend very much money or time to get it done.

Since I took the time to decide what the client needs, I can begin to explain in a relatable language what I need to solve the problem.

Because I followed these points and created a productive discussion between the client and myself we can agree and a practical solution to the problem and allow ourselves to move forward.



### A tactical extraction of information

The world is not perfect.  A client may not always know what they need, or what they want.  Even after getting to understand their situation and understanding each other's perspective you may not come to an agreement that makes you both 100% happy.  But you can come to a solution that meets the expectations of all parties involved, keep everyone happy to be involved in the project, and encourage forward progress towards an end-product that's better than what the client has now.

I want to know what my client wants, and the information abouve is how I tactically extract that information.  My clients aren't intentionally hiding this information from me, but I use my skills as an experienced web developer them understand exactly what they want with reasonable expectations so I can build something that they want and have them happy enough with my work to come back for more.

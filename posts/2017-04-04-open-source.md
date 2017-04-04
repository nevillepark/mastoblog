# So You're a Total Casual Using an Open Source Social Network For the First Time

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Happy 25th birthday, <a href="https://twitter.com/hashtag/Linux?src=hash">#Linux</a>! Here&#39;s your f-ing <a href="https://twitter.com/hashtag/cake?src=hash">#cake</a>, go ahead and compile it yourself. 

<a href="https://t.co/OCQUDPhlXY"><img src="https://pbs.twimg.com/media/CqssXMfXEAAwPcI.jpg" width=500px /></a></p>&mdash; Bogdan Botezatu (@bbotezatu) <a href="https://twitter.com/bbotezatu/status/768756952528723969">August 25, 2016</a></blockquote>

OK, so a lot of people are joining [Mastodon](http://mastodon.social), and tooting about problems they've spotted, or wondering why feature *X* is missing, and so on. So I thought it might be useful to explain how things work when the applications you use *aren't* run by giant corporations. 

## Cake 🎂

When you use Windows or Instagram or whatever, it's kind of like getting a cake. The great thing is that someone already baked it for you. And if you find a fly stuck to the icing, you can take the cake back to the store and get a refund. 

However, the recipe is top secret, and only the bakery owns it. If the bakery closes down, no more cake for anyone. Also the bakery collects your personal information and sells it to advertisers and a lot of people want the cake to be nut-free but the bakery would rather work on cake decorating and the new icing is *gross*.

Some cakes are different. They're "open source". It basically means that the recipe is free and publicly available. Usually the people who came up with the recipe also bake and give away the cakes for free. If you want to change the official recipe, you can do that—or you can make your own cakes, as long as you share your recipe. Lots of people just get free cake. There are still bakeries, but because everything is free, they tend to be non-profit or supported by someone's side business. There are also lots of people who just bake at home as a hobby. A lot of the big free bakeries use their recipes.<sup id="ref1">[1](#fn1)</sup>

## 🎶 Lower Your Expectations 🎶

So the "recipe" is source code. Some of the "cakes" include Android, Firefox, and Wordpress—but also the programming languages they're written in, the web server software that runs them, and other really fundamental parts of the Internet. I think [the Heartbleed bug really exposed](http://mashable.com/2014/04/14/heartbleed-open-source) how much of the Internet runs on open source software run by, like, some guy in his underwear at 3 a. m. 

And yes—it's usually a guy. You know how white and male tech is? Well, open source is even *more* so. The community is really resistant to criticism and calls for diversity, and there are a lot of total dinosaurs in key positions. It takes a lot of free time for little reward. And it's even less beginner-friendly in general. In open source, "code it yourself" is a common response to people who find bugs or request features.

I don't think "code it yourself" is an adequate response if you want your software to be widely used by *everyone*, not just developers. But projects that are quite new or mostly developed by one person, like Mastodon, need all the help they can get.

A major social network like Twitter or Facebook has an entire corporation behind it. They have a marketing team, people who handle spam or abuse reports, graphic designers, teams of back-end developers, front-end developers, people who come up with new features…you get my drift. Mastodon is open source, and it has none of that. It's basically just one guy and a bunch of volunteers. So you may have to adjust your expectations.

The upside is that—unlike with Twitter or Facebook—you actually have a big role in shaping Mastodon as it grows. You can talk directly to the dev (Gargron), or with other people who can do dev-type stuff. 

If you see something that's broken, or you think there's a feature that should work differently, or you come up with a way to improve the service, it is up to *you* to make your voice heard. You *can't* assume that someone else has spotted the same thing you have and will fix it in short order. Conversely, if you come up with a good idea, you can't assume that no one "in charge" will listen to a random user. You have the power to make changes yourself.

## How To Get Involved 💪

Using small and early-stage open source software like Mastodon requires a bit more engagement. You don't have to know how to code! There are many other ways to contribute, including:

- reporting bugs
- requesting features 
- discussing features
- testing new versions
- [translating](https://github.com/tootsuite/mastodon/blob/master/docs/Contributing-to-Mastodon/Translating.md)
- graphic design/art
- writing help pages/guides
- connecting people with matching needs/skills
- publicity via press or social networks

All of these are just as important as coding, especially if you want the project to appeal to people who aren't coders themselves. 

You'll want to get a [Github](https://github.com) account. Github is a site where people store code, track bugs, and collaborate on projects. It's where Mastodon's source code is hosted, as well as source code for some Mastodon apps.

If you find a bug or you thought of a feature you want or a better way to do things, [check out the "Issues" section](https://github.com/tootsuite/mastodon/issues) on Mastodon's Github page. Poke around and see if anyone has already suggested it; look at [the list of closed issues](https://github.com/tootsuite/mastodon/issues?q=is%3Aissue+is%3Aclosed) as well, in case anyone has had the same question and it's been answered.

If no one else has done it yet, [create a new issue](https://github.com/tootsuite/mastodon/issues/new)! This is the most effective way to get your voice heard by people who can actually do something about it. Your problem/suggestion can get officially numbered, flagged, triaged, and eventually checked off. Just tooting will not solve anything.

If it's something that you think you might be able to do yourself, you can edit the source code and create a pull request. Basically, when you edit a file that belongs to someone else, it creates a fork (a copy) of the source code that belongs to you. A pull request is a message asking the original owner to incorporate your changes. You don't need to download any special programs; you can just do it from the website if you want.<sup id="ref2">[2](#fn2)</sup> There's currently a little-used ["fit for newbies" tag](https://github.com/tootsuite/mastodon/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3A%22fit%20for%20newbies%22%20) which I hope will be used more widely to highlight simple changes people can hone their skills with.

The nice thing about early-stage open source software is that a lot of your fellow users are techies. If you have questions about the way Mastodon works, or how to use Github, or how to help out with related apps and websites, try posting to the federated timeline (or your local one if the federated one is too noisy). There are a lot of people who are happy to help you get involved!

Lastly, I just want to say, it feels totally awesome to officially contribute to a project, even in a tiny way. Like, I was using this Twitter client and the dates and times weren't being displayed properly and I was getting this weird error message. I figured out that it was because my computer system locale was set to *Canadian* English. If I switched my locale to US English, it worked. But I shouldn't *have* to switch! This was American cultural imperialism at work! Anyway, I went on Github and found the source code for the date and time module. There was a list of strings for displaying the information in various locales. And it included US English, Australian English, South African English, and so on…but not Canadian English! So I forked the repo and added "en_CA" to the list, and the owner merged my pull request, and the next time I fired up the Twitter client, everything worked perfectly. No more error message, no more ugly dates and times. *I* did that! I fixed that! That was me! You're welcome, English-speaking Canada!

It can be genuinely empowering to be able to shape the software you use all the time. You're not just a user, you're a maker. Maybe that doesn't really matter to you, but I think you should give it a try. Just in case. So, I've put this post up on Github. Do you have any corrections, changes, or suggestions? Maybe you want to translate it into French? Try creating an issue or making a pull request. I look forward to your contributions.

___________________________________

<strong id="fn1">1.</strong> I've sort of been using "free" and "open source" interchangeably, but the two terms represent distinct movements with fundamentally different principles. The free software movement believes no recipes should be secret and everyone should be able to bake anything they want. Cake wants to be free! Open source emphasizes the benefits of the process: anyone can work on the cake, and anyone can spot (and fix) mistakes in the recipe. Also, you don't have to pay them for it. :P Free and open source projects are often referred to together as FOSS or F/LOSS. (The L is for "libre".) [↩](#ref1)

<strong id="fn2">2.</strong>: A "Github for total noobs" tutorial is beyond the scope of this article, but I may work on putting a short one together based on the toots I've made answering people's questions. Also, *I'm* a total noob on Github, so it's like the blind leading the blind, you know? [↩](#ref2)

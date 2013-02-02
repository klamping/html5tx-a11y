Disclaimer: All this content is a work in progress. It is not an 1:1 transcript of the talk. Things are subject to change. All feedback is welcome.

----

Hello everyone, welcome to "What HTML5 Means for Web Accessibility". My name is Kevin Lamping and I do Front-end Web Development and try to do it in an accessible manner. I'm a native Texan, born and raised in Boerne, Texas. I've lived in Texas all my life, including a few years in Austin as a Web Developer then a High School teacher. I'm currently live a short drive south of here in San Antonio with my wife and son, who is pictured here.

As I mentioned, I'm involved with accessible web development and have been for a little over six years. I first got into it back in 2007 during my first job out of college. I was working with two other great developers and we were tasked with making an eye care site accessible. Pardon the pun, but it really opened my eyes to accessibility from a technology perspective. Okay, they say you need to open your talk with a joke, but they never specify that it needs to be a good one.

I'd like to ask a favor of everyone in the audience, specifically those with a laptop (or tablet) open right now. Don't worry if you don't have a screen in front of you, I'll get to you in a second. So, if you've got something out, go to your browser of choice and open up a new tab. In the location bar of that new tab, I'd like you to type in the address of the site you most recently worked on, are currently working. If neither of those two apply, open up your favorite site you've worked on. Or open your least favorite. Just get something you've coded in front of you.

Those without a screen. I want you to think of a site you've worked on. Recent, old, good, bad. Just get it in your mind. Everyone good?

Okay, here's the WCAG 2.0 checklist in all its glory. It's a little hard to see, but that doesn't matter since all of you have it memorized anyway, right? No? Hmm. Well, we'll have to improvise.

Is anyone out there looking at (or thinking of) a page right now that they know meets all of these guidelines?
    (You do? That's awesome. Can you do me a favor? You're definitely doing it right and I doubt there's anything new that I can teach you. I'm going to put my twitter handle up at the end of my talk. If you would, take note of anything I got wrong or can improve on and send me a note. I'd really appreciate it.)

Okay, for the rest of y'all. In a few minutes I'm going to start presenting various techniques for accessibility. I'd like to see if you can use one of those techniques on the site you still have in front of you. You still have it in front of you, right? And for those of y'all thinking about it, you're still thinking only about that site, right? Good. Y'all are a great audience.

Now, thinking of this site you've got in front of you. Were you paid to ensure that website was accessible? Raise your hands if you were paid for that, if that was listed out as a deliverable. This website will be accessible.

    (If more than half) More than half of you. Okay, disregarding whether that deliverable was successfully met, I'm really happy to see that many hands go it. What I see is a sign that accessibility is now a part of our job description. It's something that we're expected to get right.

    (If less than half) Less than half of you had that as a deliverable. That means something. That means that it's up to us, as web developers and designers, to get accessibility right. We're the ones who need to fight that battle. We've got work to do and we're the ones who need to do that work.

Okay, thanks for your help with that. I've got good news and I've got bad news. Here's the good news:

Accessibility is easy
Once you understand the basics of accessibility, it's pretty easy to make a simple site accessible. HTML is mostly accessible to begin with, so as long as you're following best practices, getting your site to be accessible is pretty easy. Just make sure all your images have proper alt attributes; keep your forms elements labelled, and use semantic markup. You've probably already heard it all before so I'm not going to talk about it today. Today I'm going to talk about new techniques for making HTML5 accessible, and these techniques are just as easy as adding alt text to images.

But before I get to that, I want to talk about some bad news: Accessibility is hard
All that stuff I said about accessibility being easy is only true when you're working on a page that isn't dynamic. Once you try and throw JavaScript into the mix, it gets hairy. Making something even as simple as an expand/collapse widget accessible for all users is tricky. Trying to get your site to work across the variety of screen readers out there is akin to trying to support IE6. Each has its own little quirk..... Meeting all those guidelines I listed a few minutes ago is near impossible. Not only do you have to support a wide range of browsers, you also need to support a wide range of assistive technology like screen readers.

This means that accessibility is difficult, it takes time, and it can be frustrating. We all forget to check those guidelines when we're developing. We let ourselves off the hook by saying that our audience doesn't need accessibility or we'll add it in later. The truth is, we all need forgiveness. So to get this forgiveness, I'm going to call up my Catholic heritage; please repeat after me.
Bless me father, for I have sinned.
It has been ___ days since I last used a screen reader
I am sorry for these and all the sins of my past life, especially for ___
Amen

So why do we do it? What makes it worth the effort? Well, I like to think about web accessibility like this: When you're developing a website, you have a choice to make it accessible or not. But for someone with a disability, they don't have a choice. They have to live with that disability regardless of how difficult it is. When they go to your website, they can't just turn off their disability for that moment if time. We're the ones who decide, we're the ones who play gatekeeper.

Luckily, it turns out accessibility is good for you. Accessibility is just usability for the real world. How many of y'all are parents out there? Anyone a parent of a toddler? This is a photo my son took. He's barely three and knows how to work a camera phone. He knows how to open youtube on my phone and get to his favorite video clips. He gets confused when I'm working on my laptop and he can't scroll the screen down with his finger. Any other parents out there with similar experiences? Has anyone seen their child try and use a magazine like they use an ipad? It's pretty cute.

Speaking of the ipad, a short bit before Steve Jobs passed, a famous singer had some unusual praise for the man. Let's listen in:
http://youtu.be/O2Tkj8SIHMU?t=4m47s

("I want you all to give a hand to someone that you know whose health is very bad at this time," Stevie Wonder said. "His company took the challenge in making his technology accessible to everyone. In the spirit of caring and moving the world forward, Steve Jobs. Because there's nothing on the iPhone or iPad that you can do that I can't do. As a matter of fact, i can be talking to you, you can be looking at me, and I can be doing whatever I need to do and you don't even know what I'm doing!")

Did anyone have trouble hearing that? Would it have been nice to have captions available? Even when you don't have a physical disability, supporting accessibility
TODO finish this thought.

After Jobs dies, Stevie Wonder had some more to say about why Steve was so important to him. I wish I could read the entire interview for you, since every thing Stevie says in that article is is inspirational. But since we don't have all afternoon, I'll read out my favorite parts:

“The one thing people aren’t talking about is how he has made his technology accessible to the blind and the deaf and people who are quadriplegics and paraplegics. He has affected not just my world, but the world of millions of people who without that technology would not be able to discover the world.”

“He developed Garage Band, so now a 15-year-old kid can be in his bedroom with his iPad playing around with Garage Band and come up with unbelievable ideas, which can then be taken to the next level… He has leveled the playing field.”

That quote reminds me of my son, who, at one year old, started "recording" his own music in garage band. It's amazing that the simple act of getting the mouse out of the way gave my son access to using technology to create.

This is usability and accessibility combined. Here's Stevie again, “His company was the first to come up with technology that made it accessible without screaming out loud, ‘This is for the blind, this is for the deaf.’ He made it part of the actual unit itself; there were applications inside the technology that allowed you to use it or not use it"

Here's some more from the article.
“I’m just hoping that his life [...] will encourage [and challenge] those who are living still [...] to do what he has done, [...] you just make it one of your applications, it’s in your technology. That will then create a world that will be accessible to anyone with any physical disability"

So it turns out that when you make your sites accessible, Stevie Wonder might just call you up to say thanks. But seriously, Steve Jobs made his products accessible, not to meet govt regulations or check off an item on the deliverable list, but for reasons like his love of music, He wanted to get that technology to everybody, regardless of disability. That's what makes it worth it.

So let's get to it: Does HTML5 improve website accessibility or make it worse?

...

## Sectioning Elements
Let's start off by talking about the new sectioning elements. How many of you have used one of these on your website? Cool. Well, let's look at browser accessibility support for a couple of these elements.

Let's start with the header tag. Accessibility wise, in IE, Safari and Opera, <header> is reported as a div tag. This doesn't mean that these browsers don't support the tags, just that they don't properly tell the OS what they are. In chrome, the header tag is announced as a section. Only in Firefox does it get it right.

But here's something else. That's for Windows browsers. It's different for Mac. On mac it's Opera, Chrome and Firefox mispronouncing the element. Safari is the lone browser that gets it right.

I should take a second to mention that this support information is provided by html5accessibility.com. Their most recent stats come from Septemeber of 2012, so things may have changed a little since then. Take all this with a grain of salt.

How about footer? Well, the picture is much the same, but with Chrome joining the party. On the Mac side of things, Firefox makes the cut this time.

Two elements down and support isn't stellar. And the truth is, it's actually bleaker than this. Accessibility support is actually a very broad term. This is because the browser isn't the only one responsible for supporting new language. It's also up to the assistive technology the person is using. To understand this, we need to grasp the relationship between the browser and assistive technology like a screen reader.

When you load a website, the browser will expose that website's structure to the OS. It does this through an Accessibility API. Without getting into too much details, this API is basically a middleman between the program being run and the assistive technology being used.

In this example, Safari talks to the Apple Accessibility API, which is being listened to by Voiceover. This is a simplification of what's going on, but that's okay. The point I'm trying to make is that support needs to happen in two place. Not only does the browser need to send the right information to the API, but the screen reader needs to be listening for that information.

So if you have a browser the fully exposes every HTML5 element to the Accessibility API, but your screen reader isn't listening for that content, then it's unsupported. This goes both ways; if the screen reader listens for content the browser doesn't speak, then it's equally as useless.

To make matters worse, as web developers know, users aren't the best at upgrading their technology. So while support may be introduced in newer technology, we still have to support the full spectrum. Does this mean all this semantic HTML being introduces is essentially useless until both browsers, assistive technology AND users upgrade their stuff?

Well, when you're belt can't do the job, it's time to put on suspenders.

## Sectioning Redux
Let's look again at our new sectioning elements that we talked about. While browser accessibility support was on the low side, there is still hope. How many of you have heard of ARIA?

ARIA was introduced many years ago, before HTML5 was started, as a way of adding semantics to low-semantic elements. Since it was introduced a good while back, there is already great support for it. ARIA has a lot of the same semantics as HTML5, meaning it can be used when browsers don't support HTML5 yet. Now if some browsers don’t support HTML5, but most support ARIA, what should you do? use both.

By combining ARIA and HTML5, support improves dramtically. Just tag on a role attribute to your HTML5 element and you're set. So taking a look back at header, we can add a role of banner. This now gives us support for those with HTML5 support, or those with support for ARIA. It's basically win-win.

Let's look at <footer>: Just add a role of contentinfo and accessibility improves. I'm going to go through these fast, since you can search for these ARIA roles pretty easy. I also link to it on my Github resources page.

For nav, we have navigation; aside we have complementary. The article element can have a role of article, but I marked it as red b/c I couldn't find support information on it. It's still safe to use and I recommend it.

There is a section role, but it's an "abstract" role. Because of this, the ARIA spec asks us not to use it. You could use a role like "region", but there are some details about region that I don't want to get into right now. Take a look into it if you're interested.

ARIA has another role called "main". The <main> element was just introduced for HTML5. Here's how it will look with the ARIA backup.

Okay, anyone in the audience thinking their site could use a quick update? This combination technique is really a great quick win to improve the scanability of your HTML5 website, particularly for screen reader users. Keyboard only users can also benefit if they're using a tool that can take advantage of these elements and roles. Take a look at ARIA roles and landmarks for more information.

...

## Audio/Video
How many of y'all out there have used the new audio and video tags? Personally, I haven't had a chance to work on a site that required these tags, but I do have a backlogged project that can take advantage of the audio tag and it's ability to easily start, stop and jump to certain sections of an audio clip. Anyway, for those of you who raised your hands; this section is for you.

I've spent a lot of time talking about screen reader support, but just because your site works with a screen reader doesn't make it fully accessible. You also need to consider other groups, like users with limited mobility or deaf users. Parkinson's disease is one of the most common nervous system disorders of the elderly and can cause shaking or tremors that make using a device like a mouse very difficult. Instead, it's easier for folks to use a keyboard as their primary input device.

HTML5 really helps here. It helps because it gives browsers a standard to follow and introduces built-in browser support. This means devs don't have to worry as much about create a video or audio player from scratch. They can take advantage of the built-in functionality and focus on the more inportant things.

One of the great things for accessibility when you use these elements is that since the browser provides the controls, they are much more likely to be accessible. Native keyboard support is already avialable in some browsers. This is in contrast to custom plugins, where you might only be able to use a mouse to play the video or audio.

If you decide to roll your own controls, be sure to use keyboard accessible elements for them, specifically the <button> tag. There are other ways to provide keyboard access through some ARIA techniques, so check them out if you're interested. The main point is, whether through browser native controls or custom ones, providing keyboard support with audio and video is much easier with HTML5.

I did meantion deaf users as well. Support for captioning is greatly improving. Almost all major browsers have support for WebVTT in their latest version. You can link to your track by adding the track tag, plus relevant attributes, inside your <video> tag. Because of this common format, generating and linking your text track is much simpler.

Now, while <video> and <audio> do have good support in most of the newer browsers, keep in mind that you still need have a fallback method to access the multimedia for those lacking support. That fallback can be a Flash-based player, assuming you have coded the Flash object to be accessible. Yes, Flash can be used to support accessibility. One option is to achieve all of this is to use a JS Polyfill library like video.js. It should provide all the fallbacks you need.

...

## Figure/Figcaption
Let's talk about some other new elements. <figure> and <figcaption> have been introduced as a way semantically associate information with images or figures. We’ve always been able to add a caption – usually you just put the caption right below the image, maybe put both of them in a <div> with a nice border around it. But for anyone using a screen reader, the only association between the image and its caption was proximity, and that association wasn’t particularly strong.

Now we have <figure> and <figcaption> that can be used to associate captions with images. <figure> doesn’t replace the <img> tag, instead it’s a container that holds both the <img> and the related <figcaption>. By doing this, it creates a semantic relationship between the two.

These elements have limited supported so far, similar to the support the header and footer tags have. Let's improve that by adding a role of 'group' on the figure element, and then also use the aria-labelledby attribute on your image to associate the content with the image. Again, HTML5 is our belt, ARIA is our suspenders.

Now, for technology that supports neither HTML5 nor ARIA, you should provide another fallback using the alt attribute. Here's an example of one way you can do it. Associate the photo with the caption using simple textual language. It's not an ideal solution, but it is an option. As I mentioned, accessibility is hard. One of the hard things about it is that you have to cover a lot of bases. Scenarios such as this, where you have to provide three levels of fallback and still not get everything perfect are common in the accessibility world. Do the best you can.

...

## Mobile Accessibility
I don't have too much time to cover this, but it's worth mentioning two things.
1) Yes, you do need to test your site on mobile devices (and yes, that includes content inside a Webview in an app)
2) When using the new HTML5 input elements, because iOS is accessible by default, you not only make the form better for sighted users, you also make it accessible for non-sighted users. This is one instance where HTML5 support is pretty good, at least for some users. In this case, Apple’s already taken care of it for you.

TODO consider adding a demo here if time permits

...

## Testing

If there's one thing I want to leave in your minds today, that's testing. You'd never release an HTML5 app into the wild without going through several rounds of rigorous testing; Accessibility testing is just the same.

It’s important to understand that assistive technologies such as screen readers or speech recognition software don’t all work exactly the same, so you should test your website with these technologies as much as feasible.

For testing, Apple computers have a built-in screen reader called VoiceOver, and if you have Windows, check out the free/open source NVDA. iOS and Android devices both have screen readers available for mobile testing.

If you're fortunate to work at a company with a sizable budget, you should request access to various assistive technologies. Just as you need the latest $600 phone to do mobile testing, you need the latest screen reader to do accessibility testing. Just as a website might work in FF but break horribly in IE, a site may be accessible in NVDA and break horribly in JAWS. This is the nature of software development

## Closing Remarks

The final thing I want to say, and this goes along with the testing remarks I just made, is that things may have already changed. To quote Isaac Asimov, "It is change, continuing change, inevitable change, that is the dominant factor in society today. No sensible decision can be made any longer without taking into account not only the world as it is, but the world as it will be..."

So test your stuff. Nothing is guaranteed. Speaking of, if I got anything wrong, please mention it now or file an issue on Github and I'll do my best to correct it in a timely manner.

Thanks
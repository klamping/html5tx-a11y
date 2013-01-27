Disclaimer: All this content is a work in progress. It only covers the first 40 or so slides. It is not an 1:1 transcript of the talk.

----

Hello everyone, welcome to "What HTML5 Means for Web Accessibility". My name is Kevin Lamping and I do Front-end Web Development and try to do it in an accessible manner. I'm a native Texan, born and raised in Boerne, Texas. I've lived in Texas all my life, including a few years in Austin as a Web Developer then a High School teacher. I'm currently living 75 minutes south of here, in San Antonio, with my wife and son.

As I mentioned, I'm involved with accessible web development and have been for a little over six years. I first got into it back in 2007 during my first job out of college. I was working with two other great developers and we were tasked with making an eye care site accessible. Pardon the pun, but it really opened my eyes to accessibility from a technology perspective. Okay, they say you need to open your talk with a joke, but they never specify that it needs to be a good one.

I'd like to ask a favor of everyone in the audience, specifically those with a laptop (or tablet) open right now. Don't worry if you don't have a screen in front of you, I'll get to you in a second. So, if you've got something out, go to your browser of choice and open up a new tab. In the location bar of that new tab, I'd like you to type in the address of the site you most recently worked on, are currently working. If neither of those two apply, open up your favorite site you've worked on. Or open your least favorite. Just get something you've coded in front of you.

Those without a screen. I want you to think of a site you've worked on. Recent, old, good, bad. Just get it in your mind. Everyone good?

Okay, here's the WCAG 2.0 checklist in all its glory. It's a little hard to see, but that doesn't matter since all of you have it memorized anyway, right? No? Hmm. Well, we'll have to improvise.

Is anyone out there looking at (or thinking of) a page right now that they know meets all of these guidelines?
    (You do? That's awesome. Can you do me a favor? You're definitely doing it right and I doubt there's anything new that I can teach you. I'm going to put my twitter handle up at the end of my talk. If you would, take note of anything I got wrong or can improve on and send me a note. I'd really appreciate it.)

Okay, for the rest of y'all (Flash picture of cowboy). In a few minutes I'm going to start presenting various techniques for accessibility. I'd like to see if you can use one of those techniques on the site you still have in front of you. You still have it in front of you, right? And for those of y'all (flash cowboy) thinking about it, you're still thinking only about that site, right? Good. Y'all (flash cowboy) are a great audience.

Now, thinking of this site you've got in front of you. Were you paid to ensure that website was accessible? Raise your hands if you were paid for that, if that was listed out as a deliverable. This website will be accessible.

    (If more than half) More than half of you. Okay, disregarding whether that deliverable was successfully met, I'm really happy to see that many hands go it. What I see is a sign that accessibility is now a part of our job description. It's something that we're expected to get right.

    (If less than half) Less than half of you had that as a deliverable. That means something. That means that it's up to us, as web developers and designers, to get accessibility right. We're the ones who need to fight that battle. We've got work to do and we're the ones who need to do that work.

Okay, thanks for y'alls (flash cowboy) help with that. I've got good news and I've got bad news. Here's the good news:

Accessibility is easy
Once you understand the basics of accessibility, it's pretty easy to make a simple site accessible. Make sure all your images have proper alt attributes; keep your forms elements labelled, and use semantic markup. HTML is mostly accessible to begin with, so as long as you're following best practices, making sure your site is accessible is pretty easy. It's so easy, I'm not even going to talk about those things today. There are plenty of tutorials out there if you're unfamiliar with the basics of web accessibility.

No, today, I'm going to talk about the bad news:
Accessibility is hard
All that stuff I said about accessibility being easy is only true when you're working on a page that isn't dynamic. Once you try and throw JavaScript into the mix, it gets hairy. Making something even as simple as an expand/collapse widget accessible for all users is tricky. Trying to get your site to work across the variety of screen readers out there is akin to trying to support IE6. Each has its own little quirk..... Meeting all those guidelines I listed a few minutes ago is near impossible.

Accessibility is difficult, it takes time, and it can be frustrating. We all forget to check those guidelines when we're developing. We let ourselves off the hook by saying that  We all need forgiveness
Maybe tease about knowing catholics by the fact that they can't sit still, or genuflected before they sat down
Simon Peter says 'Sit'
Simon Peter says "Kneel"
Simon Peter says "Stand"
"Genuflect"
Ha! You're excommunicated!!
Bless me father, for I have sinned.
It has been ___ days since I last used a screen reader
I am sorry for these and all the sins of my past life, especially for ___
Amen

So why do we do it? What makes it worth the effort? Well, I like to think about web accessibility like this: When you're developing a website, you have a choice to make it accessible or not. But for someone with a disability, they don't have a choice. They have to live with that disability regardless of how difficult it is. When they go to your website, they can't just turn off their disability for that moment if time. We're the ones who decide, we're the ones who play gatekeeper.

Luckily, it turns out accessibility is good for you. Accessibility is just usability for the real world. How many of y'all are parents out there? Anyone a parent of a toddler? This is a photo my son took. He's barely three and knows how to work a camera phone. He knows how to open youtube on my phone and get to his favorite video clips. He gets confused when I'm working on my laptop and he can't scroll the screen down with his finger. Any other parents out there with similar experiences? Has anyone seen their child try and use a magazine like they use an ipad? It's pretty cute.


A short while after Steve Jobs died, an interview came out with Stevie Wonder about why Jobs was important to him. I wish I could read the entire interview for you, since every thing Stevie says in that article is is inspirational. But since we don't have all afternoon, I'll read out my favorite parts:

“The one thing people aren’t talking about is how he has made his technology accessible to the blind and the deaf and people who are quadriplegics and paraplegics. He has affected not just my world, but the world of millions of people who without that technology would not be able to discover the world.”

“He developed Garage Band [recording and music editing software], so now a 15-year-old kid can be in his bedroom with his iPad playing around with Garage Band and come up with unbelievable ideas, which can then be taken to the next level… He has leveled the playing field.”

My son, at two years old, started "recording" his own music in garage band. It's amazing that the simple act of getting the mouse out of the way gave my son a five-year jumpstart on using technology to create.

“His company was the first to come up with technology that made it accessible without screaming out loud, ‘This is for the blind, this is for the deaf.’ He made it part of the actual unit itself; there were applications inside the technology that allowed you to use it or not use it"

This next quote is best said by the man himself:
http://youtu.be/O2Tkj8SIHMU?t=4m47s

("I want you all to give a hand to someone that you know whose health is very bad at this time," Stevie Wonder said. "His company took the challenge in making his technology accessible to everyone. In the spirit of caring and moving the world forward, Steve Jobs. Because there's nothing on the iPhone or iPad that you can do that I can't do. As a matter of fact, i can be talking to you, you can be looking at me, and I can be doing whatever I need to do and you don't even know what I'm doing!")

“I’m just hoping that his life [...] will encourage [and challenge] those who are living still [...] to do what he has done, [...] you just make it one of your applications, it’s in your technology. That will then create a world that will be accessible to anyone with any physical disability"

It turns out that when you make your sites accessible, Stevie Wonder might just call you up to say thanks. But seriously, Steve Jobs made his products accessible, not to meet govt regulations or check off an item on the deliverable list, but for reasons like his love of music, He wanted to get that technology to everybody at a reasonable cost.

So let's get to it: does HTML5 improve website accessibility or make it worse? How have screen readers adapted to the new technologies? Does HTML5 remove the need for WAI-ARIA or the need for accessibility testing all together?

...

Backwards compatibility:
Support for HTML5 by any particular browser is not going to be a yes/no question

...

Looking at the new sectioning elements, we already have strong support through ARIA. ARIA has some of the same accessibility functions as HTML5, and it’s been around longer, so most newer-ish browsers support it, as well as most assistive technologies.

So backwards compatibility is pretty easy: just tag on a role attribute to your tag and you're mostly set. There are still old tech out there, but they just won't get the new func. They'll still have full access though.

The nice thing about the HTML5 element is that it’s semantic HTML; that is, it provides meaning to the structure of the page. A div doesn’t do that. So if some browsers don’t support HTML5, but most support ARIA, what do you do? The answer is: use both.

...

Figure and fig caption
New element. Used to add info to images/figures. Use in conjunction with aria-labelledby attr, then include alt attribute for final fallback. Drawback is it's too verbose, so use aria-hidden

...

Audio and video
Keyboard support
Html5 really helps here, by standardizing and providing built-in support, so devs don't have to worry about it. It just works


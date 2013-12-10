# HowTo.ppt

It happens way too often to me: I watch a conference talk that has an *amazing* premise, well-researched background information and the most interesting field in the world ... and it bombs. Horribly. People are bored, the presentation drags on and on and on, and I wonder, where has all the energy gone?

Turns out, **even good ideas need awesome presentation.**

Too often, the really good ideas are presented badly. Why? I think because the people who think about the really good ideas don't assign themselves a lot of brain space to think much about presentation, or because they are of the opinion that the idea is *so* incredibly good, it should stand on its own. While that may be correct, it is also arrogant. You *want* to get your idea out there, don't you? You *want* people to think about it and talk about and maybe even try and find flaws in your idea, so you can improve on it and have even better ideas. The more easily digestible you make your idea by virtue of presenting it **not badly**, the more people will listen to you. Don't dilute your message, just avoid the most basic mistakes. 

I'm not an expert on public speaking. I've held a few moderately successful talks at uni and I'm generally okay at small talk and traversing larger groups. But I've been thinking about the subject of better public speaking a lot, and I've assembled a few tips for my fellow hackers and enthusiasts. There are a lot of resources online, in books, and as courses about this, and you should totally consume all of those. I've linked to the ones I think are most relevant below. But in the meantime, how about I try to distill some kind of tl;dr out of the available material? In addition to the elements of presentations that programmers will need more often than others (source code, demos, video), I'll focus on those things that, in my opinion, hackers and hacker-like people most often get wrong.

This article is kinda mix-and-match. Read through it, and pick out those tips that most appeal to you, and try to apply them to your talk. Before we start, though, I have to address one elephant in the room:

## On the Fruit Company

So I use an Apple computer and I sometimes write software that runs on their platforms. I also like fonts, and colors, and weird color spaces. Hackers and hacker-like people distrust people like me, because they think it's all presentation and no message. Well, forget about that. Use any font you like. Use any color you like. Create your presentation on BSD, OSX, Windows or any Linux you like, because that doesn't matter one bit. I like slides in a specific set of colors, and with a specific set of fonts, but that's just my style, and it shouldn't necessarily be yours. 

Colors, fonts, OSes... they're all window dressing, and don't really affect your core idea. What should really be important is more general: How do you present your idea so people can *grok* it? So let's start with some structure.

## How to Structure Your Talk

Obviously your talk needs structure. You need to explain things one by one before you can use them in larger building blocks – resolve your dependencies. 

What is less obvious is that you also need structure to build *tension*. You don't need to make a dramatic thriller out of your subject, your average human will care way more about a topic if theres a narrative arc in it. To help your audience stay focused, don't only talk about the technical details, tell the *story* of the technical details. 

This might seem very unnatural, unscientific or even unwise to do, so apply as much or as little of this advice as you feel comfortable with. But trust me: some tension and subsequent relief, even in a goofy fashion, will make your talk come alive like nothing else.

* Start with what you set out to do. Have some question, or a goal to attain. Usually, you're the protagonist of your talk, but maybe it is someone else? Some*thing* else even?
* Tell us about what worked, but also what didn't, and how your protagonist felt when things didn't work out. 
* Drive your story forward. How did your protagonist overcome their obstacles, were there new ones?
* Have a climax of some sort. Your protagonist's breakthrough, the final discovery, the working hack. This is where a demo might be in order, or something special.
* Don't dawdle too long after the climax. Tie up any loose ends and go to questions.

This whole story telling approach will obviously not work with every topic, every talk, or every presenter. Maybe you need to find other ways to create a narrative arc, to create tension. Or maybe is it completely impossible for some reason. So let's talk about other ways to structure your talk that are at least as important as the story telling aspect.

Don't tell people what your structure is beforehand. If your talk consists of three loosely coupled parts, it's okay to mention that. But do not make the rookie mistake of wasting a slide, and three minutes of your audience's attention on telling them what you are going to tell them, slide title by slide title. If your talk is well-structured, your audience will follow you through it without it, and if it isn't, they're going to tune out anyway. Also, this will destroy any story tension and send the clear message: this is going to be a dry, academic presentation.

Have an opening and a closing. It is common to circle back to the idea at the beginning when finishing a talk. For example, you could open with an anecdote that exposes your main problem or goal, then solve the problem through your talk, and then finish your anecdote, achieving a satisfactory ending. 

Think about the message you want to convey to your audience. Maybe the message is "there is this new exploit I found, so please be conscious of it in your projects." Or maybe it is "look at how poorly *Company X* implemented their security." Or maybe it's even "look how leet my hacking skillz are." Whatever it is, become aware of your message and keep it consistent. 

To create your structure, it's best to create an outline. Start with just one sentence as your root node (the message of your talk) and recursively create sub-nodes - Breadth first, obviously – until you've reached a depth that seems good for you. (If you haven't had the pleasure to learn about recursion or trees in computer science yet, you can also just start with one sentence and flesh that out until you get a more and more detailed outline. But it won't sound as nerdy.) 

You are very much allowed, even encouraged to move things around in your outline while developing it. Once you flesh it out more and more, a sane sequence of points should emerge, and you can begin creating slides for each sub-heading of your outline. But don't throw it out afterwards: The outline should be like a blueprint of your talk. Your slides just show what will be on the projector, but your outline shows your whole talk.

Other than that:

- Introduce yourself at the beginning of your talk (if you're not introduced). But don't spend more than two sentences on yourself, three if you're a Nobel or Ig-Nobel laureate.
- Have a title slide.
- Do **not** explain the joke on the title slide!
- Have a final slide, with your name, email and where to get the source and further information for this talk.
- *After* the final slide, have a slide for sources and citations.

## You Don't Need Slides

Slides are definitely not the most important thing about your talk, but they comprise the area where hackers and hacker-like people make the most mistakes. Maybe because we all stare at screens so much? In any case...

**You should be able to hold your talk without any slides.**

Yes, you have diagrams and screenshots and cat pictures and *oooodles* of data, but the art you are performing is *public speaking*. People are there to listen to you, to be in the same room with you, everything else is secondary. You are on stage as an ambassador to your idea, and not just as the person who clicks the "Next"-button on the remote.

If the projector fails, or your computer shreds all the slides of your presentation, you should still be able to confidently walk on stage and tell the world about your idea. Think about it as one less thing that can go wrong.

What about those who missed my talk, you ask? They will be unable to download your slides and understand my idea! That is correct. However, they can just get the audio from your talk and have a killer podcast to listen to on their way to work. Or you could even go the extra mile an create a transcript afterwards, but that's pretty optional.

## What Slides are for

Slides are there to **enhance** your talk, not **be** your talk. So, what should you put on your slides? Let's start with what *not* to put on slides:

**Never put the things you want to say on a slide.**

Imagine a novice speaker with a great idea. Their slide reads: "Methods to improve Cat Photo detection: 1. Fur Detection Algorithm. 2. Matching Intermittent Aural Output Widgets. 3. Employ Humans."

To this, they say the following words: "We have various methods to improve Cat Photo Detection. First, we have a fur detection algorithm. Next, we implement Matching Intermittent Aural Output Widgets. Third, we can use humans to improve our output."

Humans get bored very easily when they receive the same information on different channels, and tune out of the channel that seems slower to them. Notice how you almost certainly skipped parts of the previous paragraph? It's even worse in an actual talk. 

Instead, **your slides should complement your talk**.

An improvement over this example would be to split the slide into three slides, each showing relevant *background* information about the detection method: An example of the fur detection in action. The words "or MIAOW for short." Some cat photos that are detectable by those methods. Or you could simple display "Cat Detection Methods" as the headline to that part of your talk.

Have a look at this video of Stephen Colbert's *The Word* on Ayn Rand (it's 6 minutes of presentation awesome):

<embed style="display:block" src="http://media.mtvnservices.com/mgid:cms:video:colbertnation.com:221335" width="288" height="247" type="application/x-shockwave-flash" wmode="window" allowFullscreen="true" flashvars="autoPlay=false" allowscriptaccess="always" allownetworking="all" bgcolor="#000000"></embed>

Heres a [Link, in case the embed does not work](http://www.colbertnation.com/the-colbert-report-videos/221335/march-11-2009/the-word---rand-illusion).

* Most of the time when Colbert is speaking, there is just background behind him. No slides, you just focus on the speaker.
* Videos are full-screen (with a banner citing the date of publication, doubling as a source here), but the talk would work without it. They back up Colbert's claims, and are well-selected.
* Points are made by Colbert, and the slides emphasize them, serve as examples or as proof, allowing him to stay on his message. (In this example, they also contradict him for comedic effect. You should probably not do that.)
* If Colbert talks about something, like Rand's book, sales numbers, or specific quotes, the slides show that.

So, in summary: 

1. Your slides are way less important than your talk.
2. They should complement your talk, not structure it.
3. Never ever put the things you want to say on a slide.
4. Really. Never do that.

## Unclutter Your Slides

Sometimes, when presenters want to show an image, their slide contains the following: 

* the title of their talk
* the title of the subsection of their talk they're in right now
* the logo of their organization
* the GNU logo
* their website address
* their name
* the current date
* source information for the image
* license information for the image
* a title for the image
* **the actual image**
* the title of the following slide
* the title of the previous slide
* a table of contents for their presentation, with the current slide highlighted by a small yellow arrow

Say no to all that clutter. Show exactly what is needed a that moment in your talk. The people in the audience know who you are, because you introduced yourself at the beginning. They know your talk's title, because it is on the actual *fahrplan* of the event. 

All those redundant elements recurring on each slide give you, the presenter, a false sense of structure. From a bird's eye view, your slides look way more structured than the chaotic, minimal slides I'm proposing, but to your audience's point of view, all the non-necessary elements do is take up space you could be using for content.

So, start from a clean slate. Decide anew for each and every slide, what is really necessary. Are you talking about three distinct things and so people in your trial run get confused about which part of your presentation you're in? Alright, add sub-headings! Is the logo of your organization important for this slide? Put it in! But never just copy the previous slide and change the title. Every element should be needed, and if you don't need any of them, that's okay, too. A blank slide in between doesn't hurt you – it actually focuses the audience's attention back to you.

## Images, Videos and Graphs

As a corollary to the previous point, if you want to show an image, show the image. Do not clutter up your slides. 

I prefer to embed author/designer/photographer information as a inset to the image, just as news agencies and websites do. Any further information can be pushed back to your Sources and Citations slide. 

Usually people live some whitespace around the image in question. I'd argue against that. While whitespace in general (and on a regular computer screen) is good, your projector automatically has whitespace around the projection screen. So if the resolution is high enough (please, please, **please** get something with a high enough resolution) and the motive allows it, feel free to go edge to edge with your awesome image.

Generally speaking, images are a good idea. You can use them to illustrate your point, show things that are hard to describe, or just provide comic relief. If your topic lends itself to good imagery, take some time to include that in your talk, and your audience will love it. Also, using more images will help you get away from those horrible clichéd bullet-point-by-bullet-point-this-is-what-I-am-going-to-say-slides. I'd rather you used the clichéd background-image-plus-one-word-slides instead. 

What about videos? I say make those fullscreen as well! Also, be careful to use them sparingly. Use short videos, and only when necessary. People generally want to hear you speak, not watch a prerecorded video.

And Graphs? Okay, graphs can be used in two ways: Either they are complicated but important, or they are uncomplicated but explanatory. Uncomplicated but explanatory is easy: They are the graphs you show on your slide to underpin something you're saying, but you don't have to explain them. They are your basic output-over-time- or global-warming-by-pirates-graphs. Don't even acknowledge them, just throw them up to give yourself more credibility. 

Complicated but important is a different beast. Take your time with these. (Ideally, you'll only have one such graph in your presentation. Even more ideally, you'll be able to avoid them altogether. But, here we are, so let's talk about them.) First, simplify them as much as possible. Then, put them up on the projector and prepare to spend a whole minute or even two on that slide. Explain why you're showing that graph. Explain what can be seen. Show *how* that can be seen. And let it sink in for a moment.

Regardless of which graphs you show, make them simple. As simple as possible. Remove any axes, data points, units, that are not strictly necessary to the point you are trying to make. Use black and white for the background, and one or two colors to emphasize your point. Enlarge parts that you want or need to reference. And maybe even [make them fun](http://memebase.cheezburger.com/graphjam).

## Source Code Slides

You should probably not put source code on your slides. People will not be able to read it from the back, and even those who *can* read it won't have time to completely *get* it, because you're talking, remember? 

In ninety nine percent of all cases, it's better to include a link to the repository in your sources than to show actual code. But, sometimes you need to highlight a language feature, or show a very specific part of a program, so here are my rules for showing code:

1. As little as possible. Only show 3-5 lines at most. Can you make anything simpler? Do it!
2. As large as possible. The font size for this should be *huge*, so even the people in the back who can only see half of your slide can get a glimpse at it.
3. Monospaced and syntax-highlighted. Do everything you can to improve legibility.

## On Demonstrations

The idea of an actual demo always sounds awesome. Why show dry slides when you can show the real thing, live on stage? In reality, demos are often not as cool as they sound. They crash, they get different results than expected, and they take too long. And even if they work perfectly, they might just not convey the message you want them to. So use them only when you really have to, and apply the same rules as for source code slides: Reduce the demo to its absolute minimum and make it as understandable as possible what's going on. Also, your demo should have as little dependencies on outside factors like network access as possible, and **make sure you can continue if the demo is not working somehow**.

That being said, a good demo can improve a talk tenfold.

One of the best demos I ever saw was for a [Hash Collision Exploit in Web Servers](http://arstechnica.com/business/2011/12/huge-portions-of-web-vulnerable-to-hashing-denial-of-service-attack/). (There is a link to a video of this presentation in the "Examples of Good Talks" section later.) The hackers proved that, by sending certain values to certain web apps, they could slow down a single request by almost ten times. 

After explaining all the necessary prerequisites, the presenters switched to a terminal, pasted a command and said "this is a normal web request to this web app." The request was answered by a second line in the terminal almost immediately. "Now," the presenters continued, "this is our specially prepared request." They pasted another, single-line, command, hit enter and ... nothing happened. After a few seconds, the audience got that the server was *still* processing the request, and would continue to do so for almost ten seconds. The presenters received thunderous applause.

Apart from having a very interesting topic, these presenters kept their demo very short, and to the point. They also ran their demo locally, without requiring any network access or internet servers to work correctly. You can not expect the network at a conference to work reliably. No, not even at the Congress.

When it doesn't work, have a backup ready. Maybe one of your co-presenters can try to fix stuff while you [tell a short anecdote about your project or yourself](http://www.youtube.com/watch?v=xiSBSXrQ8D0). Maybe you can skip the demo entirely, or try again at the end of your talk. But don't fiddle around endlessly while the energy in the room evaporates. 

## How to Speak

You already know how to speak. For your talk, just slow down. Use short sentences, way shorter than you're used to. They may seem stupid on paper. But they will help your audience understand you better.

Also speak *slowly*. You should also repeat your most important points. Because Repetition helps your audience remember the important bits.

Did I already mention that you should slow down your speaking? I mean it. You'll feel ridiculous at first. But your audience will thank you, and after a few practice runs of your talk, the weirdness factor will have worn off.

Slooooow.

If you slow down your speaking, you will also automatically speak more clearly. Still, try to enunciate. Form your words with care instead of slurring them. You don't have to achieve the speech patterns of a news anchor, but speaking too clearly is way less of a problem than speaking in a way that has people straining to get what you are saying.

If you want to reach the holy grail of speaking, you also need to show some energy. Through your voice and your words and your movement, show people that the topic is important to you, that it fascinates or horrifies or amuses you. Because if you don't seem to care about your talk, why should your audience? Don't be over the top though – you're not an actor in a cheesy theater production. Smirk at the right places, raise your voice at the important points, and pause after them for a second or three. Once you speak slowly, deliberately and passionately, your talk will gain a lot of quality.

> **Aside: What if you can't remember your text?**
> By the time you actually give your talk, you should almost know it by heart. You don't need to know how each sentence is formulated, but even your minimalistic slides should give you enough pointers to get you going for each slide. 
> If you're like me and find out that this is not enough for you, print out your outline. If you have a speaker's desk (see also below: know the room), you can just put your printout there and glance downwards from time to time. Otherwise, print it on heavy paper and cut it into cue cards.

## Prepare Yourself

You should **rehearse your talk a lot**. First, just take your outline and speak along to that. Put up your slides on your computer screen and switch slides at the appropriate moments. You will stumble a lot over things that looked so smooth on screen or in your outline. Correct them, and move on. 

Once you can go through your complete talk without stumbling, fiend a friend whose criticism you're prepared to accept, and rehearse the talk in front of them. This time, you might experience some stage fright. This is *good* – it prepares you for the real thing. Your friend will probably have some questions or improvements. Change your talk to account for those and rehearse again. 

During rehearsals, not only change your outline and slides to better fit your message, but also change your tools to better fit your talk. If your IR clicky thing doesn't work because you're walking around too much, get a bluetooth one. If your printed outline hinders you, either change it to cue cards or learn your outline by heart.

Rehearsing your talk over and over will seem tedious and pointless. But you will be *so* glad you did it at that one moment where your name is called out and you have to walk on stage. The feeling of being well-prepared is awesome and will give you a much-needed confidence boost.

## Know the Room

Try to find out the room where you're giving your talk and get a feel for it before your presentation. That includes simply entering the room before it is full of people and trying to get a feel for the atmosphere. If you see the stage from the view of an audience member, you'll get a better feeling for how your talk will affect people in the audience.

If possible, also have a look at the projector tech you're going to use and try it out. 

* Do you have the correct adapters? If not, you should scramble to find them. 
* Is the projector's color range and temperature similar to your screen's? If not, change your slides so that your colors will look good and everything is readable. 
* Does the projector cut off any important parts of your slides? Rearrange them.
* Do you use sound or videos? Try them out so you'll know they work and have the correct volume. 

You should also really talk to the organizers of the conference about the peculiarities of your presentation. Do you use sound or videos? Need network access for that demo? Is your live tiger going to be a problem? Will there be a Q&A after the talk? These are all important questions to ask and discuss a few days before your talk, and good conference organizers will gladly answer your emails about them.

## Break a Leg!

Theater performers think it's unlucky to wish each other good luck before going on stage. So they tell each other to [break a leg](http://en.wikipedia.org/wiki/Break_a_leg) instead. And with that, I'll leave you. May your good idea get the awesome presentation it deserves!

----

## further resources
- [Giving a Talk](https://www.cs.duke.edu/brd/Teaching/Giving-a-talk/giving-a-talk.html) by and for computer scientists
- [Tension in Story Telling](http://lisezvous.blogspot.de/2010/03/tension-and-storytelling.html)
- [Elements that help you achieve Tension](http://shelleywidhalm.wordpress.com/2012/06/24/achieving-tension-in-storytelling/)
- [Story Telling](http://www.themoleskin.com/2010/03/storytelling-in-business-tension-makes-your-story-interesting/)

## examples of good talks
- gruber?
- merlin mann
- Colbert?
- Gemmel
- https://www.youtube.com/watch?v=XkWetbQHWlk
- [Hash Collisions 28c3](http://www.youtube.com/watch?v=R2Cq3CLI6H8) and [Hash Collisions 29c3](http://www.youtube.com/watch?v=wGYj8fhhUVA) see 25:00
- [27C3: Adventures in analyzing Stuxnet (Bruce Dang from Microsoft)](http://www.youtube.com/watch?v=rOwMW6agpTI)
- [29C3: Many Tamagotchis Were Harmed in the Making of this Presentation](http://www.youtube.com/watch?v=WOJfUcCOhJ0) (Her voice is quavering a little because she seems nervous, but the talk is excellent.)
- [Principles of Lighting and Rendering with John Carmack at QuakeCon 2013](http://www.youtube.com/watch?v=VUxcVzpeFqc)
- [Aimee Mullins: My 12 pairs of legs](http://www.ted.com/talks/aimee_mullins_prosthetic_aesthetics.html)
- [Webstock '11: John Gruber - The Gap Theory of UI Design](http://vimeo.com/21742166)
- [Webstock '11: Merlin Mann - Scared Shittless](http://www.youtube.com/watch?v=Lk0hSeQ5s_k) Mann is well known and has kind of a "special" way of giving talks, but it he is a very good speaker nonetheless. Also, have a look at his awesome slides. OR: [Inbox Zero](http://www.youtube.com/watch?v=z9UjeTMb3Yk)



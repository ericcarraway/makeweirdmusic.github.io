---
layout: post
title:  "Soundslice"
date:   2016-02-01 19:14:46
artist: soundslice
member: adrian-holovaty
author: anthony-garone
image: soundslice
category: gear
permalink: /gear/soundslice
redirect_from:
  - /interview/soundslice
  - /interview/adrian-holovaty
oneliner: Soundslice is a game-changer for sheet music on the web.
seo_description: Interview with Adrian Holovaty, co-founder of Soundslice.com.
seo_keywords: open source, sheet music, html5, tablature, guitar, innovation, keybord, piano, living sheet music, javascript
front_page: yes
draft: no
has_video: yes
youtube_id: ucgcR3-8BVs
file: https://s3.amazonaws.com/audio.makeweirdmusic.com/gear/soundslice/soundslice.mp3
duration: "43:01" #audio length in min
length: "73495813" #filesize in byte
explicit: "no" #other option is no
block: "no" #means is shown in itunes
---

## Soundslice

Soundslice is an incredible tool for musicians that brings sheet music to life on the web. It lets you put your sheet music into a web page without any PDFs, Flash players, browser plugins, special MIDI stuff, etc. Here's an example of Soundslice in action:

<iframe src="https://www.soundslice.com/scores/39032/embed/" width="100%" height="500" frameBorder="0" allowfullscreen></iframe>

As you can see (and hear!), it plays anything you throw at it giving you plenty of options, like a piano viewer, live guitar fretboard, notation synchronized with tablature synchronized with audio, and it lets you upload multiple audio and video tracks to accompany the sheet music. Within the site is the capability to create and sell collections of music lessons where you keep 70% of the revenue from each sale. It's frikkin' awesome!

**[Still don't get what Soundslice does? Check out their site!&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](http://soundslice.com)**

## Some Context

Below is my interview with [Adrian Holovaty&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](http://www.holovaty.com), co-creator of Soundslice, gypsy jazz guitarist, educator, and one of the world's leading web software developers.

In May 2013, a friend told me about [Soundslice&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](http://soundslice.com). I checked it out and was blown away. My first thought was: "Finally, someone has built something I've been too lazy to do myself!!" I was stunned to see that it was built by the guy who'd started the [Python&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://en.wikipedia.org/wiki/Python_(programming_language))-based [Django web framework&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://en.wikipedia.org/wiki/Django_(web_framework)). My full-time work is in web-based software development, so I already knew about Adrian peripherally. To find him behind Soundslice was exciting because it was nice to see another programmer/musician.

We started exchanged lengthy emails about Soundslice (really, I mean *lengthy*) regarding features, bugs, and ideas for the future of the product. We've been in touch since then (I can't believe it's over 2.5 years!) and finally met in person in Chicago in October 2015, just weeks before he moved to Amsterdam with his entire family.

At the end of 2015, I thought it would be cool to feature tools and gear to help people make weird music and Soundslice seemed like a great first choice. I absolutely love the product and want to get as many musicians using it as possible. I strongly believe it is the most important music product on the Internet.

So, I reached out to Adrian and asked if he'd be interested in doing an interview. He kindly obliged and we made it work despite the significant difference in time zones between Phoenix and Amsterdam.

The interview was conducted on Monday, January 18, 2016 at 5AM Arizona time via Google Hangouts.

## Interview Audio (Podcast)

{% include audio.html podcast=page.file %}

## Interview video

Here's a video of the interview:

{% include video.html vid=page.youtube_id %}

## Interview transcript

Anthony: Hey, this is Anthony from MakeWeirdMusic.com. I'm here with Adrian Holovaty, who is broadcasting to us from Amsterdam. Hello Adrian!
{: .interviewer }

Adrian: Hello!
{: .interviewee }

AG: Good afternoon! It's 5AM here.
{: .interviewer }

AH: Yeah, 1PM for me.
{: .interviewee }

AG: I was wondering if you could introduce yourself and talk about Soundslice, where the idea came from, and... Go ahead! You do the talking!
{: .interviewer }

AH: Sure! So, I'm Adrian, I'm a musician and web developer from Chicago. I just moved to [Amsterdam&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://en.wikipedia.org/wiki/Amsterdam) about two months ago and I run a website called Soundslice. The premise is it's trying to <span class="important">give you all the tools possible to learn a given piece of music all from your web browser</span>. We do that by giving you slowed-down looping, listening to recordings, looking at sheet music, looking at videos, combining all this stuff into a single interface to make it easy to learn tunes. You sort have to see it to really understand it, but yeah, that's my full-time thing. It's a two-person company and it's pretty awesome, if I may say.
{: .interviewee }

AG: Yeah, I absolutely love it. I think it's such an incredible piece of technology. Can you tell me where the idea for Soundslice first came from? Why did you decide to take it upon yourself to start a company around online sheet music?
{: .interviewer }

AH: Well, I do a lot of [transcribing](https://en.wikipedia.org/wiki/Transcription_(music)). I've been doing this for probably more than 10 years and my process for all those 10 years has been: listen to a recording, write out either on paper or in a plain text file on my computer the tab of the guitar notes.
{: .interviewee }

I can read music, but not very well, so I just use tab. For years I would painstakingly transcribe these old jazz recordings. [Django Reinhardt&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://en.wikipedia.org/wiki/Django_Reinhardt) jazz guitar stuff. And I would come back to it a week later and I wouldn't even understand my own transcription even though I did all the work of transcribing it. So, I would always have to go back to the original source recording and listen to it in tandem with the tab that I'd written out.
{: .interviewee }

That got me really really craving a way of <span class="important">seeing tab synced with a real recording</span>. Of course, there have been for many years programs that show you tab and they play a synthetic MIDI kind of a sound, but I hate that. It's horrible. <span class="important">It's a horrible way to learn how to sound</span>, how to make your guitar sound a certain way because it's not a human playing it.
{: .interviewee }

So, I firmly believe the best way to learn (at least for my way of learning), <span class="important">the best way for me to learn a tune is to listen to a real recording. I wanted to make something that let me marry the two: a real recording along with tab or sheet music</span>. So, that was the original version of Soundslice. That launched in 2012 and it worked for YouTube videos where [you could find/search for any YouTube video on our site and transcribe it&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://www.soundslice.com/completed/) and the transcription would be such that it would be linked with video.
{: .interviewee }

So you actually say, "From this moment in the video to this moment in the video, it's playing this note on this string in this fret." It's very painstaking kind of a process. It got a following, but the number one bit of feedback that we had was, "Please add sheet music. Not just tab, because I'm a piano player or a horn player and I want to use it, but I can't use it if it's just tablature."
{: .interviewee }

So, we decided to just completely make a new product that was oriented around traditional sheet music instead of just tablature. Of course it still does tablature. That's what we have now. So, the premise is you can create these interactive sheet music things, for a lack of a better term.
{: .interviewee }

AG: Well, I think that's a great high-level answer to that. I know that you've put a tremendous amount of effort into Soundslice and I consider it a pioneering piece of web technology because all the sheet music, the way you draw it out, the way it works in all web browsers, that makes it totally unique. Can you talk a little about that?
{: .interviewer }

AH: Well, all *newer* web browsers. A lot of the stuff behind the scenes is pretty bleeding edge. In other words, it only works in modern web browsers. So, browsers that are younger than 3 or 4 years old. Basically, everyone is using a modern browser these days. If you're stuck on an old Internet Explorer version at your office, it wouldn't work for you.
{: .interviewee }

But, just as an example of the bleeding edge... I'll give you two examples of living on the bleeding edge. One is audio on the web.
{: .interviewee }

<span class="important">Audio in web pages has always been a fiasco</span>. For many years, Flash was the only game in town. You had to use Flash in order to play audio on a webpage. And, fortunately there's a new thing called the [Web Audio API&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://en.wikipedia.org/wiki/HTML5_Audio). I won't get into all the geeky details, but there's a new thing that lets you play audio in web pages and that's what we use. However, when we first added that to Soundslice, it was so new that an auto-update of the Google Chrome browser actually broke Soundslice because they changed the way that they wanted the thing to work. So, I had to fix Soundslice to deal with new *new* stuff instead of the old stuff. It was kind of weird.
{: .interviewee }

So, the second thing is we're about to launch [offline mode&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://www.soundslice.com/blog/29/introducing-soundslice-offline-mode/). Later today, in fact.
{: .interviewee }

<div class="video-wrapper"><iframe width="420" height="315" src="https://www.youtube.com/embed/FtoGbbH3DYA" frameborder="0" allowfullscreen></iframe></div>

AG: Oh, congratulations!
{: .interviewer }

AH: Actually, by the time this is published, it'll exist. Hopefully... Unless it turns out to be horrible. In my blog announcement, which I've just drafted, I point out that it only works in Google Chrome at the moment, but it will work with Firefox in *one week* because the upcoming version of Firefox will support this technology. So, it's super-new stuff.
{: .interviewee }

AG: That's awesome. Can you tell us about how you ended up building the sheet music component and where that has led... Actually, you should probably talk about what the product offerings are. What do you sell through Soundslice and what are your different customers like?
{: .interviewer }

AH: There are three parts of the product/business. One is that you can buy--it's a [lesson marketplace&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://www.soundslice.com/learn/)--you can buy music lessons through our site. It's pre-recorded music lessons and we've got 10 courses at the moment and a couple dozen transcriptions of music <span class="important">all done by indie artists and they get the majority of the revenue. 70%.</span>
{: .interviewee }

<div class="video-wrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/oqyJ8n-LXeU" frameborder="0" allowfullscreen></iframe></div>

The premise there is: it's like what I want when I learn a tune. I don't want just the transcription, I want it synced up with the real recording so I can actually hear it. So, what you get when you buy these things is <span class="important">lifetime access to transcriptions or music lessons that are all written out synced with audio</span>, and in some cases video, of the teacher showing you stuff. So, that's the first part of the business.
{: .interviewee }

The second part is we have a product for music teachers called [Soundslice for Teachers&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://www.soundslice.com/teachers/) which lets them <span class="important">create these interactive pieces of sheet music and then share them with students</span>. That's for a monthly fee, $20/month.
{: .interviewee }

And the third part is [licensing to other companies&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://www.soundslice.com/licensing/), which is actually the biggest part of the business, but it's the part that our users don't really know or care about because it doesn't really affect them.
{: .interviewee }

We work with almost 30 separate websites at this point who pay us a monthly fee to embed our player in their own site. So, there's some big names there like [Guitar World Magazine&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](http://guitarworld.com), [TrueFire&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](http://truefire.com), which has awesome lessons, [Premier Guitar Magazine&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](http://premierguitar.com), [JamPlay&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](http://jamplay.com)... But not just guitar, it supports other instruments as well. It's just sheet music so it supports any kind of instrumentation that uses traditional standard notation.
{: .interviewee }

AG: Have you found adoption of Soundslice for guitarists to be the greatest? Or do you find that it's people all over the map?
{: .interviewer }

AH: It's definitely strongest in the guitar world just because that's where we come from and that's the people that I know that I was able to tell about it and it organically grows like that. With that said, since we launched the sheet music stuff, and specifically since we launched this [interactive piano/keyboard view&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://www.soundslice.com/blog/18/new-features-and-free-exercises-for-pianists/), it's been growing with other instruments too.
{: .interviewee }

<div class="video-wrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/SCydRrbSby4" frameborder="0" allowfullscreen></iframe></div>

So, I'd say piano is our number 2 instrument. There's a couple of piano instruction sites that license it. There's a couple other instruments, too, in terms of the licensing. Of course people use it for all sorts of stuff, like people put orchestral scores in there with 20-some instruments, or a high school band director put band pieces in there, which have 20-some instruments, percussion because we added support a couple months ago. It's all over the map. Most come as guitar, but yeah it supports everything.
{: .interviewee }

AG: What are some of the major challenges you've had to overcome building Soundslice?
{: .interviewer }

AH: Making it fast enough to work in a web browser. It actually assembles the sheet music on the fly directly in the web page as you request it. So, the reason for that is [it actually wraps to fit your device&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://www.soundslice.com/blog/28/new-smooth-scrolling-during-playback/). If you're on a super small screen, <span class="important">it'll wrap the notation to fit the screen</span> and only put one or two measures on every line as opposed to if you're on a huge desktop screen, it'll put 8-or-so measures.
{: .interviewee }

Because that's all happening directly in your web browser, it's doing a ton of work and it continues to be an interesting technical challenge to make that fast enough so that it's nice and responsive. You don't actually know that it's doing that stuff behind the scenes. There's a lot of technical challenges like that. But then the non-technical challenges are just getting people to know about it and getting music teachers to use it and getting musicians to sell their lessons on our marketplace platform.
{: .interviewee }

<span class="important">I'm a technologist first and foremost and I always seem to discount the non-technological stuff</span>, but that's really--that's a challenge because I don't know about it as much as I know about the tech stuff.
{: .interviewee }

AG: What about the drawing of sheet music? I would imagine if it was an easier thing to do, more people would do it, but you seem to be one of the only websites out there that allows for actual sheet music rendering in an HTML website.
{: .interviewer }

AH: Yeah, <span class="important">it's a deceptively very, very hard task.</span> Compared to drawing text--if you have an essay or a newspaper article, you have word wrap and, say you have justification where you have the words line up on both sides of both margins (left and right). Even someone who's not a computer programmer can sort of figure out how that's done. You just start at the left and keep putting words on the line until you run out of space and then, inevitably, there's a tiny bit of space where the next word wouldn't have fit, so you take that space and divide it among the other words and you're done.
{: .interviewee }

With sheet music, it's that kind of thing, but it's made probably a thousand times more difficult because you also have a lot of other constraints. If you have more than one part, more than one instrument, if they're playing at the same time, the notes have to be perfectly vertically aligned. So you have to take that into account when you're doing that justification. And then there's the fact that the horizontal space after a note is proportional, but not *exactly* proportional, to other notes.
{: .interviewee }

<div class="video-wrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/8GGciFtk9ZU" frameborder="0" allowfullscreen></iframe></div>

So, the horizontal space after a whole note is *more* than the horizontal space after a half note or a quarter or an eighth note, but it's not perfectly proportional. If it were perfectly proportional, it would be way too long. Although, as a side note, that type of layout is used for dyslexic musicians in that they really benefit from having a perfectly proporational note spacing. I'd like to implement that at some point because, actually, it would be easier than the real way of doing it.
{: .interviewee }

So, you have to account for that horizontal space, you have to account for the vertical alignment, and you have to nicely proportion it so that it's justified because that's just the convention of sheet music throughout the centuries. It goes all the way across the page, there's none of this ragged right like we have in text. So, just that in itself is a tricky programming problem. And then to make it fast is what really makes it challenging.
{: .interviewee }

I think that's why we don't see a lot of this kind of stuff being done. <span class="important">It's just a lot of work and you have to juggle a lot of stuff.</span> And at the same time, there's an element of art to it where it has to look good and feel good. I'm still learning how to best make it look good and feel good. And that just comes, I think, with looking at a lot of old pieces of sheet music and talking to musicians and trying to read it yourself and figure out what feels and looks good to you.
{: .interviewee }

AG: How much have you had to learn about sheet music layout and the traditional practices of how people used to it by hand and computer programs that do it now?
{: .interviewer }

AH: Well, I started from basically *zero* and I have learned *a lot*, so the answer is "*a lot*." I've learned about the traditional practices. It's called "[music engraving&nbsp;<i class="non-mwm fa fa-external-link-square"></i>](https://en.wikipedia.org/wiki/Music_engraving)" because in the old days it was actually engraving on the back side of a metal plate. You'd do everything in reverse with these little stencils and a hammer banging into this metal plate in reverse and then, when it's reversed and it's printed, the music prints.
{: .interviewee }

<div class="video-wrapper"><iframe width="420" height="315" src="https://www.youtube.com/embed/345o3Wu95Qo?rel=0" frameborder="0" allowfullscreen></iframe></div>

So, a lot of those techniques are clearly outdated, but some of them still sort of make sense. Like, there's a thing called "casting off," where you consider the music that you need to print and then you consider the amount of space you have and you align it so it's nice and even on the printed page. So, <span class="important">we do something like that, but digitally.</span> There are other bits where the classic human, by-hand engraving is sort of replicated in software.
{: .interviewee }

AG: That sounds like a tremendous amount of work.
{: .interviewer }

AH: This is way too geeky and dumb. If anyone's still interested, I'm surprised.
{: .interviewee }

AG: I'm definitely interested. <span class="important">This site is all about details that most people wouldn't be interested in</span>. So, please go ahead and get as detailed as you like. Can you tell us how you use the website? I'm sure it's solved some personal problems for you. Soundslice is filling several needs in your life. Where did it come into play?
{: .interviewer }

AH: Totally! <span class="important">When I want to learn a new piece of music, I stick it in Soundslice.</span> It's super effective. That's my way of learning now. It's also my library of stuff that I'm working on. Just last night, I was transcribing a YouTube video if this really nice chord melody thing and I pop it into Soundslice so that I can come back to it later and hear the original and see the YouTube video and see the notes.
{: .interviewee }

So, yeah, I love it just for learning stuff and also keeping track of all the stuff that I've learned and transcribed. And then, on the teaching side, before I just moved to Amsterdam, I taught a weekly gypsy jazz guitar class in Chicago for four, maybe five, years. I loved using it with my students. I'd show them something in class, maybe it's like a lick or a chord progression or something, and then I would go home and record myself playing it and pop it into Soundslice and then send the students the Soundslice thing.
{: .interviewee }

To a person, they all say, "Wow! This is super useful." Some of them were even joking, "Why do I even need to come to class? I just want to use this Soundslice thing." <span class="important">Because you can just listen to it 20 times in a row, really get a sense of it, do it at your own pace, slow it down, you don't have to worry about annoying the teacher or annoying your fellow students...</span>
{: .interviewee }

So, I've really enjoyed using it with students, too. Then we have this new lesson marketplace. I've been learning some stuff from that as well. Some neo-soul guitar, which I know nothing about. I *did* know nothing about, but now I know a little about because we have some courses. And it's some cool stuff.
{: .interviewee }

AG: I'm sure having a product like this has introduced you to all sorts of new kinds of music and ways of using it that you hadn't anticipated. Can you describe anything like that?
{: .interviewer }

AH: Yeah, one interesting one is with a high school band. They are using it in comparing their own band's performance to a real performance. So, it's like some big piece of music, maybe it's like a 5-minute long band concert thing, and they record their own high school band playing it, they pop it into Soundslice, and then they get a source recording from some professionals who play the same exact piece, the same arrangement, and they also throw it in there and then, using the fact that we have multiple audio sources, they distribute it to their students (the Soundslice interface) so the students can actually see--they press play, it starts off with the professional recording.
{: .interviewee }

<div class="video-wrapper"><iframe width="420" height="315" src="https://www.youtube.com/embed/ynK3rsdIubc" frameborder="0" allowfullscreen></iframe></div>

You see the playhead go by and any time they want, they can switch back to their high school performance and just get a sense as to how it differs, what parts are good, what parts are bad. I had another example of a teacher who was dealing with a student who did not--the teacher told the student, "Look, you're not playing it right. You need to change your intonation." Or whatever it was. The student was like, "No, I'm playing it right. It sounds good!" So, then the teacher recorded himself playing it, put it in Soundslice and put the student's recording in Soundslice and the student was able to compare them and actually got to see, "Oh, yeah, now I see what's up."
{: .interviewee }

And of course, you could have done that just by sending mp3s, but the difference is when you see it synced with the sheet music and everything's synced--as soon as you toggle the audio, it goes to the other performance and it picks up where the other left off, <span class="important">it just takes it to the next level.</span> So, those are some use cases that I wouldn't have thought of.
{: .interviewee }

AG: One thing I love about Soundslice is it is not in any way detrimental to the music industry. It's not taking something away or giving something away for free. You actually are supporting musicians. Was that ever your intent? Do you have any sort of stance on Soundslice as a tool for musicians to support their art as craft?
{: .interviewer }

AH: Definitely. That is fundamental to my beliefs--our beliefs as a company. Even though that sounds a little bigger than it should be because it's only two people. "*Our company's beliefs!*" We've used that as a guiding principle. There have been a couple cases where we had a question, something came up--like, one of the musicians who's selling lessons with us wanted to re-use his lesson as sort of a demo for a job he was trying to get that maybe was a little competitive with Soundslice and so we were faced with the question: Well, we did a bunch of work to help him get into Soundslice and now he's going to use that and try to turn around to compete with us, and we made the decision...
{: .interviewee }

<span class="important">We look back at our fundamental principle: We help musicians.</span> And we decided, "Of course we'll help him do it." We're here to help musicians, not only the teachers who use us to teach their stuff, but the students who learn through our software. So, yeah, I completely see it as a tool *for* musicians first and foremost. It's not about connecting with your fans or any of the stuff that a lot of other music companies do, especially in the internet startup world.
{: .interviewee }

A lot of the music stuff is about streaming music or figuring out when bands are gonna be in your town or merchandise stuff. With us, <span class="important">we're all about the musicians and actually learning music.</span> We don't know or care anything about gear. It's just, literally, playing music. That's a reflection of me, too, because I don't know anything or care anything about gear or touring or merchandise or recording, I just care about playing good music.
{: .interviewee }

AG: What's the response been from the musical community and your musician customers, the full-time musicians that are using Soundslice?
{: .interviewer }

AH: Man, it's basically universally loved. It's funny, when we get emails from people who just found out about us and more than half the time, they say, "How did I never know about this?!" It's kind of a secret because we have done zero marketing and we're super small potatoes so no one really knows about us. But yeah the response has been tremendous. People really, really like it. So, yeah, marketing suggestions welcome!
{: .interviewee }

AG: Are there any musicians, like are you selling a lot content through lessons and these transcriptions? Or is it still kind of an up and coming thing as part of your business model?
{: .interviewer }

AH: It's somewhere in between up-and-coming and selling a lot. <span class="important">I think if you asked the musicians who sell their lessons in the marketplace, they'd be very happy with the amount of money they've made so far.</span> For instance, one of the people in the marketplace has been a professional musician since the 1970s. he's done many albums, tours, instructional materials--you name it, he's done it. He said after having launched his stuff on Soundslice for only a few days, "Wow, this in terms of return on investment for the amount of effort I had to make for the amount of money and just personal fulfillment I've gotten out of it is the best thing that I've ever done in my music career." I gotta get him on video saying that.
{: .interviewee }

AG: Yeah, you do!
{: .interviewer }

AH: From the teacher's perspective for these lessons in the lesson marketplace, you record them once. And of course it takes some time to plan out your lessons plan and do the recording and all that, but from then on, you just sit back and watch the money come in and you're done. It's the whole "make money while you sleep" thing.
{: .interviewee }

<div class="video-wrapper"><iframe width="420" height="315" src="https://www.youtube.com/embed/oNl19ANnoW0" frameborder="0" allowfullscreen></iframe></div>

And of course the <span class="important">students love it because it's this unparalleled learning experience</span> where you've got video of the instructor, they've got exactly what they're playing synced with the video... it's awesome! At a price point that's less than an hour long lesson or workshop with the same exact person where you would get probably 5% of the content.
{: .interviewee }

AG: That's an interesting thing. Can you tell us how much more rich an experience Soundslice is for students and teachers than just "here's a book, study it" or "here's a video, go watch it?"
{: .interviewer }

AH: Oh man... So the book... <span class="important">Book is the worst because you're trying to describe something using the wrong sense.</span> You're trying to describe sound with sight! It doesn't make any sense! That's like writing an essay about a smell. It doesn't make any sense at all. If you want to learn music, you've got to listen to it with your ears! That's like my fundamental thing of Soundslice, the fundamental philosophy. So, learning from a book--bleh!
{: .interviewee }

Caveat! I don't want to go to extremes, so I'll say the caveat is if you're a professional musician or someone who's majored in music and you really know your stuff, you can then maybe see something on paper and hear it in your head, or you're just able to play it instantly. For that crowd, music on paper is totally fine. <span class="important">But for the 95% of us who are not like that, I don't think it's a good way of learning music.</span>
{: .interviewee }

And then just learning from videos, in comparison... If you learn from a YouTube video or a 1980s-style VHS tape, or an instructional DVD, it's okay but it's highly dependent upon the instructor and <span class="important">it's also highly inefficient in terms of the use of time.</span> It also has problems with the interface, it's very linear. I'll take these one at a time. So, the ineffeciency. If you're watching a DVD, you'll see the instructor say, "Okay, we're going to play this chord. First, you want to put your finger on the A string, 7th fret. Then you want to put this finger on the D string, 6th fret."
{: .interviewee }

Compare that to Soundslice where the instructor assumes that you're seeing the notation and the tab and the chord chart at the same exact time, so they don't have to bother with any of that. So, it cuts down all that BS that's really kind of a waste of time. So, that makes the lesson more efficient. And then, when it comes to the linear layout of video, <span class="important">I want to be able to skip parts that I don't care about.</span>
{: .interviewee }

If I'm on YouTube, the way I do that is I take the tiny little playhead and move it forward. How far forward? I don't know! I just kind of experiment and then see a split second of the video and see if the guy's done talking about the boring thing that I don't care about. But, if you have the Soundslice interface where it syncs the video with the notation, it doubles as navigation. So, you know *exactly* which moment the guy is finished talking with the thing you didn't care about. It's a better experience.
{: .interviewee }

Plus, for the things like the geeky features like slowing down the video without changing pitch and looping sections, you couldn't do that on VHS tape, maybe with some DVD players you can do looping, but it's a *really horrible interface.* Maybe you select a start point and then you have to watch it and then you hit the button at the stop point--*horrible interface* compared to just dragging on the notation with perfect precision. So much better.
{: .interviewee }

<div class="video-wrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/ahX8yJzJ2pA" frameborder="0" allowfullscreen></iframe></div>

AG: You haven't talked about how musicians actually *use* Soundslice. It is a presentation and playback mechanism, but it is not a composition tool--you don't draw out your notation within the app. So, how do people use Soundslice and get their sheet music and tablature into the app and then synchronize it with the video?
{: .interviewer }

AH: You're expected to create your notation in whatever program you're already using to create the notation. So, that could be Sibelius, Finale, Guitar Pro, Musescore (which is free), Notion... Basically any notation program out there because all those programs export something called MusicXML, which is the file that you then put into Soundslice and then we just grab the notation out of there.
{: .interviewee }

And then when it comes to syncing it with real recordings, you have a bunch of different options. You can upload an MP3 to us, you can put in the YouTube URL, Vimeo, you can upload video directly to us as well. And then once you've either uploaded or pointed at that audio or video, you use our syncpoint editor, which is this web-based thing where we show you the notation and we show you the waveform and all you have to do is listen to the recording and tap your keyboard on the downbeat of every bar. If you make a mistake, you can just mess around with the sync points manually by dragging them around.
{: .interviewee }

<div class="video-wrapper"><iframe width="420" height="315" src="https://www.youtube.com/embed/ZaZ1qu86YhM" frameborder="0" allowfullscreen></iframe></div>

So, hopefully it's easy to use and intuitive. It handles any case of syncing that you would want. A lot of people assume when they first hear about our syncing, they think that, "Oh, that means my recording needed to be recorded with a metronome. My recording wasn't recorded with a metronome, so it's gonna break your system, right?" Like, almost wanting us to admit failure or something. But, no we handle that too because <span class="important">you can put syncpoints wherever you want to put them.</span>
{: .interviewee }

Even if there's a fermata, a hold, or a pregnant pause in the music, you can have what we call inner-bar syncpoints where the first half of the bar is in time and then you can specify that the last two beats hang a little bit longer than just being strictly in time.
{: .interviewee }

AG: How many people have thrown you scenarios at this point that have been like, "Oh my goodness, I had no idea people would do that!" Total surprises or things that have introduced what you thought should be functional and then you realize what you've done doesn't support what they need... Those kinds of things.
{: .interviewer }

AH: That happens all the time. I love that, frankly, because that's my to-do list. That helps me prioritize what to do. My biggest challenge is when it comes to the product development, is prioritization. What do I work on next? I've got a huge list of stuff I want to add, but I don't know what to do first.
{: .interviewee }

So, basically, I was just chatting with a friend about this the other day. My little rubric is: the priority is decided 50% by paying customers, 10%-ish by potential paying customers, and then the remainder 40% by what I think would be good. Sort of my gut, what I want personally and what I think would be good. So, mostly driven by the paying customers. But, anyway, that doesn't answer your question.
{: .interviewee }

There are many cases where what people actually do with the software surprises me to the point where I have to fix it so it actually does what they want. That could be anything from the notation not supporting the things that they want to do to the way that they want to embed it into their site. Like when Guitar World Magazine started licensing our software, they put 8 Soundslice embeds in a single webpage. I had never actually tried that myself because I didn't have a reason to and it turns out that web browsers have a limit on the number of audio players that they can have currently running and in Google Chrome that is 6.
{: .interviewee }

So, in that example with 8 players, the first 6 worked and then the second 2 didn't work, so I had to fix that. So, yeah, you never know how people are going to use your stuff, but that's the name of the game of making software for human users.
{: .interviewee }

<div class="video-wrapper"><iframe width="560" height="315" src="https://www.youtube.com/embed/sDTZsOcc4sg" frameborder="0" allowfullscreen></iframe></div>

AG: What does the future of the product look like? Do you have a vision of the product 8- to 12-months out where you want it to be?
{: .interviewer }

AH: I don't. I probably should, but I don't think that long ahead. In 12 months from now--pfft, I have no idea what the world will be like. <span class="important">That's like an eternity in Internet time.</span>
{: .interviewee }

AG: What are some major features that you're working on for Soundslice that you wouldn't mind sharing?
{: .interviewer }

AH: So, one is offline mode, which I've been working on for a few weeks and it's launching today. It will have launched by the time this gets posted. And, let's see--at some point, I'd like there to be a notation editor, so you could just input the notation directly in Soundslice as opposed to having to use a separate program. I think that will start with the expectation that you'll just use our notation editor to massage the notation that you've already imported in there in case there was some import errors or you want to make some changes without doing a round-trip back to your notation program. Of course, that's a big project. [Laughs]
{: .interviewee }

The biggest thing is getting more lessons in our marketplace and getting more teachers to use it. For almost two years now, I've been working non-stop on the product itself and it's gotten to a point where it does 90% of what people want. <span class="important">It does 100% of what 90% of the people want.</span> For those other 10% of people, they want it to do other stuff.
{: .interviewee }

Another ongoing thing is making the notation richer in terms of the types of notation it supports and making it look better and clearer and more beautiful. But, that's just an ongoing thing. Every week we're making improvements to that. That's not the kind of thing where it's particularly sexy to talk about. I'm not going to make a huge product announcement saying we tweaked our notation a little bit. That's just par for the course to keep improving it.
{: .interviewee }

AG: That's awesome, man. I can't wait to see what you end up making and I'm really looking forward to the future of the product. I love using it and I love bugging you with the ways that I break it.
{: .interviewer }

AH: Yeah! Thank you thank you!
{: .interviewee }

AG: Cool, well I think that's a great breakdown of Soundslice. Is there anything else you want to say about the product?
{: .interviewer }

AH: Huh. I probably should have something to say, but I'm not savvy enough to know what to say.
{: .interviewee }

AG: All right, cool! If people want to reach out to you, you're on social media. Everything is "soundslice," right? Twitter.com/soundslice, all that.
{: .interviewer }

AH: Mm-hmm. Or just email: feedback at soundslice dot com or adrian at soundslice dot com. We read all those and respond.
{: .interviewee }

AG: Awesome. Thank you so much for your time, Adrian. I appreciate it.
{: .interviewer }

AH: Thank you thank you! See you online!
{: .interviewee }

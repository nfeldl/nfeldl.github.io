---
title: Recursive Encounters w/ AI
type: experiment
people:
- Jonah Bossewitch
- Rob Garfield
published: true
---

<div style="margin-top: 1em;">
<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/179079340&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>
</div>

While chipping away at my dissertation this summer I found myself faced with the daunting task of transcribing about a dozen hours of video. I desperately wanted to believe that, in 2014, transcription was a machine’s task, so I took a minor detour through the state of the (consumer) art in voice recognition.  One of my computers runs OSX which includes [Dictation](http://mac.appstorm.net/reviews/os-x-reviews/everything-you-need-to-know-about-dictation-in-os-x-mavericks/) (since Mavericks), the same voice recognition software that powers [Siri](http://mac.appstorm.net/reviews/os-x-reviews/everything-you-need-to-know-about-dictation-in-os-x-mavericks/). Following these [instructions](http://www.leveluplunch.com/blog/2013/12/30/convert-recorded-audio-text-using-osx-dictation-audacity-soundflower/) I used the [Soundflower](http://rogueamoeba.com/freebies/soundflower/) kernel extensions to send the audio output from [Audacity](http://audacity.sourceforge.net/) into Dictation’s input.

Dictation did such an awful job understanding my video that I actually found it easier to transcribe the videos manually rather than edit Dictation’s vomit. I found some decent software called ExpressScribe to assist in the manual transcription. [ExpressScribe](http://www.nch.com.au/scribe/) makes it easy to control the playback speed, and can be configured to play a segment, automatically pause, and then rewind the video to moments before it paused.  The pro version can be rigged up to foot petal controls, but I was able to do my transcription using the crippleware.

This summer I visited my friend Rob’s country house, affectionately dubbed Snowbound and located on the transcendental [Baptist Pond, NH](https://www.google.com/maps/place/Baptist+Pond,+Springfield,+NH+03284/@43.4513591,-72.0810211,590m/data=!3m1!1e3!4m2!3m1!1s0x89e1fa4350bf1385:0x5ea3e0c04bb6ef74). Rob was gracious enough to invite me up for a writing retreat, though we managed to fit in some canoeing, hiking, cooking and drinking. We also gave birth to one of the most creative [constructive procrastinations](http://www.ebaumsworld.com/video/watch/24101/) of my dissertation—Scuttlebutt.

After all that time playing with transcription tools we began to wonder if OSX could understand itself.  For years, OSX has been able to turn text to speech, and even ships with dozens of voices, with names like Vicky and Alex. **What would happen if we fed OSX’s text-to-speech into it’s own Dictation software?**

Originally we thought Scuttlebutt might analogize and highlight the way that we humans misunderstand, mishear and misremember, in particular, the lightning quick messages that we receive on a daily basis through personal interaction, social media and email—often deeply changing the message, generalizing it, and recontextualizing it.  Although voice recognition software begs us to “train” it, we thought we might have better results interacting with its infant state.

We needed a reliable benchmark and settled on the [first chapter](https://www.biblegateway.com/passage/?search=Genesis+1&version=KJV) of Genesis. We were curious if the voice recognition software would improve, with successive iterations of feeding it it’s own output back to itself using text-to-voice. There was one way to find out.

>In the beginning God created the heaven and the rest anything is left without things we think are funny face of the deep and just give it to Scott moved upon the face of the waters…

The results were surreal and absurd. Successive iterations degenerated, and we realized that Dictation was trying to adapt and learn, and would never reach a stable state. In fact, the system wasn’t behaving deterministically—we were seeing different interpretations when reading the exact same text. As you can see from our [lab notes](https://www.dropbox.com/sh/jv9h00ryablpkqu/AACefLTmce-nfJQvR9vKZq8ea?dl=0), zaniness ensued.

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/179079380&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/179079310&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

One of the things we found most beautiful about the initial Scuttlebutt experiments was watching the mechanisms think in real time, going back in the text to reevaluate previous approximations in the face of new material, yet rarely, if ever, arriving at a more humanly coherent whole.  With Soundflower enabled, the text-to-voice was inaudible and my laptop appeared possessed as the words flowed spectrally into the text editor. At times Scuttlebutt would pause, as if pondering, and burst forth with an entire paragraph. Other times it corrected itself, backtracking as if reconsidering it’s previous composition. What we saw was an unthinking machine actually thinking in a way so foreign to us that we could only find it charming and amusing.  The analogy to human misprision began to erode and the phantasm of an alien intelligence emerged to take its place.

<center><iframe width="420" height="315" src="//www.youtube.com/embed/5JPfp9gXxKw?rel=0" frameborder="0" allowfullscreen></iframe></center>

Did Scuttlebutt care about Genesis?  Did it care about cogency, grammar, narrative, character?  Was it looking for a climax?  Was it acting like an alien parrot trying to please us with its ability to mirror the sounds it heard and fool us into thinking it had at least an unsteady foothold in human (English) linguistic competence?  Would it have passed a Turing test altered to determine whether an alien mind was conscious?  Will the first recognizably sentient AI be running on free/open source software (a question we’ve pondered previously in: [Playing doctor](http://alchemicalmusings.org/2010/11/27/playing-doctor/))?

What next for Scuttlebutt? A tweeting preacher-bot?  Transrealist poet?  Mechanical Burroughsian cut-ups?

See more experiments by Jonah Bossewitch on his blog [Alchemical Musings](http://alchemicalmusings.org).

---
layout: post
title:  "Solo Adventures - Darocaro (Day 2)"
date:   2022-10-04 05:30:00 +0530
---


## [Darocaro Puzzles](https://darocaro.github.io/) - Day 2

To see spoilers, just hover over the <span class="spoiler">spoilered text</span>.

Previously on [DaroCaro Puzzles](/2022/09/29/darocaro-day-1.html)...

*We solved 6 puzzles and 2 metas out of 15+5. We take 4 days doing so. We rage a lil bit.*

...And now, this.

### [Highway Petrol](https://darocaro.github.io/puzzles/highwaypetrol/highwaypetrol) - Backsolved then hinted then solved

> Solved the sudoku, manually of course. It was fun. <span class="spoiler">Got to the next aha (car names from the Piston cup) as well as `MIDDLES` from there pretty quickly.</span> And then stuck! No clue where to go from there, except what the checker is telling me. This hunt will take a while, innit?

Stared at the puzzle some more. Ended up watching Cars 2 and 3 instead. Came back to the puzzle to stare after it some more. Backsolved it immediately![^5]

Then hinted it, and got it after the hint. <span class="spoiler">Holy crap. I would never have guessed A1Z26 inside a freaking sudoku, simply because how constraining A-I are. This was really cool, even though I discarded the right idea waaaaay too many times.</span> I am now sure transcribing the puzzle would have helped me here ;-;[^6]

[^5]: Remember the lesson kids. If you're ever stuck in a puzzle, just watch a 2 hour movie.[^7] It works 60% of the time, every time.

[^6]: Remember the second lesson kids. Always transcribe, even when you don't want to. Especially then.

[^7]: Yaya, I know Cars 2 is 1h46m, and Cars 3 is 1h42m. But together they're more than 2 hours. So who's the nerd now, neeeerd?

### [Helium Capacity](https://darocaro.github.io/puzzles/heliumcupacity/heliumcupacity) - Hinted then solved

> Making steady progress on this. Have the grid almost filled out. <span class="spoiler">Both the ahas (Elements and UP) came naturally to me, so progress has been good. I sure do like the "Confirm midway subparts" of certain puzzles, it makes the puzzle all the more easier, which newer solvers would appreciate. I just have to make sure I don't rely on it like a crutch or anything.</span> Still yet to finish the grid, and no clue how the extraction would work, so...
>
> ...*(Sleep Break)* Two days later, transcribed this on a spreadsheet, and tried to hack at the last 2 clues. Got one, but even after Nutrimatic, still clueless (heh) on the last one. ;-;

Took me a few days, but decided to start hinting this now. i think I'll rather finish the hunt than try to save my feelings at trying to do hintless. <span class="spoiler">And I'm quite glad I did, because the extraction I was stuck on was... bad. I wish they had done something different with the extraction, probably considering element sums or moving "up" from the right balloons, or anything. My accent (I pronounced the first word as `Aaaalumnt`) didn't do well either, which is another reason I really dislike pronunciation puzzles. Either way, between that and the word I was actually missing (Approach/Upproach)... I'm glad I hinted this one.</span>

And that brings me up to 8/16 woo. I wonder if the meta will budge now

### [Math is Math](https://darocaro.github.io/puzzles/mathismath/mathismath) - Solved

> I started working on it, but I'm usually bad at these "Reach target number" type of puzzles. So I've been lost in the "combinatorial explosion" that results from these numbers. Maybe it's time for me to make my own solver for this, just to make progress on it. Let's see.
>
> ...*(Sleep Break)* Decided to *not* do this one manually. As it is, if I'm doing things manually, I'll be bad, so might as well do it using good code. And by good code, I clearly mean stolen code. Thank you to github.com/Radcliffe for [this 4 fours code](https://gist.github.com/Radcliffe/fab1cefe6e2a3a23466539a7ecbc6edb) that I then modified. Made a bunch of spreadsheetfu mixed with Python to organise and sort through the logical process, made a ton of good deductions.... And immediately hit a contradiction ;-; I really don't want to start over on this, but I have to. Sigh. More automation it is.[^2] 

<span class="spoiler">After 2-3 failed backsolve attempts, I now only juuuust notice that each suit has an associated symbol with it ;-; And not only that, they're all in order, so you dont even have to play four 4s to get there. You can quite literally just do it normally.</span> Sigh. My lack of reading skills knows no bounds.

And only about 10 minutes later, with zero extra automation (and only about 600 hidden rows worth of data), I solved it. I was even quite close to backsolving it too <span class="spoiler">But I guess my peeviness against all of this hunt's answers had to continue. This answer doesn't even make that much sense tbh ;-;</span> Either way, one more puzzle down, so there's that. And this time, it was all on my reading comprehension.[^8]

[^2]: I am dreading the day I finish this and look at the solution doc. Either I'll be glad I didn't try it the manual way, or I'll feel silly for all of this extra work

[^8]: The thing that still bothers me but will probably go unsolved is why my algorithm-sheetfu failed. It was a strict superset of the info presented, with no assumptions towards ordering of the 4 cards, bracket operations or even basic operations [ + - × ÷ ]. So as long as we followed the deductions/assumptions from the example (which both final solution and my algo did), we would always get the same answer, or at least, not a contradiction. Hmm... I really want to look at this a lot deeper and see if I can rerun the algo and see where it failed.

### [Meta : Where's Sporky 2](https://darocaro.github.io/puzzles/wheressporky/wheressporkyre) - Hinted then Solved

> Finally opened this. Still at (6+2)/16 solves. Also know what to do. I think I'm stuck either guessing thematic answers, or going back to solve more puzzles. 

<span class="spoiler">The one/two extra letters I got after Helium Cupacity made an immediate difference as I made clear progress. Nice. Got to intermediate phrase `NOW RETRACE YOUR STEPS`, and now currently thinking of what it could mean.</span> Tried a few ideas that didn't pan out, maybe will attack it again tomorrow. 

...*(Sleep break)* Realised that this hunt had `HINT1` and `HINT2`. Used it (probably a tad too early imo). <span class="spoiler"> Realised where I needed to look. Turns out, what I thought was German was just reversed English ;-; RIP `NACHSARTSEINNOB`.</span> I even tried that as my first guess of the puzzle, immediately on unlocking as well ;-;

Well, at least it's solved.

### [Meta: Puzzled Toys Toy with Puzzles](https://darocaro.github.io/puzzles/wheressporky/toypuzzles) - Solved

This is a fun one to unlock. I always like puzzles with mechanics that callback to earlier puzzles (My earliest memory comes from the [Paradox Puzzlehunt Meta 2](https://paradoxpuzzlehunt.com/puzzles) which was fun and one of my earlier hunts ever). I worked on it for a little bit and made a lot of progress. Some of the subpuzzle answers had quite a bit of ambiguity for me to be happy with them, but such is life.

I did really like the World Wilde Web subpuzzle <span class="spoiler">if only for the fact that I juuuuust played Wingspan yesterday. It's a fun game so was nice going through Google searching for ways to find these birds on there. That said, I think the wingspan bit was underclued for someone who doesnt know the game so idk.</span>.[^9] [^10]

After about 7-9 minipuzzles, guessed around a little bit, used Nutrimatic some more. Got to the final answer quite quickly. Solved! And with that, we finished the hunt!! <span class="spoiler">Quite cute and thematic answer. I liked</span>

I didnt like the Familia Tunes subpuzzle though. <span class="spoiler">I listened to it a bunch of times and still did not hear "MUSHU" (only learned that word after reading (part of the) solution). A part of it might be the background karaoke thingy, but it just does not sound unambiguous enough to me, even if I listen to it after knowing the word.</span>

[^9]: Even had to convince literally all of my board gaming companions to let me play this game.

[^10]: Fun fact. Literally all three of these birds are garbage, and I think I discarded 2 out of those 3 specifically in my one game yesterday.

### [Stargazing](https://darocaro.github.io/puzzles/stargazing/stargazing) - Solved

> Started the puzzle. Decided to go off to shinier puzzles midway. Will come back to this one, eventually.
>
> ...*(Sleep Break)* Took me 2 days and one extremely boring voice call to finally start working my way through this one. It's a fair bit of busywork, so perfect for when I was feeling a bit brain-dead. I still don't know what I need to do after though, so a bit stuck here. Let's see.

<span class="spoiler">Did the Meta 4 sub-puzzle for this puzzle. Cracked that extraction eventually, mostly because of predicted letter. Came back to this puzzle. Cracked the extraction immediately. The entire description bits for everything was kinda cute, in retrospect.</span> Felt a bit silly for not trying it earlier. Well, at least I did solve this puzzle eventually. Even though extraction got me stuck for the 3-4 days. 

## (Not so) Arbitrary Break

We solved the hunt! :D Arguably a lot lot later than we should have, and unarguably with a lot more hints than we should, but such is life. Sometimes solvers are silly and forget important things, doubly so when solo. But... With that, we solved our second hunt solo :D

And now, time to 100%, which will be a lot more work, and probably a few more hints burned. Let's see. Meta 4 will be a huge boon in helping me figure out some of the weirder mechanics, so I have some hope.

Either way, it's getting kinda late (And I did stay up solving puzzles all night because I was close), so I might try to finish these puzzles later on tomorrow at a leisurely pace now. I sure as heck am not blazing through 5 puzzles in a couple hours, no matter how stuck on extraction. And I'm definitely 100%-ing the hunt before posting it, so... 

Either way, puzzles for tomorrow-me to tackle. Let's see.

### [A heroine's Journey](https://darocaro.github.io/puzzles/heroinesjourney/heroinesjourney) - Hinted then solved

> Started the puzzle, finished the "maze", stuck on the next bit. 
>
> P.S. Have I told you how much I hate not being able to zoom out of images? It just messes with me, having images stay the same size and everything else shrink/grow.

Transcribed it very very painstakingly after a gigantic risk-reward calculation of "Is this effort worth it". <span class="spoiler">No it wasn't.</span> But after 30 minutes and one panic attack[^3], I finally had everything down on my sheet. I got the aha right about them <span class="spoiler">I mean, the fact that it was a wordsearch was fairly obvious, I just had to see an example to be convinced of it and attempt to do it by sheet. But either way, once it was in the sheet, it was smoother (Conditional formatting yay), and I got the rest of the words with much lesser pain than otherwise. Definitely better than scraping through the image manually.</span>[^4]

Made a bunch of progress <span class="spoiler">Aka getting to `FOLLOW YOUR HEART`</span>, followed by getting stuck. Hmmm.

...*(Multiple Sleep Breaks)* Eventurally had to hint this one. It worked instantly. <span class="spoiler">I "think" I could have gotten the Boggle/hearts aha, but also I'm not surprised I didnt. Hinting was a fair call, though I'm not particularly happy with how much noise was in this puzzle. It could have been cleaned a fair bit. Also I feel like the Meta 4 subpuzzle for this one was also not the cleanest, as I had the wisp saying "A" because of another word. I feel like you must at least have words forming both on horizontal and vertical, even if your solvers miss something obvious like "SCOTLAND"</span>

Either way, decent puzzle. One more down.

[^3]: Completely unrelated, but surprisingly effective for busywork. My mind's already distracted so cannot be distracted any further. 0/10 would not recommend.

[^4]: P.S. Have I mentioned how much I hated it being an image (which also failed OCR somehow) without any ways to copy?


### [Recette du Success](https://darocaro.github.io/puzzles/recettedusucces/recettedusucces) - Hinted x2 then solved

> I looked at this puzzle exactly once, tried one idea <span class="spoiler">(Caesar shifting the words)</span> and immediately gave up and went to other puzzles when that didn't work. Not really doing great at this persistence thing, am I?

Hinted it after forever. Got the <span class="spoiler">They're all french with transdeletion</span> aha from there. Which, I think I would not have been able to figure out all on my own. Made progress. Decided to be lazy and not do things instead of hinting. The hint told me to do said thing anyway. ;-; Got the answer.

Well, simple and cute. I probably should have been more strategic with this, especially with my hints.

### [When one door closes](https://darocaro.github.io/puzzles/whenonedoorcloses/whenonedoorcloses) - Hinted then solved

> After days of ignoring this one... Transcribed and started progress. I "think" (think being keyword) I know how to go about this. I just don't see a direct way to. Maybe I'm missing something hm.

Hinted it after I was not getting an unambiguous solve path. <span class="spoiler"> I knew SF was first but using time=timezones is something I wouldnt have thought of. So that's a good hint use. And the hint also ended up telling me the real meaning of "Shake the terror for a price", which I thought was not a very good clue. So that's also super helpful.</span>

Smooth sailing from here (and I had most of the pieces I needed, just needed the hint to push me a lil bit further), and solved it. Didn't figure out the Meta 4 puzzle still, so hinting that as well. <span class="spoiler">One hint later, I'm not happy with the levels of ambiguity and TETBCN this one had. Oof</span>

Well, that's one more down, two to go! Puzzles are so much easier when you have hints to skip your mistakes!

### [Transmission Mission](https://darocaro.github.io/puzzles/transmissionmission/transmissionmission) - Hinted then solved

> Made steady progress through the day, almost got the entire crossword grid and.... then stuck. <span class="spoiler">I'm slowly making my way trying to identify chemical hormones by their symbols, but it's time consuming. And I'm slowly trying to use photoshop to adjust the pipes to match things, and it's.... not working.</span> Moments like these, I truly hate this website for having this weird thing where you can zoom in or out, but the images remain the same size.

Made a lot of progress on this. <span class="spoiler">Decided to finally identify all chemical hormones, and got the first letters aha (after I got all the chemicals, obviously), then got my Photoshop loaded, then got all the pipes lined up on there.</span>[^11] [^12] Only after doing all that hardwork did I notice both the <span class="spoiler">answer confirmation checker (;-;) and literally all of the flavourtext of the puzzle, in that order. Sigh</span>

Well at least I got a bunch of progress, even if I don't know what to do with the puzzle afterwards. Surely I must be getting a lot closer now.

[^11]: Technically not Photoshop but www.photopea.com the best online Photoshop tool I know #notsponsored

[^12]: Lining the pipes was (unlike my original idea) quite easy actually once you learn the shortcuts for Free Transform on Photoshop (Ctrl Alt T btw. You're welcome).

... *(Sleep break)* Hinted this finally. <span class="spoiler">I was being silly. I should have expected multiple pipes intersecting (and I actually did, I was just too lazy to actually implement it). Once I got the hint saying "You solved the meta 4 subpuzzle no" I immediately got the formula-fu set up to finish this ;-;</span> Why am I like this ;-; A hint wasted.

Overall, pretty cool puzzle. Lots of little things going on there, but it comes together quite well. I liked!

### [Charming but Cryptic](https://darocaro.github.io/puzzles/charmingbutcryptic/charmingbutcryptic) - Hinted x ??? then solved

> Oh yay another cryptic. I guess that puts an end to any plans I had of speeding through this hunt eh. Either way I decided to slowly trudge my way through this, and it's actually going okay so far. Still don't know what to do once I eventually fill out the grid though.[^1]
>
> I'm starting to see why crossword folks usually prefer checked letters so much. I am making progress, but it's so slow ;-;

[^1]: Remember that time when you and a teammate are both on a spreadsheet and they're hovering over an important cell and you get ultra frustrated because you need them to move the cursor? Well, fun fact, you do not need teammates for that authentic experience! ;-;

I looked at this puzzle again some after doing the hunt, and I think I'll be stuck in here for quite sometimes. Especially now that I know there are indirect anagrams in the mix as well ;-;[^13] Well at least the checker will be useful throughout to confirm one clue at a time, eh. I have "some" ideas about extraction, but that'll come after I solve most, maybe even all of my clues. There's no rush anymore.

[^13]: Crossword vets, I now totally get your disdain/hate for indirect anagramming.

Not happy with some of the clues here. And I think I always prefer my ! on my &Lit clues.[^14] Otherwise the clues were mostly nice and tractable. Either way, I am making progress steadily (now that I lied about sleeping and instead spent time solving) with the powers of [Onelook](https://www.onelook.com/), [Nutrimatic](https://nutrimatic.org/), [Cryptlight](https://cjquines.com/cryptlight/) and Crossword-Solvers combined. Between that and the checker that confirms individual clues, I am actually having a good time making progress on this puzzle. 26/39 solved now. 

Another two hours later, and I had 32/39 solved. Not bad. Then decided to hint away the remaining 7 since I was not getting those yet, and got them all. Now... time for the rest of the puzzle.

[^14]: I think I've become a cryptics snob. Which is saying something considering how not experienced I am with them. My snob notes for this puzzle - <span class="spoiler">FAMILY is a TETBCN. HARRY uses HAIRY in def, which is already in puzzle.</span> 

Alright last puzzle remaining. It's only fitting this is the one puzzle I do last. 

Hinted. <span class="spoiler">Got to the `NUMSANDPOINTERS` from there. I thought that zigzag was not very clear, neither in hint nor in where the location was placed, so not really happy with that ambiguity.</span> And now confused.

Hinted a bunch of times <span class="spoiler">until i got the path aha followed by "The numbers lie on the path" (Which was very cool ngl). The rest (Disambiguating Down/Across and then putting it into the blanks) was a bit faster. Until I got to the riddle, thought it was a cryptic clue, googled it.... And got the answer immediately spoiled for me via Google.</span> Well that was an unmitigated disaster ;-;

Overall, pretty cool puzzle. A few rough edges, but definitely some fun construction overall. And I did not expect to have more troubles with the extraction than the cryptics, but I think that's a bit standard at this point once I lose patience. Sigh. I guess I know where I need to work on myself.

## Overall Thoughts

I think this was a cute puzzlehunt. I liked DP a lil bit more[^15], but still this was a good 2nd hunt for me to try.

[^15]: I think I just really like clean puzzles

I really really like "Keep Going" messages to confirm clues/midway points as a way to make puzzles easier for the newcomers without sacrificing overall puzzle difficulty. It helped me quite a few times.

I also realised that I am much much lazier as a solver than I can afford to be, at least when I'm solo. I think there were 3-5 instances of "I think it's X but I don't feel like doing it so let me hint" only for the hint to just tell me X anyway. ;-;

Also, maybe hints are not the best idea in the world to spam away. Who would have thought amirite?

Either way, this was nice. I'm content, kinda. Slower than I'd like, but such is life. Next up, either [Hunt20](https://hunt20.com/) finally, or just wait for [ECPH](https://ecph.site/). Let's see.

## srrnfeeeec



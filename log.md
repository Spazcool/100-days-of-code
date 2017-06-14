# 100 Days Of Code - Log
### Day 1: March 25, Saturday

**Today's Progress**: I've spent the day in the <a href="http://www.coderbunker.com/">bunker</a> bashing away on the Tic Tac Toe game for freeCodeCamp. The base styling is done, it's at a minimum functional; a bit more difficult than usual due to my choosing to avoid bootstrap for this project. As for the brains of the site, the JS, I've got the user inputs down and the conditions required for a win OR draw. In between bouts of confusion I also added the first blog post related to the fCC algorithms.

**Thoughts**: Bootstrap, for a project like this would have been overkill; it's fine without it. As for the JS, the focus of today's work, I really need to sharpen up my understanding of data types and structures as well as algorithms. I'm hardcoding some conditionals where I could/should be using a clean algorithm with an equally clean object.

**Link(s) to work**
1. [tic tac toe](http://codepen.io/SpazCool/full/EWpaJG/)
2. [blog post](http://www.spazcool.com/blog1/)

### Day 2: March 26, Sunday

**Today's Progress**: I've spent the last couple of hours trying to style my nearly complete Pomodoro Timer. So far I've got the digits atop the screen atop the time setting slider. I've been hitting a wall here with relatively sizing the slider's div, as the stock JS hard codes its size in px. Also, I gave the user more flexibility in setting the time and uncovered a bit of a bug; if no time is set, the read out bugs out switching from 0 to -1. This can be escaped if the user pauses the timer and resets the timer.  

**Thoughts**: Bootstrap! While I definietly made some progress tonight, that set size for the slider remains a thorn in my side. I don't think it's a lack of understanding on my part just, the need for some juggling of ideas.

**Link(s) to work**
1. [pomodoro timer](http://codepen.io/SpazCool/full/mRKMQa/)


### Day 3: March 27, Monday

**Today's Progress**: Spent about 2 hours on just trying to get the the slider to resize, even sent an email to the developer asking if it can be sized with relative units. After banging my against that, I moved on to ripping out the bootstrap and relative units from my code; everything is hard-coded now and nearly in place...for this screen.

**Thoughts**: It's fucking annoying. That one piece not working has thrown a wrench into the whole of the works. I don't know if it's possible but, perhaps I can nest the divs using fixed values into a relative container; it sounds like a good idea but, I foresee problems.

**Link(s) to work**
1. [pomodoro timer](http://codepen.io/SpazCool/full/mRKMQa/)

### Day 4: March 28, Tuesday

**Today's Progress**: Ripped out the previous slider due to an inability on its part to resize responsively and an inability on my part to get it resized responsively. Moved the buttons a bit. Changed some of the colors. Added in a new simpler slider.

**Thoughts**: After yet another hour of fiddling with the previous pretty round slider, I just opted to tear it out and start over with the "stock" jQuery slider. It won't look quite as super awesome but, I need to cut my losses at this point; it's been ~4 hours tweaking pixels to get something that looked kinda ugly on any screen other than the one I'm working on. Simplify and get something that works out before the holiday is through.

**Link(s) to work**
1. [pomodoro timer](http://codepen.io/SpazCool/full/mRKMQa/)

### Day 5: March 29, Wednesday

**Today's Progress**: Finished! Styling, links, the new slider, all of it is done--barring someone tells finds a bug. Even got some of the responsive design back in there but, not completely.

**Thoughts**: Very much ready to be done with this one. I've spent at least 10 hours on it over the last three days and that was mostly fiddling CSS elements that would fall to pieces if the screen or browser were at all different. I'm happy with the look and function of this finished product and may even start using it regurlarly after posting it to my site.

**Link(s) to work**
1. [pomodoro timer](http://codepen.io/SpazCool/full/mRKMQa/)
2. [pomodoro timer, on my site](http://www.spazcool.com/pomo/)

### Day 6: March 30, Thursday

**Today's Progress**: Tweaked some logos using Pinta. Edited a bit of my portfolio site, adding said logos and smoothing out a couple of the bugs in my responsive design. 

**Thoughts**: Slower work today. Should have been more productive and worked on some algorithm challenges but design is important too.

**Link(s) to work**
1. [Portfolio site](http://www.spazcool.com/)

### Day 7: March 31, Friday

**Today's Progress**: Slight adjustements made to the Exact Change Algorithm Challenge.

**Thoughts**: The baby was less than happy today, I didn't have a single whole-hour to work so, while I was online "working" for three hours or more, little progress was made. I should have called it a lost day and just enjoyed some TV or something. I'll be at the Bunker tomorrow so, progress will be made. As for the challenge itself, I was able to just find where and what one of the bugs were; float vs integer modulus division. I got it squared away in one spot but, I suspect it'll be a problem elsewhere. Beaten today.

**Link(s) to work**
1. [Exact Change CodePen](https://codepen.io/SpazCool/pen/xqQLwO)


### Day 8: April 1, Saturday

**Today's Progress**: Basically finished the fCC tic-tac-toe challenge. 

**Thoughts**: It is a rudimentary AI, just seeking out what cells are available and pushing its character in there but, it is running as a game. Now, I'm on the bug hunt, tweaking the bits that aren't running as they should be and after that, perhaps improving upon the AI to make it seek out the win.

**Link(s) to work**
1. [TicTacToe CodePen](https://codepen.io/SpazCool/full/EWpaJG/)


### Day 9: April 2, Sunday

**Today's Progress**: Killed the last couple of bugs in the fCC tic-tac-toe challenge. It is fully operational! Tweaked the styling, cleaning the UI up. 

**Thoughts**: I still haven't touched the AI. The game is functional but, the computer always loses since it is only choosing cells at random. Part of me wants to make it smarter, more gamey but, another part of me sees the finish line for the fCC Front End cert. Do I really want to spend more time on this than I need or would the time spent on this be a benefit for me?

**Link(s) to work**
1. [TicTacToe CodePen](https://codepen.io/SpazCool/full/EWpaJG/)

### Day 10: April 3, Monday

**Today's Progress**: Beefed up the AI a bit, giving it prioritzed cells to choose from; center first, then the corners, then the rest. 

**Thoughts**: Definitely helps to work on the AI, all of the juggling of if/else statements and comapring this and that make for good practice. 

**Link(s) to work**
1. [TicTacToe CodePen](https://codepen.io/SpazCool/full/EWpaJG/)

### Day 11: April 4, Tuesday

**Today's Progress**: Continued with the AI, getting rid of the bugs created in yesterday's swashbuckling and cleaning up and shortening a lot of my code; some of this was bikeshedding but, there was some inefficiencies with my code as well. Also, tweaked my pomodoro timer by having it append the title of the "<head>" 

**Thoughts**: I have stubbornly chosen to puzzle out this game for myself, I'm certain that there are algorithmic solutions to the game that could influence and improve my AI but, I want the practice of thinking through this mess. With that said, the next bit I have gotten stuck on; having the AI seek out a partial winning sequence and completing it for its own benefit or to block the player from a win. Fingers crossed that I can finish this by the weekend.

**Link(s) to work**
1. [TicTacToe CodePen](https://codepen.io/SpazCool/full/EWpaJG/)
2. [Pomodoro](http://www.spazcool.com/pomo/)

### Day 12: April 5, Wednesday

**Today's Progress**: Work and the baby interferred quite a bit today, I only managed to watch a couple of JS vids on youtube and had the sudden terrifying realization that my Calculator project had a bug in it. I found it and tried to fix it for a bit but, again, not much was done.

**Thoughts**: Those videos really showed how little I know of JS at the moment. My calculator's JS has 250+ lines of code. Some of the examples I came across got it done in under 50. Methods like .eval and .inludes saved those creators so much time and hassle. It's a little bit sickening to see the ease with which such an app could be made when using the right tools. 

**Link(s) to work**
1. [Calculator](http://www.spazcool.com/calc/)

### Day 13: April 6, Thursday

**Today's Progress**: Junked my previous attempt with the calculator. Copied and pasted and juggled a few other solutions and in under an hour, I already got something running at nearly 100%. 

**Thoughts**: It almost feels like cheating to be using these methods. I don't know if it's a pleasant feeling or not. Suppossing that the last little bug, having numbers with more than one ".", can be dealt with quickly then I'm hoping to add a little styling tomorrow. 

**Link(s) to work**
1. [Calculator](https://codepen.io/SpazCool/pen/rjYYrp?editors=0010)


### Day 14: April 7, Friday

**Today's Progress**: A bit of easy JS, revamping my solution to fCC's profile lookup algorithm challenge, along with some light styling for the accompanying blog post entry.

**Thoughts**: It was nice to go back and see this problem with new insights. I cut out at least ten lines of code and used a couple of methods that were beyond me at the time. Still, it is an easy challenge but, it felt good nonetheless.

**Link(s) to work**
1. [Profile Lookup Challenge Blog Post](http://www.spazcool.com/blog2/)

### Day 15: April 8, Saturday

**Today's Progress**: A boatload of CSS today, a bit of JS as well but not so much to really get into it. Completely redesigned the look and interaction of the calculator for the better.

**Thoughts**: It looks good and it works well. I've only got a couple more smallish bugs to deal with and then it is golden; one related to the over-sized output to the "screen" and the other having to do with clearing the screen if a new operation is being performed following the termination of a previous one. It's all doable.

**Link(s) to work**
1. [Calculator](https://codepen.io/SpazCool/pen/rjYYrp?editors=0010)

### Day 16: April 9, Sunday

**Today's Progress**: Finito! Added a bit of JS to get the final touches in and bugs out and now it is a finished product. Updated it on both codepen and on github. A bit of CSS as well but, really just tweaks. Also, posted my Tic Tac Toe game on github; it's not where I want the finished product to be but, it's functional and offers some challenge.

**Thoughts**: Where the previous version took many dozens of hours, of little progress and great frustrations, this version took me, at most, 10 hours. Yay for using pre-existing methods and libraries! This allowed me greater freedom and ease when it came to the CSS; I wasn't too mentally taxed/exhausted by the JS to not bother with it this time 'round.  

**Link(s) to work**
1. [Calculator on CodePen](https://codepen.io/SpazCool/full/rjYYrp/)
2. [Calculator on my site](http://www.spazcool.com/calc/)
3. [Old and Broken Calculator on CodePen](https://codepen.io/SpazCool/full/LWwYoe/)

### Day 17: April 10, Monday

**Today's Progress**: Kinda sorta started the final fCC front end project, the Simon game. I write "kinda" because I haven't touched the JS at all and even HTML and CSS is a mess. At the moment, I've managed to get the screen to be filled with a hexagonal grid, though with some odd padding/margin bugs that need sorting.

**Thoughts**: My idea for my simon game design is to have a hexagonal grid where only a select fet of said hexagons glow in a rough game of simon layout, essentially using the hexagons as really big pixels. I also have other ideas related to animation of these but, first I need to get the static grid working and set to at least a computer screen's dimensions. I know that this may be needlessly complicating what is to be an already complex project but, I tried and failed using hexagons some time ago--with the wikipedia viewer--I want my hexagons even if they don't me. 

**Link(s) to work**
1. [HEX Grid on CodePen](https://codepen.io/SpazCool/pen/qreXeL?editors=1100)

### Day 18: April 11, Tuesday

**Today's Progress**: Finished a rough hexagonal grid in CSS/HTML, it will need some TLC down the road for responsiveness but, it's up and running. Also got some simple animations running with Jquery, fading in an out based on id's.

**Thoughts**: The grid took a bit of time to make but, now I get to play and see what kind of animations I can come up with. Hopeful.

**Link(s) to work**
1. [HEX Grid on CodePen](https://codepen.io/SpazCool/full/qreXeL/)

### Day 19: April 12, Wednesday

**Today's Progress**: I had about an hour total to continue to lay the groundwork for what may be a really cool visual style to my Simon game project. Basically, I played around with how I might access the hexagon id's in a systematic way with jquery to produce a nifty animation.

**Thoughts**: My usual lunch break coding session was interupted as was my evening so, not much was achieved today. I will continue to pursue this visual asthetic for now.

**Link(s) to work**
1. [HEX Grid on CodePen](https://codepen.io/SpazCool/full/qreXeL/)

### Day 20: April 13, Thursday

**Today's Progress**: A much improved layout now, things are even and very roughly colored. Still mostly CSS but, JS will soon come.

**Thoughts**: It's looking much better, more responsive if not great on a phone it still works. Liking it, gotta think about how I'm gonna animate it.

**Link(s) to work**
1. [HEX Grid on CodePen](https://codepen.io/SpazCool/full/qreXeL/)

### Day 21: April 14, Friday

**Today's Progress**: Little real progress was made, despite spending 2+ hours on it today. Mostly just playing around with JQuery methods for animation.

**Thoughts**: I've been working but, without a real goal in mind. With the trip less than a week away, I don't really want to start the heavy lifting on this project just yet. More play to follow.

**Link(s) to work**
1. [HEX Grid on CodePen](https://codepen.io/SpazCool/full/qreXeL/)

### Day 22: April 15, Saturday

**Today's Progress**: Little real progress was made, despite spending 2+ hours on it today. Mostly just playing around with JQuery methods for animation. Same as yesterday, I know but, I'm just exploring what and how.

**Thoughts**: I've been working but, without a real goal in mind. With the trip less than a week away, I don't really want to start the heavy lifting on this project just yet. More play to follow.

**Link(s) to work**
1. [HEX Grid on CodePen](https://codepen.io/SpazCool/full/qreXeL/)

### Day 23: April 16, Sunday

**Today's Progress**: Tightened up some of the creative creep that has come about. Explored the phaser JS library as a way to make HTML games but, decided against it as, I've already invested a fair bit of time on the layout as it stands.

**Thoughts**: I'm still just treading water here, getting the layout and feel working before the heavy lifting with the game logic itself. I'm hoping to hit that in a week, after the trip.

**Link(s) to work**
1. [HEX Grid on CodePen](https://codepen.io/SpazCool/full/qreXeL/)

### Day 24: April 17, Monday

**Today's Progress**: Started some of the JS logic today, thanks to an unscheduled long lunch. Got it randomly selecting one of the buttons, randomly selecting how many times to make that button glow, saving that event and also saving the similar event when the user clicks on a button and lastly comparing those two saved events in length and content.  

**Thoughts**: I'm a bit surprised at how much code is needed to just get the bare game up and running. This is not a game yet and I've nearly 100 lines jotted down, granted a lot of those are going toward graphical flourishes. It felt good to move away from the pixel placement, though.

**Link(s) to work**
1. [fCC Simon on CodePen](https://codepen.io/SpazCool/full/qreXeL/)

### Day 25: April 18, Tuesday

**Today's Progress**: No constructive work done. A super busy work schedule and the need to get ready for a flight back home killed my free time today. Watched some videos on fCC. 

**Thoughts**: Annoying to have had to put my project aside for the day, especially when I had just started it in earnest but, such is life; it may well be the case for the next week abroad.

**Link(s) to work**
1. [fCC JS video](https://www.freecodecamp.com/videos/javascript-lingo-value-types)


**!!!! STARTING OVER !!!!**


### Day 01: April 26, Wednesday

**Today's Progress**: Worked on a hackerRank sorting problem where one has to return the number of elements that the most frequent number has out of a given array; [2,5,2,4,6] should return 2 because there are two elements of the array that are equal to 2 and that is the highest incident.

**Thoughts**: Well, a week back home in the States organizing and celebrating my brothers wedding did me no favors toward this challenge. I didn't even have time to watch videos, it was a good time with those I love but, it kind of screwed me over with regards to this challenge. So, starting over.

**Link(s) to work**
1. [hR sorting problem](https://codepen.io/SpazCool/pen/zwoJGB?editors=0011)

### Day 02: April 27, Thursday

**Today's Progress**: Worked on a couple more hackerRank algorithm problems. The first being a hole counter where the input was a random number and the output had to be the number of holes in all of the digits (i.e. "6" has one hole, "7" has zero holes, "8" has two, etc). The second problem asked for a zipper merge of two strings where str1 = "abc" and str2= "efg" the output should be "aebfcg"; and it needs to handle strings of differing lengths from each other. I also spent my lunchbreak going through codecademy's Sass course.

**Thoughts**: None of the above was terribly difficult, sure there were a couple of snags here and there but, I made short work of it. I do wish I hadn't fallen asleep so early--thank you jetlag--and had been able to start back up on my Simon game.

**Link(s) to work**
1. [hR holeCounter problem](https://codepen.io/SpazCool/pen/KmaWYV)
2. [hR mergeStr problem](https://codepen.io/SpazCool/pen/YVNVRK)
3. [CC Sass](https://www.codecademy.com/learn/learn-sass)

### Day 03: April 28, Frisday

**Today's Progress**: Spent a couple of hours getting lost reaquainting myself with my Simon game before deciding to fork it and then scrub any unecesary flourish from the fork; all to make it easier to read/work with. 

**Thoughts**: Having an issue with recursion and an array method applying itself to both the copy and the original. Kind of annoying.

**Link(s) to work**
1. [fCC Simon Game](https://codepen.io/SpazCool/pen/XRMmMo)

### Day 04: April 29, Saturday

**Today's Progress**: Six mostly productive hours down in the bunker allowed me to go from a series of buttons that flash after the user hits start to a full, if ugly, game of Simon. Functionally, it is finished! All that remains is my porting the game into the GUI I've already set up and then moving all of that over a real editor to tweak before posting it on my portfolio.

**Thoughts**: Fucking close. Baby, schedule and life permitting, I'll have this done by next weekend. Then, the freeCodeCamp frontend certification is mine.

**Link(s) to work**
1. [fCC Simon Game](https://codepen.io/SpazCool/pen/XRMmMo)

### Day 05: April 30, Sunday

**Today's Progress**: No where near as productive today. Just some Sass tuts on codecademy.

**Thoughts**: Super busy today, kept me from the computer till late at night and I was falling asleep while on it. #adulting

**Link(s) to work**
1. [Sass tut](https://www.codecademy.com/courses/learn-sass/lessons/functions-and-operations/exercises/arithmetic-and-color?action=lesson_resume)

### Day 06: May 01, Monday

**Today's Progress**: Got a solid hour and a half on hackerRank tonight. Simple algorithm challenges, like finding the most frequent element in an array, zippering together two strings and counting the "holes" in a grouping of numbers. All put together and I passed the TechHire coding challenge. Fuck yeah.

**Thoughts**: I've been playing around with hackerRank for a littel while. I want to go on the record here as being firmly against their witholding of both the inputs and outputs of theri tests. It's fucking annoying and is comepletely divorced from reality.

**Link(s) to work**
1. [Sorry no real links on that one.](https://techhire.careers/candidates/dan-wright/signup/profile)

### Day 07: May 02, Tuesday

**Today's Progress**: Spent about 90 minutes plugging in and making the code play nice from my two versions of fCC's final front-end project, the Simon game. One version looks good, the other works. Now to play doctor. Not functioning yet.

**Thoughts**: I've been playing around with hackerRank for a littel while. I want to go on the record here as being firmly against their witholding of both the inputs and outputs of theri tests. It's fucking annoying and is comepletely divorced from reality.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 08: May 03, Wednesday

**Today's Progress**: Got a solid 2 hours in, Simon is functioning but, some of the pretty is missing. Specifically, I plugged in the opening animation, played with the context/menu buttons and cut out some busted code.

**Thoughts**: I was definitely tired, less in a mood to be creative and more in one to break things or, at the very least, plug in and forget. Still, I put in the time.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 09: May 04, Thursday

**Today's Progress**: Very little "real" work on code got done. I tweaked a bit of the animation for my simon game. However, I did spend a couple of hours prepping for and another hour taking part in a mock interview with TechHire.

**Thoughts**: So much work to do. It's good to get feedback finally, critiques regarding my style or communication in code are much needed. Still stings a bit, hearing the negatives after a year and a half of beating myself into some kind of developer wannabe. I want it, though. The changes will be made and I'll push forward. This could be mine if I do it right.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 10: May 05, Friday

**Today's Progress**: Started the spring-cleaning on my repos here. Adding READMEs, good comments, cleaner code and removing the dead or unused bits. 

**Thoughts**: This housekeeping stuff is less fun but, I need to make it presentable for hire.

**Link(s) to work**
1. [My git profile](https://github.com/Spazcool)


### Day 11: May 06, Saturday

**Today's Progress**: Still in clean-up mode. A lot of progress has been made, in fact I'm nearing the end of this BS and will soon get to fiddle with my portfolio page more aggressively. 

**Thoughts**: Getting there. 

**Link(s) to work**
1. [My git profile](https://github.com/Spazcool) - 32 commits today

### Day 12: May 07, Sunday

**Today's Progress**: Finished cleaning my repos! Everything has a readme, a lot of the dead code and innane comments are gone and it looks a lot cleaner. Also, started tweaking my portfolio page again but, I've been running into issues with the GIT servers taking hours to update my changed files. 

**Thoughts**: It is still not perfect but, it does feel a bit more presentable.

**Link(s) to work**
1. [My git profile](https://github.com/Spazcool) - 32 commits again!

### Day 13: May 08, Monday

**Today's Progress**: A bit of everything today. A bit more of a Sass tutorial during lunch, tweaked my portfolio a bit after work and started back up playing with the animations for my Simon game before bed. Productive.   

**Thoughts**: Back to coding.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)
2. [portfolio page](http://www.spazcool.com/)
3. [Sass tuts](https://www.codecademy.com/courses/learn-sass/lessons/sustainable-scss/exercises/sass-structure?action=lesson_resume)

### Day 14: May 09, Tuesday

**Today's Progress**: During lunch at work, whiled my way through the start of codecademy's React course. It seems an interesting library though, I'm having trouble thinking of any practical uses for something I'd make by myself; still, it might be fun to play with in the future. This evening I muddled around with my Simon game. The core game is finished but, there's alot of the GUI that is lacking. Specifically tonight, I fixed a bug with the buttonFlourish and then spent the rest of my hour in the HTML and CSS playing around with different headers.   

**Thoughts**: Not sure, I'm tired and I've lost some of the momentum for this project. I just want it done.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)
2. [React tuts](https://www.codecademy.com/courses/react-101/lessons/react-jsx-advanced/exercises/jsx-variable-attributes?action=lesson_resume)

### Day 15: May 10, Wednesday

**Today's Progress**: Added a header div to Simon and styled it slightly.

**Thoughts**: Oh what a pain in the ass. I couldn't nest the header inside of the container for the game, otherwise it would disturb all of the hex pieces, despite its position being absolute. And when set outside of the container I couldn't get the height of the thing to match the height of the container. An hour wasted languishing in HTML and CSS only to find a jQuery solution that took a single line of code and two minutes of my time. Fuck!

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 16: May 11, Thursday

**Today's Progress**: Far more productive tonight, adding a pseudo-border to the whole of the page, a sliding menu screen and a title.

**Thoughts**: Plenty got done for an hour's work, had I not gone to the gym and had not had to cook and clean and all of the other junk after work, maybe I could have spent more than an hour. However, other stuff is good too. As for this game, it needs a lot of styling to look polished.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)
2. [React tuts](https://www.codecademy.com/courses/react-101/lessons/react-jsx-advanced/exercises/jsx-variable-attributes?action=lesson_resume)

### Day 17: May 12, Friday

**Today's Progress**: Due to it both being Friday and a fussy baby, no work was done at home. I did squeeze in a little over an hour--nonconsecutive--of React tutorials at work, though.

**Thoughts**: meh

**Link(s) to work**
1. [React tuts](https://www.codecademy.com/courses/react-101/lessons/react-jsx-advanced/exercises/jsx-variable-attributes?action=lesson_resume)

### Day 18: May 13, Saturday

**Today's Progress**: Got a solid hour of GUI work in. Tweaked some of the CSS values for the header, footer and popup windows. Also added some of the logic required for all of those things to happen.

**Thoughts**: Kinda wish I had had time to head to the bunker today, I think it might be finished had I done so. 

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 19: May 14, Sunday

**Today's Progress**: Tweaking the CSS some more today, colors, fonts, borders, that sort of stuff.

**Thoughts**: Limping to the end. 

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)


### Day 20: May 15, Monday

**Today's Progress**: Added some small tweaks to the CSS and another informational div to the HTML. Most of my time was spent cleaning up my JS, creating new functions to handle similar tasks, cutting out the fat.

**Thoughts**: Still got a couple of bugs before I'm ready to submit it; the noise not playing, the counter not pausing on casual and the full hexagon not being clickable.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 21: May 16, Tuesday

**Today's Progress**: Mostly a bug hunt today. Fixed the audio issue, with the help of a forum answer. Found a new one though, where the game starts back up after pausing and adds a couple rounds to the counter. That needs to be sorted out.

**Thoughts**: Just putting in the time now. Nearly there.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 22: May 17, Wednesday

**Today's Progress**: Spreading that pesticide. Got rid of the biggest nagging bugs and cleaned out 30 lines of BS code. Started to add a bit more polish but, the baby woke up. 

**Thoughts**: Progress made.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 23: May 18, Thursday

**Today's Progress**: added a hint div the menu manner

**Thoughts**: Ugh, got stuck playing around with importing styles from jQ. Made far less progress tonight than I otherwise might have. Fuck.

**Link(s) to work**
1. [Simon on git](https://github.com/Spazcool/simonGame)

### Day 24: May 19, Friday

**Today's Progress**: Ran through a couple of GIT tutorials as well as modified Atom styling.

**Thoughts**: its friday, went to the gym, played with my infant son amd drank some wine. No real wprk is happeming tonight.

**Links to work**:
1. []()

### Day 25: May 20, Saturday

**Today's Progress**: Finished simon! Started the revamp of my emailer/behavior tracker, mostly wireframing right now.

**Thoughts**: Wam bam, thank you ma'am.Got my freecodecamp front end certificate. Now on to a couple personal projects and the back end.

**Links to work**:
1. [Simon](http://www.spazcool.com/simon/)
2. [Tracker](https://github.com/Spazcool/tracker)

### Day 26: May 21, Sunday

**Today's Progress**: Still just mucking about with the basic design of the tracker webapp. 

**Thoughts**: Super tired today with a cranky baby to contend with, got my "time" in but, wasn't able to really focus on the work...even while working.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)


### Day 27: May 22, Monday

**Today's Progress**: Still just mucking about with the basic design of the tracker webapp. Nearly finished with the rough layout; it'll be this week when I can hit the JS hard. Also, continued watching and following along with some Git basics tuts.

**Thoughts**: Fairly productive today even with a tight schedule.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)
2. [one of the Git tuts] (https://www.youtube.com/watch?v=WxMFZncm12s&list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-&index=4)

### Day 28: May 23, Tuesday

**Today's Progress**: Started with the JS in earnest today, added a couple of date related functions before moving on to starting a JSON for schedule

**Thoughts**: I should create an input field that adds to a JSON, permanantly.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)


### Day 29: May 24, Wednesday

**Today's Progress**: Not a lot. Banged out a bunch on some git tutorials at work but, ran out of time once I got home. Played around with importing and accessing a JSON file from another JS file but, started to fall asleep while figuring out how I was going to play with the information. 

**Thoughts**: Sleep.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)

### Day 30: May 25, Thursday

**Today's Progress**: Still getting lost in JSON parsing, finally got it running but, there was at least 40 mins lost to figuring it out. The rest of my time I spent on making the JSON info prepend to the screen. Also, spent a solid 2.5 hours at work going through more Git tutorials. Gonna finish one last one, hosted on Udacity before I leave Git alone for a while. 

**Thoughts**: I need to figure out JSON.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)
2. [Udacity Git course] (https://classroom.udacity.com/courses/ud775)


### Day 31: May 26, FRIDAy

**Today's Progress**: Stuck at work all day and with the baby all night, no real work was possible. Got to continue a bit of the Udacity course.

**Thoughts**: Meh

**Links to work**:
1. [Udacity Git course] (https://classroom.udacity.com/courses/ud775)

### Day 32: May 27, Saturday

**Today's Progress**: A bit of the Udacity course, a bit of reading a JS reference manual and a bit of editing on tracker.

**Thoughts**: I would have liked to do more but, too busy today.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)
2. [Udacity Git course] (https://classroom.udacity.com/courses/ud775)

### Day 33: May 28, Sunday

**Today's Progress**: Same as yesterday but more of it. A solid 2 hours continuing with the Udacity Git course and another 90 minutes jammin' with functions in my tracker, I got some basic input / output functionality working.

**Thoughts**: Much more needs to be done.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)
2. [Udacity Git course] (https://classroom.udacity.com/courses/ud775)

### Day 34: May 29, Monday

**Today's Progress**: Cleaned up my json files, making it easier and more logical to filter through them. Also made fair few functions for said filtering. A lot of my time, did get lost in organizing the data, post filter but, it would have been worse without.

**Thoughts**: I should try to break the final returned string up into the individual paragraphs. It won't help a great deal but, it might make it a little easier to read at the start.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)


### Day 35: May 29, Tuesday

**Today's Progress**: Finished lesson 3 of Udacity's Git tutorial, took about 2 or 3 hours to do so.

**Thoughts**: The baby was less than kind to my sleep schedule last night, making any creative or thinking-heavy activity something to be avoided, plus I really want to get this course out of the way before getting back to my project, should be done by this weekend.

**Links to work**:
1. [Udacity Git course] (https://classroom.udacity.com/courses/ud775)

### Day 36: May 31, Wednesday

**Today's Progress**: Continuing to clean up the data that'll be used later. Less programming really and more reorganizing some written files so that they'll play nice with the program.

**Thoughts**: It's boring ass work but, I can't automate any more of it than I have already. This will take at least another 5 hours to get through, ugh.

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)

### Day 37: June 01, Thursday

**Today's Progress**: Finished Udacity's Git & GitHub tutorial.

**Thoughts**: This was the fourth and final tutorial I'll be taking on git for a while. For the last two weeks I have spent at least a dozen hours reviewing the basics and learning some neat tricks like password caching, aliases and some bash file edits for coloring and styling git in the terminal. I think I'll be able to simply google individual problems now, without being overwhelmed by all the interrelated parts.

**Links to work**:
1. [Udacity Git course] (https://classroom.udacity.com/courses/ud775)

### Day 38: June 02, Friday

**Today's Progress**: Continuing to clean up the data that'll be used later. Nothing but organizing my JSON files.

**Thoughts**: So boring. I'm gonna cap each description type to just 10 entries for now. That's still gonna take another few hours to get through but, it'll get me back to proper programming more quickly.            

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)

### Day 39: June 03, Saturday

**Today's Progress**: Continuing to clean up the data that'll be used later. Nothing but organizing my JSON files.

**Thoughts**: I'm going to abandon this project. While scrubbing the data I calculated how many words I would need to have enough for a random selection of paragraphs related to the performance of the student. It was in excess of 160,000 words. That's a couple of novels in length. Even just focusing on the "bell" in the data would require 30,000 words. And, every 100 or so would be broken up to form a new paragraph that says about the same thing as the last; it would be writing a novel that only says one thing 3,000 times. With that said, I will branch this project and see what I can do with it as a end of year report randomizer, maybe as a chrome plugin. We'll see.               

**Links to work**:
1. [Tracker](https://github.com/Spazcool/tracker)

### Day 40: June 04, Sunday

**Today's Progress**: Read through the first You Don't Know JavaScript book and finished the exercise at the end. 

**Thoughts**: I haven't read much of this series and already it's feeling a bit theoretical for where I stand with JS. I'd prefer something that have a chapter on a topic and then have you puzzle out a problem related to said topic. Perhaps this series will get there if I give it a chance. I just want to code.             

**Links to work**:
1. [simple exercises](https://github.com/Spazcool/p1xt-guides/tree/master/exercises)

### Day 41: June 05, Monday

**Today's Progress**: Read a bit more of YDKJS, learing about clousures and scope. On top of that, I've been playing around with vue.js for the past couple of hours making little methods that interact with my html.

**Thoughts**: Too much to learn.            

**Links to work**:
1. [me playing with Vue.js](https://github.com/Spazcool/vuePlayground)


### Day 42: June 06, Tuesday

**Today's Progress**: Read more of YDKJS, finishing chap 3 of Scope and Closures. Spent most of my time, however, running through more vue.js tuts. Made a mini-reddit and some auto-editing divs. 

**Thoughts**: Very confused. I feel like vue is a really powerful tool that might be too much for something that I'd be able to make. Still, I need to learn it and it does seem pretty cool.          

**Links to work**:
1. [me playing with Vue.js](https://github.com/Spazcool/vuePlayground)
2. [You Don't Know JS notes and exercises] (https://github.com/Spazcool/p1xt-guides)


### Day 43: June 07, Wednesday

**Today's Progress**: Read more of YDKJS, finishing chap 4 & 5 of Scope and Closures. 

**Thoughts**: I definitely feel that I have a better understanding of scope and also how that relates to the engine processing the code before runtime. However, closures still seem weird and ill-defined to me.        

**Links to work**:
1.  [You Don't Know JS notes and exercises] (https://github.com/Spazcool/p1xt-guides)

### Day 44: June 08, Thursday

**Today's Progress**: Guys at the Bunker convinced me to give React another try, spent a couple of hours going through the official React tutorial, creating a tic-tac-toe game. 

**Thoughts**: I don't think I know the basics of the language nor more advanced architectuarl concepts well enough to really get a hang of this stuff at this time. I'm gonna follow one more tutorial today, hoping to at least get familiar with the basic input/output of React, if not 100% confident on creating something with it.    

**Links to work**:
1.  [React Tutorial] (https://facebook.github.io/react/tutorial/tutorial.html)

### Day 45: June 09, Friday

**Today's Progress**: Got about half way through the Lynda.com introduction to React tutorial. 

**Thoughts**: Still not really getting it.    

**Links to work**:
1.  [React playground](https://github.com/Spazcool/reactPlayground) 

### Day 46: June 010, Saturday

**Today's Progress**: Pushed through another 30% of the Lynda.com course, got the notepads and the board working but, still need to add some functionality to it.

**Thoughts**: Still have the training wheels, need to create something of my own.    

**Links to work**:
1.  [React playground](https://github.com/Spazcool/reactPlayground) 

### Day 47: June 11, Sunday

**Today's Progress**: Tweaked some functions for styling purposes in the Lynda.com React course.

**Thoughts**: Exhausted today.  

**Links to work**:
1.  [React playground](https://github.com/Spazcool/reactPlayground) 

### Day 48: June 12, Monday

**Today's Progress**: 3 hours staring at the WeChat app source code.

**Thoughts**: I understand nothing.  

**Links to work**:
1.  private repo

### Day 49: June 13, Tuesday

**Today's Progress**: Finished the bulletin board app for Lynda.com, got stuch with some errors on npm.

**Thoughts**: Oy.

**Links to work**:
1.  [React playground](https://github.com/Spazcool/reactPlayground) 

### Day 50: June 14, Wednesday

**Today's Progress**: Fixed the admitedly minor npm error for the React bulletin board app. Also read the first two chaps in This & Object Prototypes YDKJS. 

**Thoughts**: I don't have the faintest grasp of what is going on with "this", every example given in the book is one where I could just as easily write without using "this". So, I don't know how or why I'd use it.

**Links to work**:
1.  [You Don't Know JS notes and exercises] (https://github.com/Spazcool/p1xt-guides)


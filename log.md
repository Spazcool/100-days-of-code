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

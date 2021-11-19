# 100 Days Of Code - Log

### Day 0: November 1st, 2021
#####

**Today's Progress**: Got back up to speed (after not working on it for weeks) and made updates to capturing the Channel Id and sending that information to the database.

**Thoughts:** For whatever reason, I pushed off starting....eventually, though, when I sat down it all felt natural and time slowly disappeared. 

I'm going to try to expand on my toolset in the coming days (as an example, committing my project to github through the terminal vs. the UI) and will one day explain some about the project but trying to start things on a good footing.

Somethings to come:
- Clean up this repo (appreciate the template @kallaway)
- Learn a little markdown in the process
- Expand my experience with git and Github
- Update high-level project description

-----

### Day 1: November 2nd, 2021
#####

**Today's Progress**: Didn't make much progress, hit a roadblock for testing the Twitch API in an Extension Front End which I'll have to work around for now. I should be able to test via Twitch itself versus just entirely via local, but will probably sideline this specific item and come back to it later when I feel ready to spend enough time to figure it out.

**Thoughts:** I feel anxious knowing that I have to sit down and do 1 hour, but also excited about the potential progress and amount of work that needs to be done. I feel like my setup and tools need a lot of attention to make this a comfortable and truly enjoyable experience but I currently do not have the time to make large changes, so will slowly adjust until everything is right.

-----

### Day 2: November 3rd, 2021
#####

**Today's Progress**: Ignoring the roadblocks from yesterday, as the source issue continues to pile up today, I was able to make pretty decent progress on a path forward. Stubbed out the request to get data from the database and the handler for that on the backend. Confirmed and tested that they are both working properly, so the next step is to actually build the query to the database and return the results.

**Thoughts:** Another day of gently wanting to put it off. Today was really busy overall so I started much later today than normal. This is a great viewport into what things will be like on hectic days. I'm tired from the day but it felt good to sit down and focus. Time actually flew by as I was coding, but I still feel like I'm spending too much time on other things like documentation, writing notes, planning code, etc... I think its a good use of time thought and I'm sure its part of the process but just a feeling. 

(Sidenote: I feel like I should have started count at 1 instead of 0. May change in the future. XD)

-----

### Day 3: November 4th, 2021
##### SKIPPED

-----

### Day 4: November 5th, 2021
##### SKIPPED

-----

### Day 5: November 6th, 2021
#####

**Today's Progress**: Spent most of today getting my project environment setup on a different computer. Once I got everything resolved, had to figure out where I left off and was able to clean up the GET request a little. More progress to make.

**Thoughts:** I don't even know where to begin. Its been a long past 3 days. Due to some life events was unable to make any progress, though I was some level determined. When I was able to make some progress, I didn't know where to begin considering that I'm on a different computer and the idea of pullin my code down onto this computer would require me to reset up my environment form scratch. This thought put me off for a day and I knew I had to make progress some how, so I bit the bullet and spent hours getting things back into working order.

Obviously, I've skipped a few days and will have to make those up, with interest, so I'll think on that, but I'm thinking an extra day of work (2 days / day skipped). I have time, since I'm still early on, but I have plenty of other goals that I've got to reach, so will work on those. Forgive me all for the skipped days.

-----

### Day 6: November 7th, 2021
#####

**Today's Progress**: Made some progress on tying the database to the code a bit. Not quite as much as I would have liked but its progress. Also did a first pass on a few files for cleaning up the code, comments, and structure that is there.

**Thoughts:** Getting back into the grove of things has been good, but below are some general thoughts I've had for a little while but I've neglected to properly document.

"More hard work than exepected, naturally"

I think I severly underestimated the amount of work necessary to build this. Its not overly complicated or anything but my skills aren't where I thought they were, factoring in a database and having to build and test locally with it has added an additional layer of challenge, working with platform specific nuances has defintely been challenging to wrap my head around, etc. I know I generally underestimate the amount of work but I missed the mark more than usual.

"Unweildy code base, getting worse and worse"

As I've started jumping in each day to make progress, my focus is on getting right to it and writing something to make my time productive. That being said, it has lead down a path of constantly adding onto the existing code base, switching what I'm working on based on hurdles, and not coming back to clean up where I left from. All this to say, its a bit of a mess with the comments and unused code and existing code from the template I was starting from. The hope/plan is that over time, it gets cleaned over time as I work through things.

"Love comments but making it more difficult"

I actually really enjoy using comments, they help me keep organized and help me remember certain things, but thats not to say they don't have their drawbacks, one of them being that all the comments being left all over the place are making it difficult to figure out where I should start working next. I put TODOs in my comments and they are everywhere. I think I need to work better on removing them when they have been handled and tighten up the content of them as I'm writing them. Again, this is another area of improvement as time goes on, so looking forward to how these things improve.

-----

### Day 7: November 8th, 2021
#####

**Today's Progress**: Decided to attempt and tackle the helixToken issue that I have been working around the past few days. Was able to get past the assumed hurdle of having to upload the files or intentionally connect to the developer rig. Was able to test out the solution of using the Twitch Front End API with the helixToken JWT. Will have to pivot after learning that said solution won't work.

**Thoughts:** Today was a good day. Wasn't too stressed or thinking too actively about working on it and it kinda felt natural. In typical developer fashion, spun my wheels looking at a problem for a mistype combined with Javascript to be the cultprit. Regardless, was able to get past it and continue to work well with the api, tools, and platform as they are. The solution I had in my head won't quite work the way I was thinking it was, so I'll have to pivot and come up with another option.

-----

### Day 8: November 9th, 2021
##### SKIPPED

-----

### Day 9: November 10th, 2021
##### SKIPPED

-----

### Day 10: November 11th, 2021
##### SKIPPED

-----

### Day 11: November 12th, 2021
##### SKIPPED

-----

### Day 12: November 13th, 2021
##### SKIPPED

-----

### Day 13: November 14th, 2021
##### SKIPPED

-----

### Day 14: November 15th, 2021
##### SKIPPED

-----

### Day 15: November 16th, 2021
##### SKIPPED

-----

### Day 16: November 17th, 2021
##### 

**Today's Progress**: Been playing around with the MongoDB database. Last time, ran into an issue of trying to figure out the uniqueness for the stream and how we tie that to the Submission, so now switching to set the data correctly in the api and having the records created properly in the database. (minus the unique stream identifier)

**Thoughts:** Took a much longer break than I intended, was seriosly tempting to just let it go but a friend asking about the status was the small push I needed to weave back into do this. I'm obviously been slacking on doing it the proper way, but this has been a good intro around getting back into the mindset and zone, so I'm not gonna complain and continue to try and stick to it.

Took some time to get back up-to-speed with where I left off, which was a little off-putting, but eventually found a good starting place. I still have to figure out a proper solution to my current problem, but its par for the course. Would really like to get this out by the end of the year which will require a bit more work on my end.

-----

### Day 17: November 18th, 2021
##### 

**Today's Progress**: Was able to resolve the database issue, wasn't cache like I was thinking. The reason it wasn't working as expected makes sense, it was due to having to change the local port for the database, but I don't quite know why I was receiving the data issues that I was. Just had to update the port that the clients were attempting to connect to and everything started working as expected.

Todays big issue after that resolves around a core/fundamental design issue with how the app/tool is supposed to work and be used. Have to figure out a plan working around some unique-ness issues and some viewer and streamer use-cases that I don't quite like.

**Thoughts:** Feels good to remove a roadblock and have another one put in place. lol. The really challenging issue now is dealing with some core design paired with some implementation challenges. I'm struggling to come up with a proper solution and since its paired with some limitation on the platform it makes it all the more harder to deal with, feels like a huge weight. The most difficult part of it is wanting to commit and complete an app, but the initial idea seems more and more difficult and useless as time goes on. Will keep on chugging I guess...


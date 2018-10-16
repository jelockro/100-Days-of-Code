# 100 Days Of Code - Log

### Day 0: August 10, 2018 

**Today's Progress**: In the process of moving fetch requests to service worker.  Stalled out at opening transaction on database. For some reasont he database is also consoling as null.

**Thoughts:** Very tired today.  Really look forward to solving this issue.

**Link to work:** [Restaurant Survey App](https://github.com/jelockro/mws-restaurant-stage-1)


### Day 1: August 11, 2018 

**Today's Progress**: Was able to access database and create transaction on it, as well as fetch the json data within the serviceWorker. 

**Thoughts:** I feel like I'm getting very close to solving this piece.  Once I am done, I need to work on understanding how to use gulp and node and babel so that I can modularize my code and import the modules I need.  I know my code is not DRY, but once I get everything working I would like to focus on cleaning up the code and modularizing it.

**Link to work:** [Restaurant Survey App](https://github.com/jelockro/mws-restaurant-stage-1)

### Day 2: August 12, 2018 

**Today's Progress**: Was able to fetch assets out of indexedDB.  Still running into lots of bugs.

**Thoughts:** I thought I had the site up and running, and was running lighthouse audits, and then for some reason I am having database issues again.  I've spent the whole day debugging. Feeling a bit frustrated. I haven't pushed my commits yet, but will do tomorrow.

**Link to work:** [Restaurant Survey App](https://github.com/jelockro/mws-restaurant-stage-1)

### Day 3: August 13, 2018 

**Today's Progress**: I passed my lighthouse audit requirements and got my app working offline...kind of...

**Thoughts:** I presently am caching the database file that holds the idb code, which doesn't work for when I upgrade the database, and so I need to move that over to serviceworker. Started my first day in LaunchCode 101 class.  I am very excited and feel blessed that I have had these opportunities.

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 4: August 14, 2018 

**Today's Progress**: everything's broken

**Thoughts:** I tried to use too many tools.  I don't know how they all are supposed to work together, and I am running out of time.

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 5: August 15, 2018 

**Today's Progress**: Making progress understanding browserify and starting to understand how bundling works.  But my project is quite broken.  I think I will need to step back and develope a simpler solution

**Thoughts:** I think I will need to step back and develope a simpler solution

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 6: August 16, 2018 

**Today's Progress**: I was able to get the app working again.  At least the css is showing up again and the map works. Once i figure out how to bundle the databasehelper code so it has access to idb module, it should work again.

**Thoughts:** I made a good decision trying to revert to a simpler solution.  If I can get the project sent in, then I can work on learning things like babelify and making more complex script bundles.

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 7: August 17, 2018 

**Today's Progress**: I got the app working and passed all tests, sent it in to review and passed with flying colors. Feeling very proud of myself. 

**Thoughts:** I am very eager to start refactoring? (not sure that is the word) the code so that I can take advantage of modularized javascript.  I think it would be helpful to do the broswerify tutorial and start with very simple scripts and experiment with bundling them, and then eventually start to break apart the scripts in my project to their components.  

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 8: August 18, 2018 

**Today's Progress**: Worked on some backend python server stuff.  

**Thoughts:** Not going to look at the restaurant app code this weekend.   

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 9: August 19, 2018 

**Today's Progress**: Worked on assignments for launchcode using the python turtle library.  

**Thoughts:** Continued the part 3 learning in the udacity program.  Learned that with http/2 bundling & concatenating scripts is no longer be best practices.  HAH! Also learning about security.  I had been using public and private keys for cryptocurrencies and never realized the very concept was behind https.  I've just been using these tools without really understanding why or how they work. 

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 10: August 20, 2018 

**Today's Progress**: Worked on an assignment for launchcode using classes and class-inheritance.  A bit overkill for the requirements, but this is the first time I ever successfully built a class from scratch and it worked. I'm adding the code to my repo. Also created a ridiculous list splicing solution to a problem that was basically a three-liner using modulo.  

**Thoughts:** Solving the problems for the launchCode course is a lot more fun now that I have spent some time programming in python and javascript.  I think it's neat that I'm already starting to approach problems with an object-oriented perspective.  Probably due to the time spent in javascript.  

**Link to work:** [Wagon Wheel Solution] (https://github.com/jelockro/LaunchCode_101/blob/master/goMike.py

### Day 11: August 23, 2018 

**Today's Progress**: Learning Go and Dapp development.  https://tour.golang.org/moretypes/18 https://goethereumbook.org/ethereum-development-with-go.pdf
The last couple days I've been upgrading my laptop and working on a wordpress migration.

**Thoughts:** I need to get back to working on my restaurant survey app. I will still have time tonight to do that.  I'm just hitting a wall of interest.  I think what I will do is finish the survey app, and then dive into Go and Dapp development.

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/mws-restaurant-stage2)

### Day 12: August 24, 2018 

**Today's Progress**: I got my development environment ready for the third stage of the Udacity project.  I also found some svg's for the 1st part of the project which is adding favoriting capability.  I also learned a little about svg.  

**Thoughts:** I think SVG's are awesome, and I can't wait to play around with some css tricks and svg's. especially for some neat interactive homepages.  Alas, I have to work on this app and it is due in 15 days.  I wish I was more confident in implementing this stuff, but I guess that is why I am learning.  

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/MWS-Stage3)

### Day 13: August 25, 2018 

**Today's Progress**: I don't have the favorite toggle working yet, but I think I know the path I need to go down to get it finished. 

**Thoughts:** I need to be able to update the server and the idb when the favorite svg is clicked, and then somehow get the svg to change.  

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/MWS-Stage3)

### Day 14: August 27, 2018 

**Today's Progress**: I got the favorite svg to update everything on toggle, and for the dom elements to refresh.  Currently the refresh method I am using is causing some bugs in other areas of the dom, but I think I know why.

**Thoughts:** I need to break apart my fillHtml code into smaller fragments, so I can call the ones I want in particular circumstances.  

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/MWS-Stage3)

### Day 15: August 28, 2018 

**Today's Progress**:  I added a form to add reviews and some early javascript for the form.

**Thoughts:** I need to break apart my fillHtml() code into smaller fragments, so I can call the ones I want in particular circumstances.  I also need to create an IDB store for reviews and some syncing functionality so that if the user is offline, it will store the data and sync later.  I think I can get this done before the 8th. Everything is going to be broken for awhile as I revamp the DBHelper code.  

**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/MWS-Stage3)

### Day 16: August 29, 2018 

**Today's Progress**: I refactored the database helper code.

**Thoughts:** I felt really proud of myself that I was able to refactor the code into something I understood better.  I'm seeing the light at the end of the tunnel.
**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/MWS-Stage3)

### Day 17: August 30, 2018 

**Today's Progress**: Fixed the toggle code, will finish the review form code tomorrow.

**Thoughts:** So Close!!!
**Link to work:** [Restaurant Survey App] (https://github.com/jelockro/MWS-Stage3)


### Day 18: August 31, 2018 

**Today's Progress**: reviews post to idb.  

**Thoughts:** Now that reviews post to idb, I need to work on the syncing code that will Put the changes to the server when the client is online.  If I have time before the 8th, I would like to really clean up the DBHelper.js code.  It's a mess.
Plus, I don't like how github measures contributions.  I am using forks, so showing no contributions.

**Link to work:** [Restaurant Survey App](https://github.com/jelockro/MWS-Stage3/tree/master)

### Day 19: September 1st, 2018 

**Today's Progress**: favorite toggle works offline, and data syncs when online, reviews are syncing correctly yet.

**Thoughts:**  I have another project I am working on called 'Scrooge', which I always envsioned being used offline and online.  Now I know how to implement that functionality.  I think the bigger challenge will be the server-side code, which is not something I really worked with in this project.

**Link to work:** [Restaurant Survey App](https://github.com/jelockro/MWS-Stage3/tree/master)


### Day 20: September 2, 2018 

**Today's Progress**: Everything works, and project has passed lighthouse scores.  Sending it in for review, I shall find out tomorrow how I did.  Finger crossed, it feels good to have the project ready to turn in before the deadline.

**Thoughts:**  I don't know if I want to work on the scrooge project or a vr/ar project. I mean, I guess if I had to choose, I would choose the vr/ar project and take the opportunity to learn C# and C.  I also have a dashboard I was going to create to remotely monitor my mining rigs.  nextProject = random.randrange(3).

**Link to work:** [Restaurant Survey App](https://github.com/jelockro/MWS-Stage3/tree/master)

### Day 21: September 8, 2018 

**Today's Progress**: I am putting together my next project, it is a quantitative trading application, that allows the user to choose which cryptocurrency to pull daily data from an api, and then allows the user to choose which machine learning algorithms to process the data from.  Basically, creating a web-based UI for earlier scripts.

**Thoughts:**  I really was hoping to start working with node and gulp, but I want recruiters to be able to see that I have worked with machine learning.  Also, I am more motivated to refine the Scrooge app later, and will be happy to get back into javascript with that project.  I may still use incorporate javascript for its fetch capability, but I might just used the native python requests.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 22: September 9, 2018 

**Today's Progress**: I worked on some cryptography scripts for launchcode.  I used try/excepts and argument vectors for the first time, as well as import statements for my own code. 

**Thoughts:**  Python is not that bad.  I find that I can write code faster in python than in javascript.  I don't get into as many syntax problems.  My python linter seems to scream at me, but maybe that's a good thing.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 22: September 10, 2018 

**Today's Progress**: worked on bubblesort for launchcode, and fixing python environment in QuantTrading.  Learning how python environments work under the hood, so I can troubleshoot things and just do things right since if I don't activate the environment right on my mac, I'll end up using 2.7 and having all sorts of problems down the road.

**Thoughts:**  I was working through bubble-sort with another peer and her code was very clean and short.  I was making things way too complicated using recursion....and the whole time I simply was blind to how her while loop affected her code.  I am very frustrated with myself that it took me like 20 minutes before I was able to see what was going on.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 23: September 11, 2018 

**Today's Progress**: Spent most of the night getting my vr/leap motion development environmentsetup.  Using VRigdge & SteamVr for testing and Unity for development 

**Thoughts:**  I was working through bubble-sort with another peer and her code was very clean and short.  I was making things way too complicated using recursion....and the whole time I simply was blind to how her while loop affected her code.  I am very frustrated with myself that it took me like 20 minutes before I was able to see what was going on.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 24: September 12, 2018 

**Today's Progress**: Spent a few hours learning and using pipenv & virtualenv, fixing paths and .bashrc and I followed along the udacity course on git.

**Thoughts:**  Trying to clean up my commit style.  I also want to make sure that github repo shows a steady flow of commits.  I would like to go through my github, update readmes & refactor code. 

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 25: September 13, 2018

**Today's Progress**: worked on a yahtzee python game for launchcode 101

**Thoughts:** again I tend to overcomplicate things.  Also, I need to write a lot more classes.  I am looking forward to writing modular css, js, and python this next month. 

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 26: September 16, 2018

**Today's Progress**: finished writing some code for launchcode.  Writing classes, importing, and using if __name__ == __main__ to differentiate from importing the class from running the file as a script. I like that flexibility, though don't know for sure when I will use it. Started learning c.

**Thoughts:** I'd like to write some code from scratch using python, but it seems I am always importing some library, and working off of a template.  Also, it seems I spend a lot of time understangin the API's for packages like webpack of Flask, rather than writing my own packages. Someone in our AR discord group was working on an open source vr fork.  I looked through the repo to find it was written in c. For some reason I have been intimidate by c, but it looks accessible.  Wrote my first hello-world program.  I think it's cool that I can compile code and create executables.  I look forward to progressing in c, but I've got a lot on my plate.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 27: September 17, 2018 

**Today's Progress**: added login requirements for my application via flask.

**Thoughts:**  I almost got blocked today thinking that I needed to understand the database schema, then decided to keep it simple and just iterate complexity as I realiaze what I need.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 28: September 18, 2018 

**Today's Progress**: added react to my project

**Thoughts:**  I am looking for a react tutorial so that I will better understand react components, also so I will know where to put directories for my project, which always seems to be a hurdle for me.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 29: September 19, 2018 

**Today's Progress**: Lifting state into parent components with tic tac toe https://reactjs.org/tutorial/tutorial.html#overview

**Thoughts:**  A little intimidated by this material, but can't wait to master it and start using it in my project.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 30: October 4, 2018 

**Today's Progress**: 3d printers, emacs, git merge conflicts, and a better way to c.

**Thoughts:**  I have been coding here and there, but work and my wife's imminent due date has been keeping me from being more disciplined about updating everything. I honestly can't keep track of what I've done over the days so I am just going to update everything on this day.

I started Stanford's CS106B - Programming Abstractions to learn C.  However, the free course is too outdated.  I created a virtual ubuntu 32 bit box to try to keep up, and tried to learn emacs to write code and compile everythnig from the terminal.  emacs is a diaster.  I was using hyper and I just didn't have the patience to try to get everything configured correctly.  I did manage to work through emacs included tutorial for their ede.  But I did something wrong in the directions, and the emacs ede project won't compile.  I will have to delete everything and start over, but then I'm thinking, why?  learning emacs, to write c via a terminal seems to be an unnecessary learning curve to C.  

I also received and put together my 3d printer.  And today I am configuring Cura with the help of online tutorials to create a good profile so I can print the frame for project Northstar.  Today, Sam also gave me the lenses he had CNC'ed.  Which is awesome, but instead of the three pairs he thought he could make I only got one.  So I will have to be extra careful sanding and making them reflective.  

Today at launchcode I helped classmates with the lesson or "studio" on git and github.  I enjoyed the part where we teamed up and dealt with merge conflicts. 

Still no progress with react, though I have some great articles come into my inbox from medium, but I am very backed up with reading.  I also need to catch up with the career stuff from udacity, which I haven't been able to even read.  

I've over-extended myself on projects, I can tell that now.  Apparently github is also counting my contribution to this repo, which is great, as before I didn't believe they were getting counted.  This gives me a bigger incentive to keep doing this for another 70 days!


**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 31: October 09, 2018 

**Today's Progress**: I worked on the 3-d printer, and installed software & firmware on mac.  

**Thoughts:** Baby arrived Sunday night. It's Tuesday night and I'm pretty darned tired, but I wanted to spend some me time with the 3d printer.  Of course I jam it more than anything I've seen on the internet. So I take it apart, and thankfully it is working again.  Was hoping to do some configuration prints, but spent most of the night on the jam/clogged hot end.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/QuantTrading)

### Day 32: October 10, 2018 

**Today's Progress**: started a tutorial on implementing material design into my project.  I really like their theme for finance, and I hope to implement it into scrooge later, but now implementing into the launchcode project html-me-something, but will be useful for quant-trading. 

**Thoughts:** I plan on updating quant-trading's front-end during this stage of launchcode and then developing the backend in the next stage. I am working on upping my game by using material design.  I feel like I have webpack down pack, although I don't have any special tooling to auto-compile at the moment. But I am using babel more fluently, bundling js, and hopefully going to getting more familiar with sass.  

I also need to hook up my laptop to the 3d printer and get things configured, but not tonight.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/html-me-something)

### Day 33: October 15, 2018 

**Today's Progress**: Managed to get the modal drawer and top-app-bar from google's material design working on my launchcode project.  

**Thoughts:** I hope to recreate their rally theme to be used for quant-trading and eventually Scrooge.  I will try to implement as much of what I want in scrooge in quant-trading from a design perspective.

**Link to work:** [Crypto Quant Trading App](https://github.com/jelockro/html-me-something)


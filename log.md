# 100 Days Of Code - Log

### Day 0: March 9th 2019 - Saturday

**Today's Progress**: Forked the repo, downloaded a bunch of tools: bash, node.js, powershell, LUIS etc. Started in the Azure portal building a web app bot that will be a virtual assistant. Also started some prep for a twitter bot using python. 

**Thoughts:** There's a lot of prep work outside of the actual code. But the instructions are really good these days, so I'm optimistic. Turns out it might take a few days to get developer keys from Twitter, new rules they seem to have introduced within the last 6 months

**Link to work:** Nothing to see here yet :-( 

### Day 1: March 10th 2019 - Sunday

**Today's Progress**: Did some more stuff in Azure with the AI Bots and found some more Python chatbots to play with. I also played codecombat for an hour, to practice my python skills

**Thoughts**: Lots of stuff is out of date, libraries don't match. PIL has not been ported to Python 3 yet and I don't have a clear understanding of how to get similar functionality out of other standard libraries. The research part is not as fun as the coding part and it's frustrating to try and do and understand stuff when it doesn't work anymore. But little by little I am progressing.

**Link(s) to work**: I started some files for each day so you can see the code I am playing with.

### Day 2: March 11th 2019 - Monday

**Today's Progress**: Got my Twitter developer access. Solved some more problems in CodeCombat.

**Thoughts** I need to do this at the start of the day, I'm too tired at night.

**Link(s) to work** See Day 002

### Day 3: March 12th 2019 - Tuesday

**Today's Progress**: Under the recommendation of @nnja I started the python build a github bot tutorial by @Mariatta

**Thoughts** An hour is not enough to feel like I'm making progress. I don't want to stop when I get it, and I do want to stop when I'm frustrated, but my brain calls me a quitter if I stop then.

I did another hour this evening, and I feel better. Not everything works as expected, but I am able to do a bit of limited troubleshooting and really enjoyed how far I got tonight. Everything I learn leads to more questions though.

**Link(s) to work** https://github.com/msandfor/github-bot-tutorial I'm up to here: https://github-bot-tutorial.readthedocs.io/en/latest/gidgethub-cmd-line.html

### Day 4: March 13th 2019 - Wednesday

**Today's Progress**: It wasn't quite working last night, so I redid some aspects of the bot and went a bit further. The first part is complete now, it's deployed in Heroku and it responded to a comment in my repository!

**Thoughts** I thought I'd have to redo everything, but it's more like 2 steps forward and 1 step back. Just when you think it won't work, it does.

**Link(s) to work** https://github.com/msandfor/snickers/issues/1

### Day 5: March 14th 2019 - Thursday

**Today's Progress**: Did a Kubernetes workshop.

**Thoughts** Discovered sometimes it's not me, it's you. i.e. I didn't have all those lines of red code because of mistakes I was making. All my Microsoft buddies got the same error when using our work subscription. So something was locked down for us. But I also saw stuff that everyone knows how to do, I wouldn't have known how to do 2 weeks ago, and now I did it as quickly as they did.

**Link(s) to work** https://github.com/msandfor/kubernetes-on-azure-workshop/blob/master/slides/kubernetes-101/Kubernetes-101.pdf
https://docs.microsoft.com/en-us/Azure/containers/

### Day 6: March 15th 2019 - Friday

**Today's Progress**: Continued with my Python Github bot, I'm now trying to get it to Say thanks when an issue has been merged¶

**Thoughts** I know now why developers have so many screens, it really would be easier if I could see the documentation on one screen and the instructions, and then the code screen in another. There is not enough room on one screen for 3 windows.

**Link(s) to work** https://github-bot-tutorial.readthedocs.io/en/latest/gidgethub-for-webhooks.html

### Day 7: March 16th 2019 - Saturday

**Today's Progress**: Finished the Python bot from @Marietta - I mean not all the optional extras, just the standard part

**Thoughts** I'll probably move on and try other tutorials, and then come back to the extras as I become more confident.

**Link(s) to work** https://github.com/msandfor/webservice

### Day 8: March 17th 2019 - Sunday

**Today's Progress**: Woke up with a headache, so decided to play codecombat until the drugs kicked in. Then I looked at NLP chatbots from @ParulNith and was able to figure out why ROBO wasn't running and get it going. Followed the Azure learning path: Create Intelligent Bots and built a Bot using Q and A maker, attached it to a web app 

**Thoughts** Discovered that sometimes I can't see the errors in my code, no matter how long I stare at it, and then after I wiped the whole page and started from scratch - I did it perfectly the first time. Most of the time I think I can't do stuff from scratch, I always need to build on other peoples work, or see an example before I can do my own. And then this happens. Following the learning path to create the Q&A bot was fun and easy. I'm eager to do more like that.

**Link(s) to work** https://codecombat.com/play/forest https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e
https://docs.microsoft.com/en-us/learn/paths/create-bots-with-the-azure-bot-service/

### Day 9: March 18th 2019 - Monday

**Today's Progress**: Started the Build a chat bot with the Azure Bot Service Module on Microsoft Lean. I've done 5 of the 8 modules, but I'm a bit confused at the moment. During this module I'm learning:
* Create an Azure Web App Bot to host a bot
* Create a knowledge base, populate it with data, and connect it to a bot
* Debug bots locally using Visual Studio Code and the Microsoft Bot Framework Emulator

But I've done something wrong, and I don't know how to undo it. I asked for help on Twitter and @antonjb replied telling me how to fix it - and I was able to redo that part.

So I did this: C:\Users\misandfo\Documents\Factbot>git remote add qna-factbot {https://LeoBotAdmin@snickerbot2.scm.azurewebsites.net:443/snickerbot2.git} and I think I should have done...

C:\Users\misandfo\Documents\Factbot>git remote add qna-factbot https://LeoBotAdmin@snickerbot2.scm.azurewebsites.net:443/snickerbot2.git

and now it says: 

fatal: remote qna-factbot already exists.

But I don't know how to un-exist it and try again...

But @antonJB replied on twitter with this solution:
you can see your remotes with `git remote -v` then remove the one you don't want with `git remote rm {REMOTE URL}`

and it worked!

But now I've reached a bit in the instruction where I don't know what it means.

**Thoughts** Either this will look better in the morning, and it'll be clear what I need to do, or I can ask one of the lads in the office to help me. So it's not too bad, surely? 

I was really happy when I asked Twitter for help and got the answer right away - I felt the love of my network and community.

**Link(s) to work** https://docs.microsoft.com/en-au/learn/modules/build-chat-bot-with-azure-bot-service/

### Day 10: March 19th 2019 - Tuesday

**Today's Progress**: 
Continued on with the tutorial. 
* Implement bots in code and debug the bots that you build
* Publish bots and use continuous integration to keep them up to date
* Debug bots locally using Visual Studio Code and the Microsoft Bot Framework Emulator

I was stuck on this bit for ages:
4. Confirm that "test bot endpoint at http://localhost:3978/api/messages" appears in the debug console.
Your bot code is now running locally.
5. Launch the Bot Framework Emulator from the Start Menu or launch icon.



**Link(s) to work** https://docs.microsoft.com/en-au/learn/modules/build-chat-bot-with-azure-bot-service/

### Day 11: March 20th 2019 - Wednesday

**Today's Progress**: 
I started to create a slackbot that would replace peoples faces with emojis.
This one used a sandbox in Azure, that has a time limited of 3 hours on it. Which makes it tough because usually I would do an hour at the start of the day and then finish up later. But I'll have to redo some parts of it, with this time limit. I got stuck again - the command func host start didn't work.

*** Thoughts***
POsted my progress to Twitter and got the answer back from @DavidWengier: Install core tools -
https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local

**Link(s) to work**
https://docs.microsoft.com/en-au/learn/modules/replace-faces-with-emojis-matching-emotion/4-create-an-azure-function-project

### Day 12: March 21st 2019 - Thursday

**Today's Progress**: 
Looked again at the slackbot tutorial that would replace peoples faces with emojis.
Stuck again in another place - don't see the Javascript Debug option as described in the tutorial. Think I need to start from scratch and double check every step.
Started playing with a Twitter tutorial, but it wasn't new enough to include the OAuth option, so put that aside too.

*** Thoughts***
A frustrating day because I couldn't find anything I could achieve in under and hour and I didn't have more than an hour to spend.

**Link(s) to work**
https://docs.microsoft.com/en-au/learn/modules/replace-faces-with-emojis-matching-emotion/4-create-an-azure-function-project

### Day 13: March 22nd 2019 - Friday

**Today's Progress**: 
Had another go at the slackbot tutorial that would replace peoples faces with emojis.
Worked all the way through it, but I'm still getting errors. I'll delete it again and have one more try tomorrow.

*** Thoughts***
Felt better for going all the way through it. I know I can do it. Just need to really focus.

**Link(s) to work**
https://docs.microsoft.com/en-au/learn/modules/replace-faces-with-emojis-matching-emotion/4-create-an-azure-function-project6. Select the Enter your endpoint URL field. Enter the bot name and the bot URL displayed in the debug console in the previous step.

Because the I didn't know what the bot name or URL field was. Eventually, after much thought, I decided that the bot name must be bot, and the URL must be http://localhost:3978/api/messages - obvious once I say it, but not obvious from the instruction.

**Thoughts** 
An unclear tutorial is confusing and offputting - but it's very satisfying when you figure stuff out and I am enjoying this more and more.

### Day 14: March 23rd 2019 - Saturday

**Today's Progress**: 
https://github.com/ykdojo/twitterbotsample

Learnt how to create a Twitter bot with Python and Tweepy! Also, here are the links mentioned in the video: - How to install Tweepy and the source code of this project: https://csdojo.io/twitter - PythonAnywhere (a referral link): https://csdojo.io/py And this was part of the: - Build a startup series: https://www.youtube.com/playlist?list... - As well as my Python tutorial series: https://www.youtube.com/playlist?list... And, you can find me on Twitter and Instagram @ykdojo!


*** Thoughts***
This was really fun. But I still need to figure out how to have it running all the time - so the cloud service part.

**Link(s) to work**
https://github.com/msandfor/botsnicker

### Day 15: March 24th 2019 - Sunday

**Today's Progress**: 

Spent a lot of time trying to figure out Heroku, and how to get the twitterbot running in the cloud. Still have not quite got it, but I enjoyed the troubleshooting

*** Thoughts***
Even though I didn't solve it, I still feel good.

**Link(s) to work**
https://github.com/msandfor/botsnicker

### Day 16: March 25th 2019 - Monday

**Today's Progress**: 

I thought a lot about how to connect my Twitter bot to the internet. I think I should be able to do it with the web server and some web hooks. I also went to #juniordev and I'm keen to have a go with #Flask There were 3 presentations, getting started with FLASK, with REACTJS and then some image optimisation and playing with CodePen

*** Thoughts***

I prefer to be following tutorials where I can write code and see what happens. But I know I need to try and understand some of the concepts to apply them to my Twitterbot, else I won't pick the right way to implement it. This is architecture.

**Link(s) to work**

https://www.meetup.com/Junior-Developers-Perth/events/259719006/

### Day 17: March 26th 2019 - Tuesday

**Today's Progress**: 

I started the Azure Fundamentals course, to try and get some of the concepts down. Still thinking about my twitterbot. I also installed a bunch of programming apps on my phone so I could learn on the go.

Setup my first Talk about my 100 days - It will be in May, so I'll need to start putting it together already

Completed my Azure Cloud Concepts - Principles of cloud computing

*** Thoughts***

Those apps seem mostly the sameish. But they are pretty good. To be fair, I've only tried 2 of them so far.

**Link(s) to work**

Apps: 
Programming Hub
SoloLearn
GrassHopper
Enki
Encode
Learn Python

### Day 18: March 27th 2019 - Wednesday

**Today's Progress**: 

I was looking at serverless logic and azure functions. There might be something there for my twitterbot. 
I also played codecombat for a couple of hours after dinner and looked at Grasshopper (javascript) and EnKi in the park whilst walking the dogs.

Completed: Create serverless logic with Azure Functions
Completed: Execute an Azure Function with triggers

*** Thoughts***

Not sure if this will be the cheap/freeish option I'm looking for, but it's worth exploring and understanding

**Link(s) to work**

https://docs.microsoft.com/en-au/learn/paths/create-serverless-applications/

### Day 19: March 28th 2019 - Thursday

**Today's Progress**: Looked at a bunch of Python bots, trying to understand the architecture and understand webhooks, webservices, github, heroku, azure apps etc

*** Thoughts***
Sometimes you have to slow down if you want to go faster.

**Link(s) to work**

### Day 20: March 29th 2019 - Friday

**Today's Progress**: I went to Rotto today for the Directors Forum, so I didn't have much time. But I did all my lessons on Enki. 


*** Thoughts***
Learning stuff like dictionarys and tuples and lists is super boring to me. I prefer doing stuff with the bots.

**Link(s) to work**

### Day 21: March 30th Day 2019 - Saturday

**Today's Progress**: 
Spent the whole day linking my twitter bot from https://github.com/msandfor/twitterbotsample/blob/master/my_twitter_bot.py to Heroku using http://briancaffey.github.io/2016/04/05/twitter-bot-tutorial.html

*** Thoughts***
Really pleased I got that working and I think I understand the different components and how they architect together now. Still stuff to learn - but I have one running, all the time now!

**Link(s) to work**
https://github.com/msandfor/botsnicker1


### Day 22: March 31 2019 - Sunday

**Today's Progress**: 

Played with an Instabot. Also setup my project repository and started writing the docs in Markdown.

*** Thoughts***
Really think I'm starting to understand how github works. I accidentally killed my twitterbot for a while, but it's all part of the process.

**Link(s) to work**

https://github.com/msandfor/RiseOfTheRoBots


### Day 23: April 01 2019 - Monday

**Today's Progress**: 
Worked on the docs in my Rise of the Robots repository. I want to re-document the tutorials, as I did them so others can follow

*** Thoughts***
Documentation takes more time than coding and is just as frustrating

**Link(s) to work**

https://github.com/msandfor/RiseOfTheRoBots

### Day 23: April 02 2019 - Tuesday

**Today's Progress**: 
Did some Markdown and HTML via @github learning labs today. If you haven't tried them, have a go, because a bot teaches the tutorial and approves your commits. 

*** Thoughts***
Love this bot that teaches me how to use GitHub

**Link(s) to work**

https://lab.github.com/

### Day 24: April 03 2019 - Wednesday

**Today's Progress**: 
More Github Learning labs. I want to learn how to make that bot

*** Thoughts***


**Link(s) to work**
https://lab.github.com/


### Day 25: April 04 2019 - Thursday

**Today's Progress**: 
I checked out @ChloeCondon 's very cool App on #github what a clever idea 

*** Thoughts***
Needs more study to see what can be done with this

**Link(s) to work**
https://github.com/ChloeCodesThings/sos-plz-save-me
https://medium.com/microsoftazure/an-ambiverts-guide-to-azure-functions-95931976c565
https://motherboard.vice.com/en_us/article/gyaaw7/this-fake-boyfriend-app-bails-you-out-of-awkward-moments
https://github.com/msandfor/twilio-csharp


### Day 26: April 05 2019 - Friday

**Today's Progress**: 

I did more @Github Learning Labs on Markdown, HTML and Apps. I  the bot that teaches me stuff and want to build one just like it. Think I'm gonna have to do #JavaScript as well, not just #Python because that's what the Probots are. So much more to know... #100daysofcode
Completed: Getting started with GitHub Apps

*** Thoughts***

**Link(s) to work**
https://lab.github.com/

### Day 27: April 06 2019 - Saturday

**Today's Progress**: 

Purchased a Flic button and set-up a Twilio account. Forked Chloes SOS directory and followed her instructions for setting up the Azure Functions.
Completed: Chain Azure functions together using input and output bindings
Completed: Create serverless applications

*** Thoughts***

**Link(s) to work**

### Day 28: April 07 2019 - Sunday

**Today's Progress**: 

Played Twilio Quest. It had a thing in it where you need to take your local page and use ngrok to put it on the internets. I had to use FLASK for the web side of Python, did that all ok - but was a bit baffled by the negrok stuff. Same as when I was trying to understand the place of Heroku in things. I followed the instructions, but it wasn't working. Phil Nash from Twilio helped me - he saw the port that Flask used was not the same as negrok had used - he told me how to make negrok use the same one - and then it worked! 

*** Thoughts***

I was really happy for three reasons:
1. When I am stuck, and I ask for help - someone helps me. The world should be as great as the developer community.
2. It was a small thing that was wrong. I had nearly done it all myself - so it wasn't as if I was completely hopeless. And it's always small things that are wrong. I can do this!
3. I feel like the concept is similar to the Heroku thing. I keep coming across the same architecture again and again - in different forms. I feel like I will get it, and then I will be able to bridge that gap in many ways. In fact, I think this is what I used Azure Functions for when following Chloes instructions yesterday.

**Link(s) to work**

https://www.twilio.com/quest/mission/13


### Day 29: April 8th 2019 - Monday

**Today's Progress**: 

Just did an hour of Azure Fundamentals like all the good Microsofties are doing this month. 

*** Thoughts***

Pretty tired, Mondays are the worst... We should get a 3 day weekend, every week.

**Link(s) to work**

https://docs.microsoft.com/en-au/learn/


### Day 30: April 09 2019 - Tuesday

**Today's Progress**: 

*** Thoughts***
Did some more Azure Fundamentals

**Link(s) to work**



### Day 31: April 10th 2019 - Wednesday

**Today's Progress**: 
Did another hour of Azure Fundamentals. I'm at Level 5 now. 
Did some of the chatterbot tutorial.

*** Thoughts***

**Link(s) to work**



### Day 32: April 11th 2019 - Thursday

**Today's Progress**: 

Did some more Azure fundamentals. Had to travel to Sydney.
My Flic button arrived!

*** Thoughts***

**Link(s) to work**


### Day 33: April 12th 2019 - Friday

**Today's Progress**: 
Started working on my virtal husband app, from Chloe Condon, now I have my Flic button

*** Thoughts***

**Link(s) to work**


### Day 34: APR 13th 2019 - Saturday

**Today's Progress**: 
worked through a bunch of @twilio tutorials, playing with the voice functions and trying to solidify in my mind how everything fits together. #100daysofcode

*** Thoughts***

**Link(s) to work**


### Day 35: APR 14th 2019 - Sunday

**Today's Progress**: 
Just did some more Azure Fundamentals today


*** Thoughts***

**Link(s) to work**


### Day 36: APR 15 2019 - Monday

**Today's Progress**: 
Got a Trophy from @Microsoft Learn for doing some more Azure stuff. This course is great for Business Decision Makers - gives a great overview of what everything is and the business case and strategy around choosing things

*** Thoughts***

**Link(s) to work**


### Day 37: APR 16 2019 - Tuesday

**Today's Progress**: 
I did some exam practice for Azure Fundamentals then I went to #juniodevperth which was awesome

*** Thoughts***

**Link(s) to work**


### Day 38: APR 18 2019 - Wednesday

**Today's Progress**: 
Still playing with Azure Functions and Twilio. Might try redoing my code in Python tomorrow as Javascript is not quite as pleasing to me

*** Thoughts***

**Link(s) to work**


### Day 39: APR 20 2019 - Saturday

**Today's Progress**: 
did some SoloLearn basic concepts on my phone at the airport. Got to admit, I find just learning syntax super boring
*** Thoughts***

**Link(s) to work**

### Day 40: APR 21 2019 - Sunday

**Today's Progress**: 
Had a look at a BroBot today. Seems like a fun idea. Based on the ELIZA concept but... well, more of a Bro

*** Thoughts***

**Link(s) to work**

### Day 41: APR 25 2019 - Thursday

**Today's Progress**: 
Day 041 played with some more of the tweepy and twitter stuff for my @BotSnicker today - trying to see what other functionality I can add #Snickers #100daysofcode

*** Thoughts***

**Link(s) to work**


### Day 42: APR 26 2019 - Friday

**Today's Progress**: 

Did some more azure functions, still trying to figure out Chloes boyfriend app functions.

*** Thoughts***

Think I need to spend a whole day quietly working on this, so I understand the end-to-end

**Link(s) to work**


### Day 43: APR 29 2019 - Monday

**Today's Progress**: 

Day 043 #100daysofcode Finished my Azure Fundamentals on @Microsoft Learn. I studied for a few hours this evening, because I'm going to try the exam tomorrow and it must be 20 years since I originally did my MCSE exams... We'll see

*** Thoughts***

**Link(s) to work**

### Day 44: APR 30 2019 - Tuesday

**Today's Progress**: 
Soo.....Day 044 #100daysofcode I passed my Azure Fundamentals exam today. Scored 865 - so I'd say the free course on #microsoftLearn is well worth the price. You may congratulate me now 


*** Thoughts***

**Link(s) to work**

### Day 45: May 01 2019 - Wednesday

**Today's Progress**: 
Day 045 I went to the #DevOps #DevOpsPerth meetup @Bankwest

*** Thoughts***

**Link(s) to work**

### Day 46: May 02 2019 - Thursday
Thought about Azure Functions and source code versioning

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**

### Day 47: May 03 2019 - Friday

**Today's Progress**: 

Day 047 I started a thing with @perth_web_girls which is gonna open up the world of #code to a bunch of mid-career/career-change women #100daysofcode

*** Thoughts***

**Link(s) to work**

### Day 48: May 04 2019 - Saturday

**Today's Progress**: 
Day 048 Went through the NLP Python Tutorials on @Codecademy
 Updated my presentation for @TheBigDayIn next week. 
 Submitted CFP's to @DDDPerth  and @DDDMelb
 #100daysofcode Today's productivity makes up for all my sick days where I couldn't think to code

*** Thoughts***

**Link(s) to work**
https://sessionize.com/app/speaker
https://www.codecademy.com/courses/natural-language-processing/lessons/getting-started-with-nlp/exercises/topic-models
https://pretalx.com/pyconau2019/talk/review/LAAY3JHJHTRS7NCRVQGZMK3PKMQWTZXM


### Day 049: May 05 2019 - Sunday

**Today's Progress**: 
Started following @nnja Python Fundamentals Course on FrontEnd Masters
REPL
Variables
Numbers
Strings
Data types
Functions
Function arguments
Empty default Lists
Function scope
Lists
Tuples
Sets


*** Thoughts***

**Link(s) to work**
https://frontendmasters.com/courses/python
git.io/python3
https://pep8.org/


### Day 050: May 06 2019 - Monday

**Today's Progress**: 
Continued following @nnja Python Fundamentals Course on FrontEnd Masters
Dictionaries
Booleans
Comparisons
and, or & not


*** Thoughts***
Really great summary to get clear on all these concepts in the excercise - link below

**Link(s) to work**
https://www.learnpython.dev/02-introduction-to-python/080-advanced-datatypes/70-exercise/
https://www.learnpython.dev/02-introduction-to-python/090-boolean-logic/40-exercise/


### Day 051: May 07 2019 - Tuesday

**Today's Progress**: 
Made a twitterbot from Coderdojo, called it CoderDJBot. It's not automated and still need to play with some stuff, but the tutorial was super clear and I think this combined with the other stuff I learnt about twitter bots might create something interesting.
*** Thoughts***
CodeMasters offered me a free 3-Saturday Bootcamp for Python. Excited to attend that.

**Link(s) to work**
https://projects.raspberrypi.org/en/projects/getting-started-with-the-twitter-api

### Day 052: May 08 2019 - Wednesday

**Today's Progress**: 
Completed @NNJA's Python Fundamentals Course
Looping over lists
Looping over dictionaries
Control Flow
While and Control Statements
Python files and Modules
Debugging Strategies
Importing Modules and the main method
APIs
Requests - this is cool


*** Thoughts***
I had seen break before, but not Continue

**Link(s) to work**
https://www.learnpython.dev/02-introduction-to-python/110-control-statements-looping/40-break-continue/
https://www.learnpython.dev/02-introduction-to-python/175-running-code/30-the-main-method/
https://www.learnpython.dev/02-introduction-to-python/190-apis/00-the-requests-library/


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


### Day 0: MMM DD 2019 - Xday

**Today's Progress**: 

*** Thoughts***

**Link(s) to work**


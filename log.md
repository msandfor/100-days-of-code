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

*** Thoughts***

Not sure if this will be the cheap/freeish option I'm looking for, but it's worth exploring and understanding

**Link(s) to work**

https://docs.microsoft.com/en-au/learn/paths/create-serverless-applications/

### Day NN: Month Day 2019 - Day

**Today's Progress**: 


*** Thoughts***

**Link(s) to work**

### Day NN: Month Day 2019 - Day

**Today's Progress**: 


*** Thoughts***

**Link(s) to work**

### Day NN: Month Day 2019 - Day

**Today's Progress**: 


*** Thoughts***

**Link(s) to work**

### Day NN: Month Day 2019 - Day

**Today's Progress**: 


*** Thoughts***

**Link(s) to work**

### Day NN: Month Day 2019 - Day

**Today's Progress**: 


*** Thoughts***

**Link(s) to work**

### Day NN: Month Day 2019 - Day

**Today's Progress**: 


*** Thoughts***

**Link(s) to work**

### Day NN: Month Day 2019 - Day

**Today's Progress**: 


*** Thoughts***

**Link(s) to work**

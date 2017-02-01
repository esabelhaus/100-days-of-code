# 100 Days Of Code - Log

### Day 1: Jan 3, 2017

**Today's Progress**: Completed code and specs for pull request on drbd chef cookbook

**Thoughts:** I think I need to expand my overall knowledge of chefspecs. Functionally I can get by, but I would love to have a more comprehensive knowledge of the test suite so I can write better, or more complete unit tests on cookbooks

**Link to work:** [drbd](https://github.com/chef-cookbooks/drbd/pull/8)

### Day 2: Jan 4, 2017

**Today's Progress**: Updated gitlab-doge to have no more critical vulnerabilities

**Thoughts**: It is definitely liberating to remove version locking in some cases, but I need to get better about locking to a major versions and going through updates more often.

**Link(s) to work**: [gitlab-doge](https://github.com/esabelhaus/gitlab-doge)

### Day 3: Jan 5, 2017

**Today's Progress**: Updated gitlab-doge to have as little outdated dependencies as possible

**Thoughts**: Most everything works great, there are still a few tweaks needed to CSS and Angular after the updates

**Link(s) to work**: [gitlab-doge](https://github.com/esabelhaus/gitlab-doge)

### Day 4: Jan 6, 2017

**Today's Progress**: Began working on the pending specs, got it down to 11 from 14

**Thoughts**: Feature tests are being a PITA right now, need to stub some more request data, and get things tidied up

**Link(s) to work**: [gitlab-doge](https://github.com/esabelhaus/gitlab-doge)

### Day 5: Jan 7, 2017

**Today's Progress**: Moved the broken pending specs work to a feature branch, cleaned up master

**Thoughts**: This is going to be fun digging in on the specs, and trying to get coverage up :D

**Link(s) to work**: [gitlab-doge](https://github.com/esabelhaus/gitlab-doge)

### Day 5: Jan 7, 2017

**Today's Progress**: Started tinkering with the python NLTK and scrapy

**Thoughts**: I think I've got a decent grasp on the basic construct of a scraper in scrapy, and I get the basic gist of how to process text with NLTK. This is a good start, and once I get scrapy working with more advanced file processing, I'd like to get it pulling in files of a certain extension, and then do post processing on those files once they're pulled in locally, then run NLTK against them and figure out neat details about the files

**Link(s) to work**: [secret-octo-dubstep](https://github.com/esabelhaus/secret-octo-dubstep)

### Day 6: Jan 8, 2017

**Today's Progress**: Wrote a python script which posts a fortune from `fortune` to twitter daily

**Thoughts**: I like this concept, want to incorporate NLTK to ensure positive tweets are only flying out

**Link(s) to work**: [daily_fortune](https://github.com/esabelhaus/daily_fortune)

### Day 7: Jan 9, 2017

**Today's Progress**: debugged my cron from yesterday, found I was missing fortunes, and also limited the number of fortune cookies to pull from

**Thoughts**: tomorrow I will start writing an NLTK script to process all the fortune files into a keystore file of twitter ready quotes so there is no need for an app install other than python3 and python3-pip

**Link(s) to work**: [daily_fortune](https://github.com/esabelhaus/daily_fortune)

### Day 8: Jan 10, 2017

**Today's Progress**: worked through the stages of scraping, refactoring stages into main spider

**Thoughts**: Kinda cool grabbing the URL for over 340 files, did a wget on the list for fun, almost a quarter gig worth of PDFs :D

**Link(s) to work**: [secret-octo-dubstep](https://github.com/esabelhaus/secret-octo-dubstep)

### Day 9: Jan 11, 2017

**Today's Progress**: all 4 stages of scraping work now, could be more streamlined, but I believe I scraped all PDFs :D

**Thoughts**: 411 PDFs grabbed, 17000+ requests made, a lot of duplicate requests though... gotta clean that part up eventually

**Link(s) to work**: [secret-octo-dubstep](https://github.com/esabelhaus/secret-octo-dubstep)

### Day 10: Jan 12, 2017

**Today's Progress**: Doing some homework as my entry today. Taking a class at UMUC on game development using jMonkey. Modifying some boilerplate code and adding stuff to create a coin flipping game. should be done by tomorrow.

**Thoughts**: I REAAAAAALY want to refactor my professors code, but I'll resist the urge for now. If I knock things out quickly tomorrow, refactoring will happen, and the swing code will be cleaned up

**Link(s) to work**: [CMSC325](https://github.com/esabelhaus-homework/CMSC325)

### Day 11: Jan 13, 2017

**Today's Progress**: got the flipping gui sorted, but I need to modify the action listener to let the user know whether their guess is correct.

**Thoughts**: still want to refactor the code, but I got distracted by playing Destiny, so that happened. Need to designate a block of time for code, rather than gaming/coding at the same time.

**Link(s) to work**: [CMSC325](https://github.com/esabelhaus-homework/CMSC325)

### Day 12: Jan 14, 2017

**Today's Progress**: Almost have everything working with the gui, had to save the coin flip output to txt files

**Thoughts**: Data encapsulation in swing is a pain in the ass

**Link(s) to work**: [CMSC325](https://github.com/esabelhaus-homework/CoinFlipping)

### Day 13: Jan 15, 2017

**Today's Progress**: Ok, everything works, code is cleaned up, at some point I will try to refactor this to not need to save the output to a file, but it works :D

**Thoughts**: homework submitted, I think there ought to be a better encouragement from college faculty on pushing homework code to github/gitlab so that people can share and learn from one another.

**Link(s) to work**: [CMSC325](https://github.com/esabelhaus-homework/CoinFlipping)

### Day 14/15: Jan 16/17, 2017

**Today's Progress**: processed the text of the hundreds of PDFs I scraped using PyPDF2, output them to text, and then started working with NLTK to process them further

**Thoughts**: This is going to be neat. Everything is currently ham strung, but once I get it all working in some fashion, I will abstract it out, and make it a service of sorts possibly

**Link(s) to work**: [secret-octo-dubstep](https://github.com/esabelhaus/secret-octo-dubstep)

### Day 16: Jan 18, 2017

**Today's Progress**: getting some sentiment analysis strategies worked out, still work to do

**Thoughts**: This is going to be neat. Everything is currently ham strung, but once I get it all working in some fashion, I will abstract it out, and make it a service of sorts possibly

**Link(s) to work**: [secret-octo-dubstep](https://github.com/esabelhaus/secret-octo-dubstep)

### Day 17: Jan 19, 2017

**Today's Progress**: had a fun day with kernel panics today, they're no picnic... Besides that, got to work on some jmonkey game dev for class

**Thoughts**: Openstack + VirtualBox is a tricky dance apparently, nested virtualization is a pain in the butt. JMonkey is pretty neat I guess.

**Link(s) to work**: [SabelhausHwTwo](https://github.com/esabelhaus-homework/SabelhausCMSC325)

### Day 18: Jan 20, 2017

**Today's Progress**: Got my homework finished, today is a somber day

**Thoughts**: I need to focus less on politics, and more on how I can help those in need. #FuckTrump

**Link(s) to work**: [SabelhausHwTwo](https://github.com/esabelhaus-homework/SabelhausCMSC325)

### Day 19: Jan 21, 2017

**Today's Progress**: the text processing is still working, but slow going as it is doing an iterative comparison loop on each word. I've either got to paralellize it, or consider modifying my algorithm.

**Thoughts**: could go the recursive route here, or possibly hash the comparison words and use boolean comparison on the hash. A little more memory intensive, but it will rapidly increase the process as it would be only one iterative loop, rather than running an exponential route as I currently am

**Link(s) to work**: [secret-octo-dubstep](https://github.com/esabelhaus/secret-octo-dubstep)

### Day 20: Jan 22, 2017

**Today's Progress**: so, today was major progress. The last run through of this data set didn't even finish in a day. I redesigned the algorithm to process matching words to a hash value within a dictionary. I'll explain in the thoughs as to why I did this change :)

**Thoughts**: Using a nested loop, you're iteratively going over every item in one list, and for every item in the first list, it iterates over all items in the second list. Say I have two lists, each with 50,000 items. I am now iterating over 50,000 items, 50,000 times each. This is an exponential growth rate, and is non functional at scale.

The alternative approach I defined uses an iterative loop over the strings being classified, and it uses a dictionary or `dict()` data structure to compare items within the iterative loop. A dictionary object type provides a key value pair, and in this instance, I created a dictionary of words, paired to a boolean value of True `{'word': True}`. This allows me to loop over every string and verify if it exists within a `try: except:` block. This solution requires more memory, but significantly less time than it previously had.

**Link(s) to work**: [secret-octo-dubstep](https://github.com/esabelhaus/secret-octo-dubstep)

### Day 21: Jan 23, 2017

**Today's Progress**: Finally getting around to building my website. I had been working on using hamlJS before, decided to go with pug. I've set up my layout template with the top bar. Loves me some zurb foundation :D

**Thoughts**: I've got a few ideas of how I'd like to lay things out, maybe I can get a logo made on fiverr

**Link(s) to work**: [sabel.haus](https://github.com/esabelhaus/sabel.haus)

### Day 22: Jan 24, 2017

**Today's Progress**: I worked on homework for my comp sci class tonight, got a start by copying in the boiler plate code provided from my professor, tweaked a few things, created a font, tomorrow I'll redo things from the boiler plate to match my theme.

**Thoughts**: This class has been pretty straight forward so far, and a bit nicer than the computer graphics class I took last semester.

**Link(s) to work**: [sabel.haus](https://github.com/esabelhaus-homework/SabelhausCMSC325/tree/proj1)

### Day 23: Jan 25, 2017

**Today's Progress**: Static website content started, assets added.

**Thoughts**: still thinking about the layout of each page, and whether I'll hit up Fiverr

**Link(s) to work**: [sabel.haus.static](https://github.com/esabelhaus/sabel.haus.static)

### Day 24: Jan 26, 2017

**Today's Progress**: added content to index page, gotta consider the layout a little. Basic is fine for now though

**Thoughts**: still thinking about the layout of each page, and I think I'll hit up Fiverr

**Link(s) to work**: [sabel.haus.static](https://github.com/esabelhaus/sabel.haus.static)

### Day 25: Jan 27, 2017

**Today's Progress**: Worked on my homework some more, nearly finished laying out objects in the scene

**Thoughts**: jmonkey is neat, but documentation is weird to get at unless you've got an account to their hub

**Link(s) to work**: [SabelhausHwTwo](https://github.com/esabelhaus-homework/SabelhausCMSC325)

### Day 26: Jan 28, 2017

**Today's Progress**: Homework finished, might not be my best work, gonna do better on the next assignment

**Thoughts**: spending two days on a project that could have taken 3 was a bad idea, gotta focus on school more

**Link(s) to work**: [SabelhausHwTwo](https://github.com/esabelhaus-homework/SabelhausCMSC325)

### Day 27/28: Jan 28/29, 2017

**Today's Progress**: worked on some python code for processing tweets, lots of trial and error

**Thoughts**: APIs are neat

**Link(s) to work**: [socially-distorted](https://github.com/esabelhaus/socially-distorted)

### Day 29: Jan 30, 2017

**Today's Progress**: got the stream being processed asynchronously as it should be, still need to tweak processing

**Thoughts**: APIs are neat

**Link(s) to work**: [socially-distorted](https://github.com/esabelhaus/socially-distorted)

### Day 30: Jan 31, 2017

**Today's Progress**: I've now processed over 88000 tweets and counting, gonna let it run over night

**Thoughts**: So, I stumbled upon the fact that MAGA was being tweeted heavily in association with hateful connotation, and I wanted to confirm it. Once I've gathered a couple hundred thousand tweets, I will use the mongo aggregation pipelines to slice and dice these tweets I've been storing. I also intend to publish my findings, as well as possibly make the scripts a little more dynamic. Currently I have a broad scope just filtering tweets containing the MAGA hashtag, which is a broad net to cast. But I intend to do many different data studies on these tweets, so it's necessary for now.

**Link(s) to work**: [socially-distorted](https://github.com/esabelhaus/socially-distorted)


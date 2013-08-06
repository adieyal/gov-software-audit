# Software Audit of SA Government Departments

How much does our government spend on proprietary software? I haven't found an audit anywhere so I decided to conduct one myself. 

## Why do I care; Why should you?

My estimate is that we are spending over R10 billion of public funds annually on proprietary software, the large majority of it to overseas companies through their local partners. That's essentially a pot of money that leaks out of the South African economy. Why not use open source software instead supported by local companies? There are lots of good reasons to using open source software most of which I won't mention but the ones I think are important for government are:

* No vendor lock-in - software is often like a monopoly, once you've bought into it, the cost of moving to another system can be prohibitively expensive. Knowing this, vendors can maintain high prices with little fear of competition
* Software quality - bugs are quick to fix - anyone can clone a repository, make the fix and send a pull request. The fix benefits everyone and doesn't require a long version update cycle.
* Reduction of redundancy - Department A needs some software, Department B needs the same software - why do they both have to purchase their own software?
* You want a feature? - You don't need to wait for the next version of the software and hope that your must-have feature is included.
* Free? - nope - that's not at all true and should not at all be a reason to choose open source software.

Apart from the above - my biggest argument for moving government to open source systems is economic. An additional 10 billion rand annually injected into the local software development industry will create a bundle of jobs and stimulate economic activity which is being lost to software imports.

## Arguments against going open source

* *You'll need to re-train all of government* - hey, you have R10 billion to spend - spend some on training
* *Open source software sucks* - you think so? Spend R10 billion tuning it to be just so
* *There is no accountability with open source projects - poppycock! Open source software is managed in the same way as any other software development.
* *You can never move government wholesale* - one step in front of the other
* *There is no open source equivalent to X package* - let's talk - are you sure you looked carefully enough?
* *What about support* - Pay for it - I'm sure there are tons of companies willing to provide it.
* * Open source is difficult to use - that's a general statement - I don't find oogle chrome to be difficult to use at all - Internet Explorer has until recently been lagging very far behind all the other open source browsers. Some open source software might have poor usability for non-technical users - this can always be improved with sufficient developer spend. 
* *It will be difficult to move to open source software in government because proprietary companies using unscrupulous business practices to influence procurements - that's why we need a government policy that prefers open source software tp proprietary software. A motivating statement would need to be made to argue why a closed source system should be used instead.
* *Proprietary software offer out-of-the-box solutions - so what? That is not necessarily true, but even if it was - we should plan for the long-term by producing software that promotes transparency and local economic development. 
* *Open source software is costly to customise - possibly true, but consider the long-term cost of ownership of the two alternatives. Licensing fees are paid annually, most customisation of open source software takes place initially. Thereafter you have a much cheaper maintenance phase. It is quite likely that any development cost can be amortised over a few years. Of course, there is no guarantee that closed-source software doesn't need to be customised. SAP is the biggest culprit. One often hears of multi-million rand SAP implementations. 


## What this project is not

* This project isn't and should not become an exercise in Microsoft bashing.
* Change is slow and difficult - bashing government (despite the occasional frustration) is neither productive nor desirable
* This project aims to be naively idealistic - it may not work, in fact the odds are against it - so what? Let's do it anyway. At the very least we may raise awareness of the issues, help society take one more step on the right direction. Also - we, as South Africans need to take ownership of our world. The only way to do that is to stand up for what we believe in. Finally - I believe in freedom of information - government holds data that we have a right to have. This right is entrenched in the bill of rights and we need to assert that right. This is an opportunity to do that and hopefully learn something in the process.


## I geddit - what's next?

A strong quantitative economic argument for why open source software is good is the only way to convince decision makers. To achieve this, I am gathering information by submitting [PAIA](http://www.sahrc.org.za/home/index.php?ipkContentID=25&ipkMenuID=45) requests to government departments requesting information on software licences. What software are they using? How many licences do they have? How much are they paying?

PAIA is tedious but defines a process through which members of the public can access information held by government (with exceptions). A PAIA request costs R35 and can take anywhere between 30 days - 1 million years to process. 

Once I receive the data, I enter it into the csv file in this repository ready for analysis. 

## Sounds like an awesome idea - how can I help?

I am targeting government at national, regional and local level. It's great that we have PAIA but it isn't as easy as sending an email. You often have to send a couple. Sometimes you deal with public servants who like to test your resolve. Also, in practice, government departments have no real obligation to give you the data. In principle you can take them to court but in practice that's not really going to happen. 

That said, I can't do it alone but I do feel that it is a worthwhile goal. If nothing else, a database of software used by government may be useful outside of this project. Also - learning about PAIA is quite useful - just because information is not available on a government website doesn't mean that you can get access to it. It's a useful tool in your toolbox if you need to research a particular topic.

If you're willing to help - contact me, clone the repository and get cracking. Send pull requests and I'll merge your additions into the database (and credit you appropriately).

Here are the steps:

1. Clone the repository
2. Have a look at the PAIA requests csv file.
3. Identify a department that hasn't yet been claimed (at can be national, regional or local)
4. Add your department to the file.
5. Create a PAIA request - see the template file for an example 
6. Look on the department website. You should find a link to their PAIA manual. In it you should find the contact details of the Information Officer or their deputy. 
7. Send them the request and then negotiate the data. You may be asked to pay R35 for the request but not always. Here are some hints that may be useful:
	* Sometimes the email bounces - find another email address. People change jobs all the time while the PAIA manual is seldom updated.
	* In theory, they have 30 days to respond - in practice they may completely ignore your request. There's not too much that can be done unfortunately except try to find someone else to contact.
	* You may be asked what you want the data for. They are obliged to furnish you with the data regardless of your reasons and you're not required to answer. In this case, I don't think that it is a problem.
	* I have had one case where they have refused to give me costs - I'm not sure how to deal with this yet.
8. When communicating with your PAIA, be sure to be polite. Since they may ignore your request without real repercussions, it's best to be friendly. You're much more likely to get a response.
9. Once you get your data, fill in the packages.csv file.
10. You're done - go back to step 1.

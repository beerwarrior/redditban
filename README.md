# redditban
Reddit Ban

Update #1: Thanks to /u/robojumper and /u/temporarymctempton for reading this and posting bits to Buttcoin, much appreciated. I sent a query to the admins about 8 hours ago but no response yet. To answer some questions:

> My guess is that he used his main account to post in subs where his bots were banned or vice versa.

I have only ever created the three accounts on Reddit: Barca, then the Buzzword and Zen Bot accts, both of which only read and post to /r/Buttcoin and /r/testingground4bots when testing, never elsewhere. I only use the Barca account for personal posts, 99% of which are on Buttcoin. I sub to/read some of the cryptocurrency subs but I try hard to never post on them.

The bots' User-Agent: ID has the Barca account info as does every post. I went to great lengths to register all three accounts legitimately, wrote the bots to all Reddit standards, got permission from the Buttcoin mods for both bots (which they put on an approved list.) Never used Tor nor tried to mask who I am.

I check my inbox at least once a day, and did not see any attempt to contact me before the ban.  In the BarcaloungerJockey mailbox, the last message before the ban was:

username mention Cringe to the max!
from ZenMasterBot via /r/Buttcoin sent 13 hours ago

Free Butterin
But first[...]

> Did he run BigLambdabot? I could see him crying to the admins.

This could be part of the issue. I just checked and that account is banned. I did not create that account. The owner sent me the password for it in a PM a few months ago and asked if I wanted to do something with it. As an experiement to see how fast I could write a working bot from scratch (58 minutes it turned out, yay me) I put one together and ran a couple tests on /r/testingground4bots. It never ran on /r/Buttcoin.

After some thought I decided that biglambda, whom I quite like and have had some friendly discussions with, might consider it harassment and that it was unethical to target a bot at a single user, so I deleted the code and API reg, and removed the password from my browser. Haven't even thought about it until I read the post above.

This could certainly be what the problem was and I'm kicking myself for even logging into it, but hindsight is 20/10. I hope this isn't it as I thought biglambda had a sense of humor about that account, and I've always thought he might be the actual owner. I don't remember anything posted from that account that crossed the line into something bannable. It was just short and silly.

> Can you check if this applies to ZenMasterBot and BuzzwordBingoBot as well? Maybe one of them was banned and your main account triggered the suspension?

Looking at /u/ZenMasterBot, which was also banned, there was an issue about a month ago when /u/jstolfi had gilded the bot account with tippr, which sent it a message. ZenBot is set up to send a random, short reply to anything that comes to the inbox, and the two bots got into a back-n-forth reply loop. Fortunately I caught this fairly quickly and immediately halted the both and added code to prevent auto-replies going out to known bots, Reddit admin/staff, etc. It hasn't been an issue since and figured the admins would contact me if it was.

The last user message to Zenny was:

subject Fj
from Dunedune sent 3 days ago

Test

to Dunedune sent 3 days ago

beep

"If you spoke to me mano a mandible this way, I would break your arm."

This quote taken from Vinay Gupta's rants might also be the issue if a silly reply from a bot can be seen as a threat of physical violence, but I naively thought the "break your arm" was a known joke meme in Buttcoin. Not sure why that user would have messaged the bot directly. He appears to be an /r/btc regular and has defended buttcoins but I've never interacted with him directly and he seems a reasonable sort, mainly.

I'm going through the databases now and removing any posts that might come across as threats. There's also the ZenBot rants that might have set someone off and been reported, but given how absurd they are and mainly randomly based off others' posts (who have not been banned) I'm not sure why they would be an issue. I'm turning those off for now to be safe.

Apologies for the long message but I'm trying to do an honest, thorough triage. Happy to answer any other questions, etc. I obviously made some mistake but it was unintentional and I hope I get a chance to address and rectify it.

ZenBot source is available/free should someone else want to take it up. If I can't sort out the account bans I'm not going to bother. I try to be a non-toxic, rule-abiding guy on the Interwebz, but this isn't the first time I've been caught up in bans despite that and I've found it best to just walk away.

Thanks to everyone who posted humorous replies, many good laughs there! Cheers!

----

Original message:

My account was permanently banned. I have absolutely no idea why. The message I received says:

"Your account has been permanently suspended for using alternate accounts to evade a subreddit ban.
You are no longer welcome to use the site."

The same happened to the /u/ZenMasterBot acct, same message. No warning, no temporary ban, no contact in either account from other users or admins. The BuzzwordBot account seems untouched. It was also running on a Raspberry Pi but nobody had been using it. I have the three accounts, two of them for the bots, both registered with my main acct listed in the API as well as with every single post so I could be contacted if necessary.

I have written an appeal asking why, esp. since I have never been banned on any account or sub before, so the "alternate accounts" thing makes no sense to me (I am naive about Reddit, admittedly.) I rarely post outside of r/Buttcoin so I don't know what sub I was supposedly banned from and evading.

I don't know if others contacting the admins can help or just make things worse? I don't see why I'd be banned, as I follow the rules, don't get into arguments, etc. Anyone can check my post history to confirm.

I'm waiting for if/when I get a reply on the appeal. I'll check the thread posted on /r/Buttcoin periodically for feedback & advice. It's a shame this mistake has happened and hopefully I can get my account/ZenBot restored but Reddit's not a super-high priority TBH.

Thanks for all the kinds words and support. Cheers!

P.S. I won't be creating another account, using Tor, etc. to try to evade the ban. I'd rather work it out with the admins and it's not my thing to bypass rules.

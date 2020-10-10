
# frdcsa backup
## overview
* there's about 20TB of data to backup
* it should only be needed in rare situations to transfer it back in full
* There should be a ssh into the box
aindilis and koo both has 5Mbps uplink. That translates to about 50GB/day max.
### sneakernet to get it over the ocean.
ok, best with old-ish HDDs, so that we don't have to pay customs, and we don't have to give up possible warranty repairs.
How safe is shipping hdds, for the data?

# alternatives to irc
## gitter
"threads" are anonymous chatrooms spawned from a message in a channel, and can't be nested. It's not like, for example, reddit.
## discord
no reddit-style threads, but you can easily create a room, and everyone is instantly part of it
## matrix
>riot.im (matrix) are very frustrating because (AFAICT) you cannot share permissions between channels. In general it’s just not as nice to use as a discord server if you have more than one or two channels, which means you’re more likely to put all conversations in one or a few channels which isn’t ideal. In discord can have many channels in a server and if you grant someone permissions in the server, then it can apply to any number of the channels. In matrix, again AFAIK, you need to add permissions to each channel separately for a user.
>Matrix is definitely better than IRC, but in my opinion it’s still inferior to discord, not due to the quality of, or number of features in, the client, but from a conceptual standpoint. I understand why matrix did their design that way, and it may be the best open standard option out there, but there are a lot of benefits to the way discord organizes its concepts.


## slack
>Slack and Discord have nearly identical user interfaces for text communication.
>Slack's free plan, on the other hand, is more limited. It allows for 10 integrations with third-party services, up to 10,000 messages stored in the history




# discord-emacs/irc
## option 1
* http://www.aliquote.org/post/discord-bitlbee/
## option 2
So, given that we would all move to discord for serious discussions, the goal of an irc relay would be to ease the entry for newcomers and old lurkers. I would propose to create a bridge bot that would:
* relay all discord messages into irc, where they would be printed possibly prefixed by discord channel name. 
* relay back messages into "#general" or somesuch.






# mealplanner
## resources

### data

* http://p.ip.fi/7hEg

### engines

* https://github.com/koo5/calorie_constraints
* https://pastebin.com/raw/Su176JJ9
* https://pastebin.com/raw/tw7i57Q6 
* https://github.com/aindilis/gourmet-formalog
* https://gist.github.com/Anniepoo/bd24803d14181627bb8a482b5a3d8768

## notes
```
<koo6> so actually CLP still bothers me a lot. clpr/q doesn't have anything like labelling... maybe i figured out a workaround for that and forgot it again...  and there's the bugs. Then there's clpfd, which, in it's probably greatest and maybe bug-free version is called clpz and has an implentation in rust ... which is all great, but .. 
<koo6> it's integers, and i haven't found a way to simulate quotients or anything like that ... it'd rather stop solving completely
<stoopkid> That’s all true wrt the CLP issues, main reason i bring it up is for comparison w/ something like Mathematica
<koo6> something else i looked into was solving with limits, ie, just specify the ranges that your inputs are in, and hope to obtain the ranges that your outputs must be in
<koo6> needless to say...clpq/r will choke on any form of such equations, best bet is to just express those ranges "naturally" as clp constraints, and maybe then try to do something silly like try to do fake labelling manually
<koo6> i'm just tired of clpz/f/d/f/q/etc
<stoopkid> koo6: yea swi-prolog clp is kind of a mess, but i mainly bring it up just cause in theory a Mathematica-like system isn’t really doing anything conceptually different, and neither is Coq’s auto-proving
```



# sensor-net
## hw
* https://diyprojects.io/esp8266-deep-sleep-mode-test-wake-pir-motion-detector/
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6767279/
* https://www.amazon.com/SMAKN-Microwave-10-525GHz-Doppler-Detector/dp/B00FFW4AZ4
* https://biomedpharmajournal.org/vol12no3/a-novel-approach-for-non-contact-heart-rate-measurement/
* apple watch/mi band etc

## sw
* https://corescholar.libraries.wright.edu/cgi/viewcontent.cgi?article=1334&context=knoesis
* https://dtai.cs.kuleuven.be/problog/
* https://arxiv.org/abs/1207.3270
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3979570/
* https://github.com/nkatzz/ILED
* http://cer.iit.demokritos.gr/RTEC/demo.html
* https://users.iit.demokritos.gr/~a.artikis/publications/artikis-TKDE14.pdf
* https://www.researchgate.net/profile/Amit_Sheth/publication/232652895_Situation_awareness_via_abductive_reasoning_from_Semantic_Sensor_data_A_preliminary_report/links/0fcfd50a8fd2ada87a000000/Situation-awareness-via-abductive-reasoning-from-Semantic-Sensor-data-A-preliminary-report.pdf?origin=publication_detail
* https://www.researchgate.net/publication/281234978_RDF_Stream_processing_Let%27s_react
* https://pdfs.semanticscholar.org/5e00/70c4ef3506b945c12e49abc06ab7ab7b301a.pdf




# nextgen MAS's
* https://pdfs.semanticscholar.org/5049/ed95b79c10eb536f40a893ed537fd84e652c.pdf
* https://www.youtube.com/watch?v=M8-WFTjZoA0&ab_channel=TL%3BDR%2F%2FJavaScriptcodecastsforworkingdevs
* http://soft.vub.ac.be/amop/crime/factspaces
* https://elixir-lang.org/
* https://notamonadtutorial.com/lasp-a-little-further-down-the-erlang-rabbithole-febba29c8d0c





# semantic desktop

https://frdcsa.org/~andrewdo/software/domains.lisp
https://sourceforge.net/projects/conversio/



# libs / inputs / outputs / cca / graph search
* https://www.commonwl.org/user_guide/
* https://sourceforge.net/projects/conversio/
* https://web.archive.org/web/20040930065210/http://libs.sourceforge.net/user/welcome.php






# DC30-Badge-Challenge-Writeup

Table of Contents
=================
* [Intro](#intro)
* [Challenge Part 1: Gathering Notes](#1)
* [Challenge Part 2: Calling YИИEႱ](#2)
* [Challenge Part 2A: Alice](#2A)
* [Challenge Part 2B: Bob](#2B)
* [Challenge Part 2C: Carol](#2C)
* [Challenge Part 2D: Dan](#2D)
* [Challenge Part 2E: Eve](#2E)
* [Challenge Part 2F: Trevor](#2F)
* [Challenge Part 3: The Final Thread](#3)
* [Afterthoughts](#after)

<br/><br/>
<a name="intro"></a>
Intro
===
Hello there!  I'm Pete - aka Kybr - and this is my writeup for the DEF CON 30 badge challenge.  

This year's challenge was heavily focused on music and hacker pop culture, which I feel made it more widely accessible than some previous badge challenges.  We had a huge crew of hackers in person and on Discord working at the badge from the moment they started handing them out on Thursday morning all the way through Sunday afternoon, when we finally finished the last challenge just four hours before DEF CON ended.  Big thanks go out to Mike and crew at MKFactor for the truly unique and beautiful badge, and also for the many hours of ~~pain and suffering~~ fun!

We divided the challenge into 3 parts: gathering notes, gathering friends, and the final thread. You can look over our documentation here:  
https://dc30badge.fandom.com/wiki/DC30Badge_Wiki  
Our notes are available here:  
https://docs.google.com/spreadsheets/d/1MdZgv_O3ogv4JDS07iobh5rhoDYXCsF7QVExuG08txA/edit#gid=0  
Finally, if you enjoy this sort of thing, I encourage you to join us in Discord for next year's challenge here:  
https://discord.com/channels/867438418212683796/867438418212683799  
Thanks for reading!
  
<br/><br/>
<a name="1"></a>
Challenge Part 1: Gathering Notes
===
The first challenge can be found by selecting the "Challenge" option on the main menu.  We are presented the following text:  
`Collect the Measusres, Break the Silence, Continue the Journey`  
<sup>NOTE: The misspelling of the word Measures was accidental and not relevant to the challenges.  </sup>  
![Challenge One](/assets/c12.jpg)  
This is a reference to the musical measures found on the faceplate of the badge itself.  There are 9 different colored badge types at DEF CON, and each type had something different on the faceplate.  Gathering photos of all 9, we find that 8 have music and 1 (the grey CFP badge) has letters spelling `POWWYGBR`  
That's our key to ordering the other 8 badges by color: Purple, Orange, White, White, Yellow, Green, Blue, Red.  
![Badge faceplates](/assets/fronts2.jpg)  
Once in this order, the measures form the beginning of the song "Peer Gynt Suite No.1".  Playing these notes on the badge in "Play" mode unlocks Challenge Part 2:  
`ANSWER: in Play mode, play the following at any speed - GEDCDE GEDCDE GEGAEA GEDC GEDCDE GEDCDEDE GEGAEA B G# F# E`  


https://user-images.githubusercontent.com/22137377/185831822-232a2285-28f1-4f51-860c-354b4d5b5660.mp4




<br/><br/>
<a name="2"></a>
Challenge Part 2: Calling YИИEႱ
===
After playing Peer Gynt Suite, the Challenge option on the badge now shows us the message `Call YИИEႱ` and our keyboard now plays dial tones instead of notes.  "YИИEႱ" is a reference to the song "867-5309 / Jenny" by Tommy Tutone, and since Jenny is written backwards, we're meant to dial her number backwards: 903-5768.  Dialing this number on the badge itself does nothing, there were physical telephones in the Contests area of the convention that needed to be used for the remainder of these challenges.  
![The Contest Area Phones](/assets/contestarea.jpg)  
Calling 903-5768 on these phones gave us a series of 5 clues about 5 missing friends:  
`Alice - Was last seen shopping for a new water pipe`  
`Bob - Little Bobby turn tables, dropped himself`  
`Carol - Went to her favorite arcade`  
`Dan - Greenwich manhattan`  
`Eve - Cerebrum data link`  
The message also told us that for the remainder of these challenges, each answer will be a URL starting at `https://defcon.org/badge/30/`
So we submit our answers by adding it to the end of that URL.  If we're right we find a new webpage with the next challenge, and if we're wrong we just get a standard 404 "not found" error.  We have 5 threads to follow now, one for each of the 5 missing friends.

<br/><br/>
<a name="2A"></a>
Challenge Part 2A: Alice
===
1) YИИEႱ's message said "Alice was last seen shopping for a new water pipe"  
This was our easiest question which introduced us to the challenge format.  "Water pipe" here is a simple reference to a hookah, and we found our next challenge by adding "hookah" to the given URL.  
`ANSWER: https://defcon.org/badge/30/hookah/`

2) Solid blue screen  
The hookah URL presents us with a solid blue screen, with nothing interesting in the code or website traffic.  Between the name "Alice", the reference to a hookah, and the color blue, the question is a reference to Alice in Wonderland where Alice meets a caterpillar smoking a hookah.  We add "caterpillar" to the end of the URL to find our next challenge.  
`ANSWER: https://defcon.org/badge/30/hookah/caterpillar`

3) Image of the caterpillar  
We are given a picture of the hookah-smoking-caterpillar from Alice in Wonderland. Upon downloading the image and inspecting it's metadata, we find that the "OwnerName" attribute has a curious value of `9dFDfOi_-ss`.  
![Metadata](/assets/caterpillardata.png)  
This is a video reference for a YouTube URL, so we browse to https://www.youtube.com/watch?v=9dFDfOi_-ss which gives us a video of our smoking caterpillar reciting the poem "How Doth the Little Crocodile"  
`ANSWER: https://defcon.org/badge/30/hookah/caterpillar/howdoththelittlecrocodile`

4) Poetry  
We are given the text `When is a measure not for science?  double the common form.`  
This is a reference to the Common Measure, a poetic metre consisting of four lines that alternates between iambic tetrameter (four metrical feet per line) and iambic trimeter (three metrical feet per line).  The poem "How Doth the Little Crocodile" is written in this meter.  The poem consists of 8 lines, and counting the feet per line gives us 4,3,4,3,4,3,4,3, so doubling that form gives us 8,6,8,6,8,6,8,6.  Since 86868686 was not a valid URL, we called that number on the contest phones and were given the unlock code for Alice (who now appears under the "Friends" menu option on the badge!)  
`FINAL ANSWER: Call the number "86868686" on the contest phones to find Alice.`   
![Alice](/assets/alice.jpg)  

<br/><br/>
<a name="2B"></a>
Challenge Part 2B: Bob
===
1) YИИEႱ's message said "Little Bobby turntables, dropped himself"  
This is a reference to the XKCD comic "Exploits of a Mom" (https://xkcd.com/327/) in which a child is given a name containing destructive SQL injection logic.  
`ANSWER: https://defcon.org/badge/30/logic`  

2) Image of the rapper "Logic"  
The rapper Logic famously named his hit single "1-800-273-8255" after the phone number for the National Suicide Prevention Lifeline (NSPL).    https://en.wikipedia.org/wiki/1-800-273-8255_(song)  
`ANSWER: https://defcon.org/badge/30/logic/18002738255`  

3) About the Lifeline  
The previous link takes us to a page about The Suicide & Crisis Lifeline, which, starting in 2020, can now be reached quickly by dialing 988 (much like 911).  
https://en.wikipedia.org/wiki/988_Suicide_%26_Crisis_Lifeline  
(side note: kudos to the challenge authors for calling attention to this important work and information, however uncomfortable it may be to discuss)  
`ANSWER: https://defcon.org/badge/30/logic/18002738255/988`  

4) Geocache over Eight  
We are shown the symbol for Geocaching over the number 8.  Taking our answer from the previous challenge, 988, and dividing by 8 gives us 123.  The geocaching symbol is intended as a hint that there is a geocache hidden in room 123.  Upon a search of room 123, a geocaching symbol with a QR code was found.  
![The geocache](/assets/gc2.jpg)  
The QR code gives us the text "By the Numbers".  Keeping with the theme of the last two answers, we find the URL https://988lifeline.org/by-the-numbers/ which tells us that the Lifeline has received 23,044,100 calls (at the time of this writing).  
![That is a lot of calls](/assets/numbers.png)  
`ANSWER: https://defcon.org/badge/30/logic/18002738255/988/23044100`  

5) Dots and Slashes  
The page gives us the text `./ - ../` and nothing else.  In a UNIX directory structure, "./" refers to your current directory and "../" refers to your parent directory.  In the case of our current challenge URL https://defcon.org/badge/30/logic/18002738255/988/23044100 (which is itself a reference to a directory structure), the "./" refers to 23044100 and "../" refers to 988.  Taking 23044100 minus 988 gives us 23043112.  
`FINAL ANSWER: Call the number "23043112" on the contest phones to find Bob.`  
![Bob](/assets/bob.jpg)  

<br/><br/>
<a name="2C"></a>
Challenge Part 2C: Carol
===
1) YИИEႱ's message said Carol "Went to her favorite arcade"  
This is a reference to the show "Mr. Robot" in which the character Carol's favorite arcade is called "Fun Society".  Eventually the main characters of the series form a hacktivist group called "fsociety" based on this name.  
`ANSWER: https://defcon.org/badge/30/fsociety`  

2) Beastie Boys  
We are given an image of the Beastie Boys from their album "No Sleep Till Kawasaki".  Keeping with the theme of Mr. Robot, inside the Fun Society arcade there is an arcade game called "Intergalactic Planetary", which shares it's name with the lyrics of the Beastie Boys' famous song "Intergalactic".  
`ANSWER: https://defcon.org/badge/30/fsociety/intergalactic`  

3) Intergalactic  
We are given an audio file which plays "Night on Bald Mountain" followed by "Intergalactic".  If we download and inspect the audio file, we can see there is a comment in the metadata reading "v=N5aAu8CCQY0".  
![MOAR metadata](/assets/intergalactic.png)  
Once again this a YouTube video URL, which leads us to a talk on phone phreaking from DEF CON 7.  
https://www.youtube.com/watch?v=N5aAu8CCQY0&ab_channel=DEFCONConference  
Searching the DEF CON archives (https://defcon.org/html/defcon-7/defcon-7-pre.html#SpeakingSchedule) shows us that this talk was given on Friday, July 9, 1999 at 4:00 PM PST, which is 11:00 PM in GMT.  Converting this to Epoch time gives us 931561200.  
`FINAL ANSWER: Call the number 931561200 on the contest phones to find Carol.`  
![Carol](/assets/carol.jpg)  

<br/><br/>
<a name="2D"></a>
Challenge Part 2D: Dan
===
1) YИИEႱ's message said "Greenwich, Manhattan"  
Every DC30 badge has at least four built-in sounds available in "Play" mode: Piano, Violin, Clarinet, and Dog.  Several badge types also have a fifth default sound option: for example, the Vendor (purple) badge has a "Cha-Ching" option that makes a cash register sound, the Goon (red) badge has a "Make a hole!" sound, etc.  The Village (orange) badge has the following fifth sound option called "Dial" (linked below)    
This is an 8 digit DTMF tone (https://en.m.wikipedia.org/wiki/Dual-tone_multi-frequency_signaling) that decodes to "01906967", which turned out to be Dan's first URL.  We believe "Greenwich, Manhattan" is a clue for Dan's second challenge.  
`ANSWER: https://defcon.org/badge/30/01906967`  


https://user-images.githubusercontent.com/22137377/185828716-b06e2f7d-e923-4945-88a4-6319f25836ac.mp4



2) Unchained Melody  
We are given an audio file which plays "Unchained Melody".  This song is perhaps most famously featured in the "pottery" scene of the movie Ghost (1990).  The movie title Ghost, coupled with the earlier hint "Greenwich, Manhattan" (the setting for Ghostbusters), and the fact that we are looking for Dan, leads us to Dan Aykroyd - the actor who played Ray Stantz in the 1984 Ghostbusters movie.  
`ANSWER: https://defcon.org/badge/30/01906967/aykroyd`

3) Ghostbusters  
We are given an image of the 1984 Ghostbusters.  Who ya gonna call?  Searching for the Ghostbusters' phone number gives us their current phone number 212-897-1964.  
https://www.facebook.com/Ghostbusters/photos/theyre-ready-to-answer-your-call-dial-212-897-1964-to-get-a-very-special-ghostbu/722572714463399  
`FINAL ANSWER: Call the number "2128971964" on the contest phones to find Dan.`  
![Dan](/assets/dan.jpg)  

<br/><br/>
<a name="2E"></a>
Challenge Part 2E: Eve
===
1) YИИEႱ's message said "Cerebrum data link"  
This is a simple riddle referencing the synapses of the brain.  
`ANSWER: https://defcon.org/badge/30/synapse`  

2) Image of a satellite  
We are given an image of a satellite in orbit.  Upon downloading and inspecting the image, we find that there is a hidden PCAP (network traffic capture file) embedded in the image file, extracting and studying the PCAP shows a single ping to an IP address 10.48.29.234  
![The ping in question](/assets/pcap.png)  
`ANSWER: https://defcon.org/badge/30/synapse/10.48.29.234`  

3) NURV  
You can see the acronym NURV on the whiteboard in the background.  This is a reference to the 2001 movie AntiTrust, where NURV is the name of an evil corporation.  Both previous answers were also references to the movie AntiTrust, where "synapse" is the name of the evil network and "10.48.29.234" is the IP address of one of their sattelites.  
http://mike.passwall.com/uselesstrivia/antitrust.html  
`ANSWER: https://defcon.org/badge/30/synapse/10.48.29.234/nurv`  

4) 1 or 0  
We're given the text `You're eiTher a one or a zero. Alive or dea9.`  "T9" clearly stands out from the given text - and T9 is a text technology on mobile phones which stands for "Text on 9 keys"  
https://en.wikipedia.org/wiki/T9_(predictive_text)  
Keeping with the AntiTrust theme, typing out the word "antitrust" in T9 gives us "268487878"  
`FINAL ANSWER: Call the number "268487878" on the contest phones to find Eve.`  
![Eve](/assets/eve.jpg)  

<br/><br/>
<a name="2F"></a>
Challenge Part 2F: Trevor  
===
1) #Trevorforget  
Upon close inspection of the "Challenge" screen after completing Step 1, we notice that there is a single pixel in the upper-right corner of the screen which is blinking slowly.  Treating the blinks as morse code gives us `- .-. . ...- --- .-. ... -.. .- - .` which decodes to `TREVORSDATE`.  Trevor was a beloved member of the hacker community who was tragically taken from us on 9/23/2017.  
https://www.youtube.com/watch?v=oOXcol_fFGQ&ab_channel=SAINTCON  
`FINAL ANSWER: Call the number "923-2017" on the contest phones to find Trevor.`  
![Trevor](/assets/trevor.jpg)  

<br/><br/>
<a name="3"></a>
Challenge Part 3: The Final Thread  
===
1) After unlocking all friends, calling YИИEႱ (9035786) again now gives us a new message: `slash here we go again rot13`  
Taking the ROT13 (aka Caesar cipher) of the string "herewegoagain" gives us "urerjrtbntnva"  
`ANSWER: https://defcon.org/badge/30/urerjrtbntnva`  

2) We are given the text "(Red-Yellow)(Blue-White)"  
There are small numbers hidden on the faceplates of several of the badges that cannot be seen unless the faceplate is removed.  Taking these numbers from their respective badges gives us red = 3205272, yellow = 3203902, blue = 3205274, and white = 3203901.  From there it's math: (3205272-3203902)(3205274-3203901) = (1370)(1373) = 1881010.  
![Tiny Numbers](/assets/smallnumbers2.jpg)  
NOTE: the URL https://defcon.org/badge/30/urerjrtbntnva/1881010 gives us a 403 instad of the normal 404 "not found" page, which tells us that we're correct but we're not looking for a URL for this puzzle.  Instead, we're meant to call the number 188-1010 to get our next clue.  
`ANSWER: Call the number "1881010" on the contest phones to get our next challenge`  

3) Calling "1881010" gives us the message `Redundancy is key in footwear`  
This is a reference to another famous hacker movie "Sneakers" (1992).  The "Key" refers to the movie's music, nearly all of which is written in the key of E Minor.  
`ANSWER: https://defcon.org/badge/30/urerjrtbntnva/eminor`  

4) We are given the text "DC30 - DC1"  
This is a time-based math puzzle asking us for the amount of time passed between DEF CON 30 and DEF CON 1.  DEF CON 1 was held in June of 1993, and DEF CON 30 in August 2022.  Ignoring the specific day of the month of the conventions, the time that passed between DC1 and DC30 (July 1993 through June 2022) is 10,625 days, or 918,000,000 seconds (918000000 in Epoch time).  
`ANSWER: https://defcon.org/badge/30/urerjrtbntnva/eminor/918000000`  

5) We are given a picture from the movie "The Little Rascals"  
A reference within a reference, "what's the number to 911?" is a reference to an episode of "The IT Crowd" where they change the emergency service number from 999 to 01189998819991197253  
https://www.youtube.com/watch?v=HWc3WY3fuZU&ab_channel=TheITCrowd  
Dialing this number on the contest area phones led to a recording of the song "The Final Countdown"  
`ANSWER: https://defcon.org/badge/30/urerjrtbntnva/eminor/918000000/thefinalcountdown`  

6) The cipher  
We are given a long list of sets of numbers, each line consisting of 4 numbers separated by hyphens.  This is a book cipher, where the four numbers in each line represent page number, paragraph number, line number, and word number respectively.  The book in question is the DEF CON 30 program.  Converting each line to it's respective word produced the following wordlist:  
![The book cypher](/assets/bookcypher.png)    
Now looking at the first letter of each word, backwards, we see the lyrics to "Never Gonna Give You Up".  
(Mind the mistakes, we were in a hurry!)  
`ANSWER: https://defcon.org/badge/30/urerjrtbntnva/eminor/918000000/thefinalcountdown/nevergonnagiveyouupnevergonnaletyoudown`  

7) The final challenge  
We are given the following text:  
`Bring the badgemakers a gum wrapper with the final`  
`subdirectory for each of your friends and the answer to`  
`"Who died and left you in charge?" written on it.`  
The subdirectories needed are: howdoththelittlecrocodile (Alice), 23044100 (Bob), intergalactic (Carol), aykroyd (Dan), and nurv (Eve).  
The final question "Who died and left you in charge?" is a quote from the movie "Spaced Invaders", the answer to the question is "Captain Bipto!"  
`ANSWER: howdoththelittlecrocodile 23044100 intergalactic aykroyd nurv Captain Bipto`


<br/><br/>
<a name="after"></a>
Afterthoughts
===
If you've made it this far, thank you so much for your time!  I hope you learned something interesting on the way.  And I REALLY hope you watched the Trevor video, if you've never seen it before.  
<br/>
Winning this year's badge challenge has been overwhelming.  This hits so close to home for me - many years ago I randomly stumbled across an article on the internet that turned out to be the badge challenge writeup from a past DEF CON.  It was that writeup that not only inspired me to start attending DEF CON, but also to start playing regularly in CTFs and participate in challenges like this as often as I can.  It has probably had a huge impact on my life and career, come to think of it.  And now to have actually won this contest, and to be sitting here, writing the very same article that first inspired me... I'm at a loss for words.  It's surreal!   <br/>  
Of course at the end of the day, credit belongs to the badge hacking community.  It was a group effort to solve these challenges - none of us could have done it without all the collaboration and teamwork we had.  It was a joy.  I look forward to working with you all next year!  
<br/>  
![Black Badge Front](/assets/bbf.jpg)  
<br/>  
![Black Badge Back](/assets/bbb.jpg)  
<br/>  
If you were at the awards ceremony, and you played music on your badge with me and the rest of the con, I just want to say: you are awesome.  
![Award Ceremony](/assets/stage.jpg)    



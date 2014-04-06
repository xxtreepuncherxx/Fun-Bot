Punch Bot
=======

A Bot script which is used for [PunchCraft MineCraft](http://plug.dj/punchcraft/)

`warning`
- Do not use this bot without Author permission this bot is only allowed for staff members of [PunchCraft](http://plug.dj/punchcraft/)!!

You can customize this bot script once you fork it.
How to function it? scroll down [HERE](https://github.com/DJ-Neon05/Fun-Bot#installing-bot)

---
## What can this bot do? ##

###- Bot Commands
- Bot commands are mainly to instruct the bot
  - Admins of the bot can also use the moderators commands
      - Helpful for moderating the room.
  - While using `.commands` you can also instruct bot to show it's commands to other users. By simply Mentioning the user. `example 1`
  
`commands`

```
.reward | .reload | .die | .addsong | .flipcoin | .catfact | .dogfact | .hug | 
.8ball | .fortune | .songlink | .download | .help | .whywoot | .whymeh | .props | 
.votes | .woot | .meh | .skip | .say | .version | .userstats | .mystats | .source | .status
```
`example 1`
```
#Tools: .commands @Neon
#plugbot: @Neon My commands are ..[commands]..
```

- There some commands that Mention is included!
- Here are the commands below that are required for mentions

`example 2`
```
#JordanTheGuy: .reward @USER
#Plugbot: @USER, JordanTheGuy has rewarded you with a blueberry muffin. Enjoy!
```
- More commands will be available soon!

--
###- Filter Chat
- There is only two chat filters (for now).
- `Begger Filter` can be Enable/Disable by using command `.tbf` This will allow bot to moderate Fan begging in chat [delete fan begging] `example 1`
      - Bot can only do this process if bot has a staff rank.

`example 1`
```
[#Neon: Fan me] = [message deleted]
#Plugbot: Are you serious @Neon?
```
- `Command Filter` Allows bot to delete commands if a user sends out a command to chat.
  - To Enable/Disable `Command Filter` type `.tcf`

--
###- Gives rewards (Fun Command)
- You can command bot to give free reward to user(s) in the current lobby!
- Fun commands such as:
`.reward`
`.8ball`
`.hug`
`.fortune`
`.catfact`
`.dogfact`

    - Mention is included when using `.reward` and `.hug` commands.
`example 1` 
```
#Neon: .hug @USER
#plugbot: Gives soft hugs to @USER!! <3
```
- More fun commands will are coming soon!

--
###- Limits songs length
- Bot limits song 10 min and under.
- Song/Video that goes more than 10 min will allow bot to automatic skip. 
  - Bot will also reason for why it has skip the song!
  - An Example below
`example`

```
[ Plugbot has skipped the current DJ ]
#Plugbot: Sorry +DJ+ skipping because video exceeded the song time limit!
```
- Enable/Disable skipping songs... Coming soon!

--
###- Block Songs/Artist
- You can allow bot to automatically skip songs and artist if [keywords](https://github.com/DJ-Neon05/Fun-Bot/blob/master/Bot/Fun.js#L83) are on block list.
    - This will set bot to skip user and alert last dj, why song was skipped.
    - Example given below
`example`

```
#Plugbot: Sorry this Video/Artist is blocked!
[ Plugbot has skipped the current DJ ]
```

--
###- Helps put up link
- Usually random users can't have the opportunity to link out URLs into chat.
- Issue fix. bot can now help none staff users to link out random URLs
- An example is given below `example 1`

`example 1`
```
#Neon: [URL Hidden]
#Neon: Can you guys see the link?
#Tools: Can't see nothing
#Neon: .linkin www.YouTube.com/fQpgHvAYGNY
#Plugbot: https://www.YouTube.com/fQpgHvAYGNY
#Tools: There it is!
```

--
###- Interval announcements

- If you have a facebook group link you would like to share, or any message you would like to regularly announce, the bot can be configured to say a certain message every X number of songs.
    - You can add your own announcement keyword [HERE](https://github.com/DJ-Neon05/Fun-Bot/blob/master/Bot/Fun.js#L79) 

--
###- Greets the Joiners
- If a user joins the lobby. Bot can randomly send out greeting message to that user.
- Random keywords for greetings
`example`

```
#plugbot: Welcome @USER 
#Plugbot: Hey there @USER
#Plugbot: Glad you came by @USER
```

--
###- Current Song/Video Link
  - If `.songlink` It'll instruct bot to give the current playing video/song URL to chat.
    - Imagine provided with can be found [HERE](http://i1328.photobucket.com/albums/w536/Tawi_Bien/songlink_zps934f6316.png?t=1394283093)
  - An example is given below `example 1`

`example 1`
```
#Dark: .songlink
#Plugbot: @Dark - http://youtu.be/R2N16TDszf8
```
--
###- Remove Video/Audio/Audience
- When the script is being function bot can automatically remove video screen/audio in order for your pc to run faster!
  - This can allow your computer to run extra faster due to low cpu that is already being used.
  - An example screenshot [HERE](http://i1328.photobucket.com/albums/w536/Tawi_Bien/funbot_zpse09a0525.png)
        - You can toggle CPU through a various commands
  - CPU can be activated if moderators type `.die` 
        - Example below `example1`

```
#Neon: .die
#Plugbot: [Re-Enables Video/Audio/Audience]
```
  - Whats a CPU? A central processing unit (CPU) (formerly also referred to as a central processor unit) is the hardware within a computer that carries out the instructions of a computer program by performing the basic arithmetical, logical, and input/output operations of the system.

--
###- Room Stats
- Bot can monitor and save room's woot and other accountable statics within the room/user. Sends out last song's status.
  - Room stats and users stats
  - Your status can also be found within the bot `example1`
  - bot can also keep Users/Room status. An example has been setup below `example2`

```
#Plugbot: Neon Last played: song [stats: 0 Woot | 0 Grab | 0 Meh]
```
`example 1`
```
#Neon: .mystats
#plugbot: @Neon [Stats: Joins: 0 | Woot: 0 | Meh: 0 | Votes: 0 | Curates: 0 | Songs: 0 | Skips: 0]
```
`example 2`
```
#Neon: .roomstats
#plugbot: Room Statistics - Woot: 0 | Meh: 0 | Votes: 0 | Curates: 0 | Songs: 0 | Skips: 0 | Joins: 0 |
```


---
You can function your own bot script after forking this script.
```JavaScript
javascript:(function(){$.getScript('');}());
```

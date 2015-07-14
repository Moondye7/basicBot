Commands:
=========

X specifies a number  
Arguments between ( ) are optional


Manager
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X | sets the maximum afk time |
|!botname | (botname) | change the default bot name |
|!bouncer+ | | toggle bouncer+ |
|!skippos | X | set the position to which skip and lockskip moves the dj |
|!clearchat | |clears the chat |
|!cycle | | toggle DJ cycle |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled |
|!language | (language) | specify the language you would like the bot to use |
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled |
|!maxlength | X | specify the maximum length a song can be when timeguard is enabled |
|!logout | | logs out account bot is hosted on |
|!refresh | | refreshes the browser of whoever runs the bot |
|!usercmdcd | X | set the cooldown on commands by grey users |
|!usercommands | | toggle user commands |

Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | add user to the waitlist |
|!afkremoval | | toggles the afk check |
|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) |
|~~!deletechat~~ | ~~@user~~ | ~~delete all the chats by a certain user~~ |
|!lock | | lock the waitlist |
|!lockdown | | lock down the room: only staff can chat |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 |
|!remove | @user | remove user from the waitlist |
|!roulette | | start a roulette |
|!songstats | | toggle song statistics |
|!unlock | | unlock the waitlist |
|!welcome | | toggle the welcome message on user join |
|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit. |

Bouncer
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!afkreset | @user | resets the afk time of user |
|!afktime | @user | shows how long user has been afk |
|!autodisable | | toggle the autodisable |
|!ban | @user | bans user for 1 day |
|!blacklist / !bl | blacklistname | add the song to the specified blacklist |
|!commanddeletion | | toggles if bot commands gets deleted |
|!blinfo | | get information required to blacklist a song |
|!cycleguard | | toggles the cycleguard |
|!dclookup / !dc | (@user) | do dclookup for user |
|!english | @user | ask user to speak english (asked in the language they set plug to) |
|!eta | (@user) | shows when user will reach the booth |
|!filter | | toggles the chat filter |
|!forceskip | | forceskips the current song |
|!historyskip | | toggles the history skip |
|!jointime | @user | shows how long the user has been in the room |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!kill | | shut down the bot |
|!lockguard | | toggle the lockguard |
|!lockskip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message |
|!mute | @user (X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
|!reload | | reload the bot |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour |
|!skip | (reason) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) |
|!status | | display the bot's status and some settings |
|!timeguard | | toggle the timeguard |
|!togglebl | | toggle the blacklist |
|!togglemotd | | toggle the motd |
|!togglevoteskip | | toggle the voteskip |
|!unban | @user | unban user |
|!unmute | | unmute user |
|!whois | @user | returns plug related information about user |

Resident DJ
-----------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!ghostbuster | @user | überprüft, ob der Benutzer ghostet |
|!voteratio | @user | stellt die Vote Statistik für den Nutzer dar |
|!sessionstats | | display stats for the current session |
|!moondye7 | |  Moondye unser im Himmel, geheiligt werde dein YouTubeAccount. Dein Skill komme. Dein Sieg geschehe, wie bei DayZ, so bei Battle Royale. Bringe uns den Cancer durch Plug.Dj. Denn dein ist die Intelligenz und die Freundlickeit in Ewigkeit. AMENO! |
|!pjsalt | | DANIEL DU BLUTEST! Nimm das für deine Wunden :pjsalt: |

User
----

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer. |
|!autowoot | | links to PlugCubed, the advised script/plugin to use for autowooting |
|!ba | | explains the Brand Ambassador rank |
|!commands | | gives a link to the commands |
|!cookie | (@user) | give a cookie to user |
|!dclookup / !dc | | use dclookup on yourself |
|!emoji | | a link to a list with emoji's |
|!eta | | shows how long before you reach the booth |
|!fb | | links to the room's Facebook page (if set in the settings) |
|!gif | (message) | returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided. |
|!help | | links to an image to help get people started on plug |
|!join | | join the roulette if it's up |
|!leave | | leave the roulette if you joined |
|!link | | when the user is the DJ, give a link to the current song |
|!op | | links to the OverPlayed list (if set in the settings) |
|!ping | | pong! |
|!purchase | | returns link to purchase more plug notes |
|!rules | | links to the rules (if set in the settings) |
|!theme | | links to the room's theme (if set in the settings) |
|!website | | links to the room's website (if set in the settings) |
|!youtube | | links to the room's youtube page (if set in the settings) |
|!nicemoves| |  ┗(＾0＾)┓ N I C E M O V E S ᕕ(⌐■_■)ᕗ |
|!softeis | | isst das Softeis selber :4head: Du hast doch nicht geglaubt, dass du einfach so ein Softeis bekommst:md7kappa:|
|!kreygasm | | :kreygasm: NOW :kreygasm: THIS :kreygasm: IS :kreygasm: WHAT :kreygasm: I :kreygasm: CALL :kreygasm: MUSIC :kreygasm: |
|!bier | |  DRINK DAT BIER!!! :avabeer: :swiftrage: |
|!ritzenspalt | |  Ritzenspalt ist ein kleines ScriptKiddie :babyrage: , welches diesen Bot für Moondye7 gemacht hat :4head:|
|!residentsleeper | | residentsleeper: FORCED :residentsleeper: TO :residentsleeper: WATCH :residentsleeper: MOONDYE7 :residentsleeper: BECAUSE :residentsleeper:  FORSEN :residentsleeper:  IS :residentsleeper: OFFLINE :residentsleeper:  |


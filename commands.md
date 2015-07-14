Commands:
=========

X specifies a number  
Arguments between ( ) are optional


Manager
-------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!afklimit | X | Legt die maximale AFK-Zeit fest |
|!botname | (botname) | Ändert den Botnamen |
|!bouncer+ | | An / Ausschalten von Bouncer+ |
|!skippos | X | Legt die Position fest, an die Nutzer verschoben werden nachdem sie übersprungen wurden |
|!clearchat | | Leert den Chat |
|!cycle | | Aktiviert den DJ-Zyklus |
|!cycletimer | X | Legt fest wielange die es dauert bis ein Song mit !cycleguard übersprungen wird |
|!language | (language) | Stellt die Sprache des Bots ein |
|!locktimer | X | Legt fest wielange die Waitlist bei einem !lockguard gesperrt ist |
|!maxlength | X | Legt die maximale Songlänge fest |
|!logout | | Loggt den aktuellen Bot-Benutzer aus |
|!refresh | | Lädt den Browser des Bot-Hosts neu |
|!usercmdcd | X | Legt den Zeitabstand fest indem user Befehle benutzen können |
|!usercommands | | Aktiviert / Deaktiviert User-Befehle |

Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:---------:|:--------------------------------------:|
|!add | @user | Fügt einen User zur Warteliste hinzu |
|!afkremoval | | Aktiviert / Deaktiviert den AFK-Check |
|!autoskip | | Überspringt Songs automatisch im Falle eines Cyclebugs |
|~~!deletechat~~ | ~~@user~~ | ~~Löscht alle Nachrichten eines Users~~ |
|!lock | | Sperrt die Warteliste |
|!lockdown | | Sperrt den Chat. Nur Bouncer, Manager und Host/Co-Hosts können chatten |
|!move | @user (X) | verschiebt einen User zu einer bestimmten Position in der Warteliste |
|!remove | @user | Entfernt einen Nutzer von der Warteliste |
|!roulette | | Startet ein Roulette |
|!songstats | | Aktiviert / Deaktiviert Song-Statistiken |
|!unlock | | Entsperrt die Warteliste |
|!welcome | | Aktiviert / Deaktiviert die Wilkommensnachricht |
|!voteskip | (X) | Wenn eine bestimme anzahl and Meh's erreicht wurde wird der aktuelle Song geskippt  |

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
|!ask / !8ball | (message) |stell dem Bot eine Frage, er wird mit einer zufälligen Variation  einer Ja/Nein Antwort antworten . |
|!autowoot | | verlinkt zu PlugCubed, dem empfohlenen Plugin für Autowooting |
|!ba | | erklärt den Brand Ambassador Rang |
|!commands | | gibt Link zu den commands |
|!cookie | (@user) | gib einer Person einen Keks! |
|!dclookup / !dc | | benutz dclookup an dir selbst |
|!emoji | | Link zu einer Liste von emoji's |
|!eta | | zeigt, wie lange es dauert, bis du dran bist |
|!fb | | verlinkt zur Facebook Seite des Raums (Falls es in den Optionen festgelegt ist) |
|!gif | (message) | postet ein gif (von giphy) passend zu den Schlagwoertern. Postet ein zufälliges gif, wenn keine Schlagwoerter benutzt wurden. |
|!help | | gibt Link, welcher Neulingen hilft |
|!join | | dem Roulette beitreten, falls es aktiv ist |
|!leave | | das Roulette verlassen |
|!link | |wenn der User am Dj Pult ist, Link zum Song geben |
|!op | | verlinkt zur Overplayed Playlist (Falls es in den Optionen festgelegt ist) |
|!ping | | pong! |
|!purchase | | gibt Link zum Kauf von weiteren PlugNotes |
|!rules | | verlinkt zu den Regeln (Falls es in den Optionen festgelegt ist) |
|!theme | | verlinkt zum Thema des Raums (Falls es in den Optionen festgelegt ist) |
|!website | | verlinkt zur Website des Raum's (Falls es in den Optionen festgelegt ist) |
|!youtube | | verlinkt zum Youtube Kanal (Falls es in den Optionen festgelegt ist) |
|!nicemoves| |  ┗(＾0＾)┓ N I C E M O V E S ᕕ(⌐■_■)ᕗ |
|!softeis | | isst das Softeis selber :4head: Du hast doch nicht geglaubt, dass du einfach so ein Softeis bekommst:md7kappa:|
|!kreygasm | | :kreygasm: NOW :kreygasm: THIS :kreygasm: IS :kreygasm: WHAT :kreygasm: I :kreygasm: CALL :kreygasm: MUSIC :kreygasm: |
|!bier | |  DRINK DAT BIER!!! :avabeer: :swiftrage: |
|!ritzenspalt | |  Ritzenspalt ist ein kleines ScriptKiddie :babyrage: , welches diesen Bot für Moondye7 gemacht hat :4head:|
|!residentsleeper | | residentsleeper: FORCED :residentsleeper: TO :residentsleeper: WATCH :residentsleeper: MOONDYE7 :residentsleeper: BECAUSE :residentsleeper:  FORSEN :residentsleeper:  IS :residentsleeper: OFFLINE :residentsleeper:  |


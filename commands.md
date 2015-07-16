Moondye7 Plug DJ Commands:
=========

X legt eine Nummer fest  
Argumente zwischen ( ) sind optional, daher nicht notwendig


Manager
-------

|Command | Arguments |  Beschreibung |
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
|!reload | | Bot neu Laden |
|!usercmdcd | X | Legt den Zeitabstand fest indem user Befehle benutzen können |
|!usercommands | | Aktiviert / Deaktiviert User-Befehle |
|!mugge | |  ɪᴄʜ ʙɪɴ ᴅᴇʀ ʟɪᴇʙᴇ ᴍᴜɢɢᴇᴍᴀɴɴ <3 |

Bouncer+
--------

|Command | Arguments |  Beschreibung |
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
|!voteskip | (X) | Wenn eine bestimmte Anzahl an "Mehs" die Anzahl der "Woots" um X übersteigt, wird der Song geskippt.  |

Bouncer
-------

|Command | Arguments |  Beschreibung |
|:------:|:---------:|:--------------------------------------:|
|!afkreset | @user | setzt den afk Timer eines Nutzers zurück |
|!afktime | @user | zeigt, wie lange ein Nutzer bereits afk ist |
|!autodisable | | Wenn es aktiviert ist, sendet der Bot !afkdisable und !joindsiable jede Stunde aus. Das deaktiviert Afk Nachrichten und Autojoining auf plugcubed |
|!ban | @user | Nutzer für 1 Tag verbannen |
|!blacklist / !bl | blacklistname | Song zu der festgelegten Blacklist hinzufügen |
|!commanddeletion | |Befehlslöschung aktivieren/deaktivieren |
|!blinfo | | erhalte Informationen, um den Song auf die Blacklist zu setzen |
|!cycleguard | | aktiviert/deaktiviert |
|!dclookup / !dc | (@user) | führt dclookup für einen Nutzer aus |
|!english | @user |bittet Nutzer, Englisch zu sprechen (fragt in der festgelegten Plug DJ Sprache) |
|!eta | (@user) | zeigt an, wann der Nutzer an der Reihe ist |
|!filter | | aktiviert/deaktiviert den Chatfilter |
|!forceskip | | überspringt den momentanen Song |
|!historyskip | | aktiviert/deaktiviert das Überspringen von bereits gespielten Songs |
|!jointime | @user | zeigt, wie lange der Nutzer schon anwesend ist |
|!kick | (X) | kickt Nutzer für X Minuten, Standard ist 0.25 (15 sekunden) |
|!kill | | deaktiviert den Bot |
|!lockguard | | aktiviert/deaktiviert den lookguard |
|!lockskip | (reason) | überspringt, sperrt und verschiebt den Dj wieder nach oben (die Position kann mit !skippos festgelegt werden) |
|!motd | (X)/(message) |Wenn kein Argument gesetzt ist, zeigt es die momentane Nachricht des Tages an, wenn jedoch X gesetzt ist, dann wird die Nachricht alle X Songs, falls eine Nachricht gesetzt ist, angezeigt.|
|!mute | @user (X) | Nutzer stumm schalten, für X minuten, falls X festgelegt ist, ansonsten für eine undefinierte Zeitspanne |
|!restricteta | | aktiviert/deaktiviert die eingeschränkte Nutzung von !eta: Normale Nutzer können diesen command nur einmal pro Stunde benutzen |
|!skip | (reason) | skippt den Dj mithilfe von smartskip. Aktionen wie schließen und verschieben hängen von verschiedenen Faktoren ab (die Position, auf die der Dj nach dem skip verschoben wird, kann mit!skippos festgelegt werden) |
|!status | | Status und einige Optionen des Bot's anzeigen |
|!timeguard | | Zeitwächter aktivieren/deaktivieren |
|!togglebl | | Blacklist aktivieren/deaktivieren |
|!togglemotd | | Tagesnachricht aktivieren/deaktivieren |
|!togglevoteskip | | Voteskip aktivieren/deaktivieren |
|!unban | @user | Nutzer entbannen |
|!unmute | | Nutzer entmuten |
|!whois | @user | zeigt Plug spezifische Informationen über diesen Nutzer an |

Resident DJ
-----------

|Command | Arguments |  Beschreibung |
|:------:|:---------:|:--------------------------------------:|
|!active | (X) | Zeigt an, wieviele Benutzer in den letzten x Minuten gechattet haben. Wenn X nicht festgelegt ist, ist 60 als Standart festgelegt |
|!ghostbuster | @user | überprüft, ob der Benutzer ghostet |
|!voteratio | @user | stellt die Vote Statistik für den Nutzer dar |
|!sessionstats | | zeigt die Statistik der momentanen Session an |
|!moondye7 | |  Moondye unser im Himmel, geheiligt werde dein YouTubeAccount. Dein Skill komme. Dein Sieg geschehe, wie bei DayZ, so bei Battle Royale. Bringe uns den Cancer durch Plug.Dj. Denn dein ist die Intelligenz und die Freundlickeit in Ewigkeit. AMENO! |
|!pjsalt | | DANIEL DU BLUTEST! Nimm das für deine Wunden :pjsalt: |
|!lauch | @user | Schlag jemanden mit einem Plüschlauch! |

User
----

|Command | Arguments |  Beschreibung |
|:------:|:---------:|:--------------------------------------:|
|!ask / !8ball | (message) |stell dem Bot eine Frage, er wird mit einer zufälligen Variation einer Ja/Nein Antwort antworten . |
|!autowoot | | verlinkt zu PlugCubed, dem empfohlenen Plugin für Autowooting |
|!ba | | erklärt den Brand Ambassador Rang |
|!commands | | sendet Link zu den Commands |
|!cookie | (@user) | gib einer Person einen Keks! |
|!dclookup / !dc | | benutz dclookup an dir selbst |
|!emoji | | Link zu einer Liste von emoji's |
|!eta | | zeigt, wie lange es dauert, bis du dran bist |
|!gif | (message) | postet ein gif (von giphy) passend zu den Schlagwörtern. Postet ein zufälliges gif, wenn keine Schlagwörter benutzt wurden. |
|!help | | sendet einen Link, welcher Neulingen hilft |
|!join | | dem Roulette beitreten, falls es aktiv ist |
|!leave | | das Roulette verlassen |
|!link | | wenn der User am Dj Pult ist, sendet es einen Link zum Song |
|!op | | verlinkt zur Overplayed Playlist (Falls es in den Optionen festgelegt ist) |
|!ping | | pong! |
|!purchase | | sendet Link zum Kauf von weiteren PlugNotes |
|!rules | | Link zu den Regeln (Falls es in den Optionen festgelegt ist) |
|!theme | | Link zum Thema des Raums (Falls es in den Optionen festgelegt ist) |
|!social | | Link zu allen Moondye7 Social Links |
|!plugin | | Link zum empfohlenen PlugDj Plugin |
|!nicemoves| |  ┗(＾0＾)┓ N I C E M O V E S ᕕ(⌐■_■)ᕗ |
|!softeis | | isst das Softeis selber :4head: Du hast doch nicht geglaubt, dass du einfach so ein Softeis bekommst:md7kappa:|
|!kreygasm | | :kreygasm: NOW :kreygasm: THIS :kreygasm: IS :kreygasm: WHAT :kreygasm: I :kreygasm: CALL :kreygasm: MUSIC :kreygasm: |
|!bier | |  DRINK DAT BIER!!! :avabeer: :swiftrage: |
|!ritzenspalt | |  Ritzenspalt ist ein kleines ScriptKiddie :babyrage: , welches diesen Bot für Moondye7 angepasst hat :4head:|
|!simplex | | Simplex ist ein :md7lauch:, der den Bot mit Ritzenspalt zusammen am laufen hält |
|!nazimod | | ༼, ͡ຈ ͜ʖ ͡ຈ,༽ ヽ____卐卐卐卐 - beachtet mich nicht... ich führe nur die Mods Gassi :4head|
|!slap | @user | Schlag jemanden ins Gesicht! |
|!residentsleeper | | residentsleeper: FORCED :residentsleeper: TO :residentsleeper: WATCH :residentsleeper: MOONDYE7 :residentsleeper: BECAUSE :residentsleeper:  FORSEN :residentsleeper:  IS :residentsleeper: OFFLINE :residentsleeper:  |


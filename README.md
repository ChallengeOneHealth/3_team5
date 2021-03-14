# 3_team5 - Challenge One Health MUD ( Challenge One Health Multi User Dungeon )

---
## Pitchvideo
Graphik anklicken um Video zu starten!

[![Challenge One Health MUD](https://raw.githubusercontent.com/hemmerling/challengeonehealthmud/master/challengeonehealthmud.jpg)](https://youtu.be/nSFE1z9yMpg)

auf dem [YouTube Channel "Rolf Hemmerling"](http://www.youtube.com/channel/UCmionNDYdoE1AEB-3NVVZeQ)

---
## Teammitglieder

**Rolf Hemmerling** - *Ideengeber:in & Entwicker:in* & *Designer:in* - [GitHub "hemmerling"](http://www.github.com/hemmerling/)

---
## Problemstellung 

Thema #1 des Challenge One Health Hackathons: "Wie kann das öffentliche Gesundheitswesen in Zukunft auf Pandemien vorbereitet werden?"

Menschen erfahren von Pandemien nur als Betroffene durch eigene Krankheit oder die von Verwandten / Bekannten ( bei der aktuellen Corona-Pandemie ab 2020-03 zum Zeitpunkt des Hackathons 2021-03 sehr selten bis gar nicht, da ja fast niemand bislang erkrankt oder gar gestorben ist ), sowie durch häufig als Willkür und unsinnig empfundene staatliche Maßnahmen und Einschränkungen. 

Eine positive vorbeugende oder eine Pandemie begeleitende Beschäftigung mit dem Thema Pandemie, vergleichbar "Zähneputzen" für das Thema "Gesunde Zähne behalten, Vermeiden von Zahnarztbehandlungen", findet bislang kaum statt.

--- 
## Lösung 
Öffentlichkeitsarbeit machen. Mein Ansatz: Gamification, Anbieten einer unterhaltsamen ( Online- ) Computer-Anwendung, die Menschen für das Thema sensibilisiert. Die Benutzer der Computer-Anwendung können ihr im Spiel gezeigtes Verhalten selber am Spielerfolg bewerten und es werden Lösungsmöglichkeiten für besseres Verhalten in Zeiten einer Pandemie sowie vorbeugendes Verhalten aufgezeigt. Kein "Zeigefinger-Spiel" mit stark belehrendem Charakter!

Häufig wird nichtstaatliche Öffentlichkeitarbeit zu brennenden sozialen, wirtschaftlichen und ökologischen Problemen durch unabhängige, nichtstaatliche Organisationen ( NGOs - Non-Governmental Organisation ) gemacht. Dabei kann in diesem speziellen Fall auch ich als Einzelperson in die Rolle einer NGO schlüpfen, "Dank" dem Internet und der daraus eventuell möglichen Sichtbarkeit für alle Internet-Nutzer.

Mein geplante Gamification-Anwendung ist der "Challenge One Health MUD " ( "Challenge One Health Multi User Dungeon" ).

Was ist ein MUD:

[Wikipedia "Multi User Dungeon"](http://de.wikipedia.org/wiki/Multi_User_Dungeon): Ein Multi User Dungeon (Abkürzung: MUD, selten auch Multi-User Dimension, Multi-User Domain oder Multi-User Dialog) ist eine üblicherweise textbasierte virtuelle Welt, in der mehrere Spieler (Mudder oder MudHeads) gleichzeitig mittels Computern spielen. MUDs verbinden Eigenschaften von gemacht Rollenspielen, Hack and Slays, Player versus Player-Kämpfen, interaktiven Fiktionen und Online-Chats miteinander. Viele MUDs gehören zu den Online-Rollenspielen.

Konkret besteht so ein MUD in seiner reinen ursprünglichen Form aus einer Reihe von Räumen - wie in einem Haus -, zwischen denen wechseln kann. Man kann also einen Raum betreten, indem man im selben Augenblick den Raum verlässt, in dem man aktuell ist. Ein Raum muss also mindestens einen Eingang haben, und falls er keine Sackgasse darstellen soll, auch mindestens einen Ausgang. Also zwei "Türen". In den Räumen kann der MUD-Benutzer mit anderen MUD-Nutzern, Gegenständen und sogenannten "Non-Player-Characters" ( NPC ) interagieren.

Bezogen auf meinen "Challenge One Health MUD", kann der MUD-Benutzer wie in einem Museum durch mehrere Räume gehen, sich dort informieren, mit anderen MUD-Nutzern chatten, aber auch mit Gegenständen bzw. NPCs interagieren. Seine Entscheidungen für oder gegen etwas ( z.B. Annahme eines Gegenstandes "Impfpass" ) entscheiden dann im Folgenden über seine weiteren Möglichkeiten ( z.B. Aktion "Impfung" nur möglich, wenn man schon einen Gegenstand "Impfpass" hat ). 

---

Dazu verwende ich ein in der Programmiersprache Python geschriebenes Open-Source-Framework [[Evennia - The Python MU* Development Library]](http://www.evennia.com/). Vor Beginn des Hackathons hatte ich zwar das Spiel lokal auf meinem Software-Entwicklungsrechner installiert, habe auch ausreichende praktische Kenntnisse in der Programmiersprache Python um gleich anzufangen, aber die 48h Zeit im Hackathon gingen natürlich im Wesentlichen drauf für die Einarbeitung in das Framework, durch Durcharbeiten von 2 Tutorials. Der tatsächlich entstandene Code für das eigentliche Projekt ist also naturgemäß gering geblieben.

Das nächste Ziel nach dem Hackathon ist, die Gamification-Anwendung auf eine (kostenlose) Online-Plattform mit eigener Web-Adresse zu bringen, wo die Gamification-Anwendung ausgeführt werden kann. Dies ist grundsätzlich möglich, weil das spezielle MUD-Framework eine fertige Web-Oberfläche für jedes selbsterstellte MUD-Anwendung mitbringt, d.h. die MUD-Anwendung kann und muss vom Benutzer und Administrator im Internet-Browser aufgerufen werden. Es ist nicht notwendig, eine eigene Internet-Domain zu nutzen, bei vielen kostenlosen Online-Plattform Angeboten gibts halt eine Third-Level-Domain oder ein Unterverzeichnis auf einem öffentlichen Server. Das reicht für meine Zwecke, Schaffung einer Demo-Plattform, auch aus. Die Zahl der kostenlos nutzbaren Online-Plattformen, wo Python und Standard-Linux Tools wie ein C/C++ Compiler zur Verfügung stehen, ist allerdings stark begrenzt, im Vergleich z.B. zu 100 oder mehr kostenlose nutzbaren Online-Plattformen für PHP-Anwendungen.

Ich werde versuchen, auf einer mir zur Verfügung stehenden Online-Plattform für Python-Anwendungen die MUD-Software zu installieren. Wenn's klappt, wäre die Gamification-Plattform dauerhaft ( kostenlos für mich und die Benutzer der MUD-Anwendung ) nutzbar.

Wenn die MUD-Anwendung auf einer Online-Plattform tatsächlich laufen sollte, wäre sie erstmal in erster Hinsicht für Software-Entwickler interessant, die sich für das MUD-Framework interessieren und durch Benutzung meiner MUD-Anwendung lernen wollen, wie sie selber ihre eigene MUD-Anwendung zum laufen bringen. Ein nachweisbarer Kundennutzen für die eigentliche Zielgruppe, Menschen die bereit sind sich spielerisch mit der Vorsorge und Verhalten bei Pandemien zu beschäftigen, ist davon leider noch weit entfernt. Da die MUD-Anwendung als OpenSource auf GitHub gehostet wird,  können andere Entwickler einen Fork erstellen und selber auf eigene Faust die Idee und den Code weiterenteickeln.

---
## Code Repository

[GitHub "hemmerling/challengeonehealthmud"](http://www.github.com/hemmerling/challengeonehealthmud)

---
## Slack Channel

3_team5

---
## Lizenz

MIT Lizenz [LICENSE.md](LICENSE.md)

---
## Was fehlt eurem Projekt noch?
* **Zeit** um sich in das MUD Framework einzuarbeiten, um dann wirklich eine vorführbare Gamification-Anwendung mit erkennbarem Kundennutzen zu haben
* **Online-Plattform**, wo die Gamification-Anwendung gespielt werden kann. Ich werde versuchen, auf einer mir zur Verfügung stehenden Online-Plattform für Python-Anwendungen die MUD-Software zu installieren. Wenn's klappt, wäre die Gamification-Plattform dauerhaft ( kostenlos für mich und die Spieler ) nutzbar.
---


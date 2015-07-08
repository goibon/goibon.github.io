---
title: Wonder Wool
layout: game
thumbnail: wonder-wool-appicon.png
icon: wonder-wool-appicon.png
cover_image: wonderWool_fb_cover.png
short-description: A mobile game developed for Android and iOS during my semester at DADIU. The game was developed over the course of a month with a team of 18 people. The game was created using Unity3D and all game code was written in C#.
---
* TOC
{:toc}

#Summary
A casual free to play flock runner for Android and iOS developed during my semester at DADIU[^0] in 2014. For this project I was lead programmer in charge of six game programmers working closely with the rest of the lead team[^1]. My role as lead programmer is described in more detail in **[My Role](#my-role)**, but mainly I was in tasked with the following:

- Creating, discussing, and delegating tasks for the game programmers.
- Meeting with the lead team and discussing the development of the game.
- Acting as a primary link of communication between programmers and the rest of the team.
- Making sure that the game followed the [conditions for the game](#conditions-for-game).

In the game the player controls a flock of sheep and has to steer them through various levels while they are fleeing from a cyclops that wants to steal the sheep. The player needs to get as many sheep as possible through the levels in order to obtain their wool, which he can acquire more of if the sheep eat grass during the level. 

The game is set in ancient Greece and uses characters from Greek mythology such as Zeus, who aid the player by giving him godly powers like the ability to strike down the terrain with lightning to clear a path for the sheep. The game contains nine unique levels presenting various terrain hazards such as mud that slows down the sheep, and pillars that can crush them. There is also two god powers available, one being the lightning strike, and the other being the power to make the sheep eat grass much faster thus reducing the risk that they are left behind.

##Download
[![Google Play Link]({{site.url}}/Assets/Google-Play-Badge.png)](https://play.google.com/store/apps/details?id=dk.dadiu.woolympians)
[![App Store Link]({{site.url}}/Assets/App-Store-Badge.svg)](https://itunes.apple.com/us/app/wonder-wool/id958953053)

#Development
The game was developed in the period of November 1st through December 5th 2014 with two weeks of pre-production in October.
The pre-production weeks consisted of the lead team[^1] coming up with idea for the game and designing it. We actually had to come up with ideas and designs for three different games and pitch all these to the head of DADIU both in order to see which ones they thought would be most viable but also to practice presenting and selling ideas for games.
After the pre-production period the whole team of the 18 people listed in **[Credits](#credits)** gathered in the office space given to us and the production began immediately.


##My Role
During the project I was lead programmer which meant that I was in charge of the six game programmers of the team. I was also in charge of all technical responsibilities such as making sure that the game adhered to the **[Conditions](#conditions-for-game)** that DADIU had set up for the game.

As I was the only programmer with a position in the lead team i was also the person in charge of communication between game programmers and the rest of the team. While the game programmers would of course still talk with other members of the team, I was the one having meetings with the lead team and discussing the feasability of various ideas for the game based on my experience and knowledge of game programming. 

After a meeting I would then round up the game programmers and discuss upcoming tasks with them and make sure everybody understood them. As well we would estimate the time it would take to complete these tasks and these estimates would be reported back to the project manager by me.

##Major Decisions During Production
As lead programmer I made a series of decision that I felt would aid the production of the game, listed here are some of the ones I felt had a big impact on the production.

###Git
From my experience from previous projects I knew that version control would be important and I had personally used git for almost all of my projects the past couple of years and as such I decided to use it for this game as well. None of the game programmers had experience with any version control system other than SVN, yet I decided to use git anyways knowing that I would have to teach them how to use it.

###Pull Requests and Code Reviews
Since I had decided to use git I also decided that we'd use the concept of pull requests and code reviews. Whenever a programmer was sure he had completed a task in a satisfactory way he would create a pull request to get his code into the development branch of the git repository. Then the other programmers were to review the pull request to make sure the submitter had not missed anything.

To not spend too much time reading other peoples code and reviewing it, I decided that it was enough for just one programmer to have approved a pull request. Once it was approved by at least one programmer then QA programmer would then merge the pull request into the development branch.

This workflow worked well and many bugs where spotted during reviews and saved the programmers some headaches that would have risen later on had it not been detected and fixed.


###Unity 4.6 Beta
Initially the production began with using Unity 4.5 but about two weeks into he project Unity released the public beta version of Unity 4.6 which had a completely new UI system that performed much faster than the old one. This was something I was very eager to use, but knowing that beta software can be less stable than release versions I decided to have a few programmers test it out to see if any major issues came up. Since none did I had the whole team upgrade to Unity 4.6 and this allowed for a much greater and faster UI in the game.

###Unity Cloud Build Beta
As I had seen how much time our QA programmer had spent compiling the game during the [minigame production](link to bunny nights) I decided to use the new Unity Cloud Build[^2] beta that had just been made available. Again this was use of beta software, but I knew that we could still compile the game ourselves at any time, should the need arise.

It turned out to be a great benefit to use UCB as the members of the team did not need to build the game themselves, instead they could simply just download a finished build straight onto their devices whenever they wanted to test something or just see the game.

##Conditions for Game
The conditions for the game as written by DADIU.

- Genre: Casual
- Platform: Samsung Galaxy 2
- Mode: Single player
- Levels: At least five levels demonstrating game features and monetization strategies. In a “level-free” game this condition is substituted by five features / gameplay elements.
- Business: Free2Play with built-in functions (modifiers, customization, services, etc.) for monetization.  
- App store: Make a nonfunctioning mockup of a store - be aware to clearly state it is NOT a real shop and consider giving (e.g.) 10 diamonds/points as “hard currency”. This will enable your users to “spend real money” in your game. 
- Metrics: Include metrics (eg. game session started/ended, Unique User, Paying Unique User, etc.).
- APK size limit: The APK file size cannot exceed 50 MB.
- Languages: Danish/UK English (enable choice at start screen).
- Splash sreens: DADIU splash screen is #1, Unity is #2 + #3 splash screen is the Game Title. The screens may be interrupted by touch. You are not allowed to modify the logos and lettering from DADIU and Unity. The DADIU splash screen says: “Produced by DADIU / Logo / The National Academy of Digital Interactive Entertainment / www.dadiu.dk”


#Credits
<ul style='text-align: right;list-style-type: none;display: inline-block;'>

<li>Ursula Blix</li>
<li>Nils Sørensen</li>
<li>Tim Løye Skafte</li>
<li>Kasper Lind Sørensen</li>
<li>Asger Arentoft</li>
<li>Gustav Lund</li>
<li>Knut Liestøl</li>
<li>Mikkel Kristoffer Buhl</li>
<li>Toke Wivelsted</li>
<li>Tommy Aagaard Christensen</li>
<li>Svetla Tomova</li>
<li>Emil Juul Clevin</li>
<li>Ludwig Sandbacka</li>
<li>Anchelika Skjødt</li>
<li>Casper Knudsen</li>
<li>Henrik Josefsen</li>
<li>Jonathan Buus Horskjær</li>
<li>Dennis Gravenhorst</li>
 
</ul>
 
<ul style='text-align: center;list-style-type: none;font-weight: bold;display: inline-block;'>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
<li>-</li>
</ul>

<ul style='text-align: left;list-style-type: none;display: inline-block;'>
<li>Game Director</li>
<li>Game Designer</li>
<li>Level Designer</li>
<li>Lead Programmer</li>
<li>Pipeline Programmer</li>
<li>QA Programmer</li>
<li>Programmer</li>
<li>Programmer</li>
<li>Programmer</li>
<li>Programmer</li>
<li>Technical Artist</li>
<li>Art Director</li>
<li>Visual Designer</li>
<li>Animator</li>
<li>CG Artist</li>
<li>CG Artist</li>
<li>Audio Designer</li>
<li>Project Manager</li>
</ul>

------
*[DADIU]: The National Academy of Digital Interactive Entertainment
*[UCB]: Unity Cloud Build
[^0]: [http://www.dadiu.dk](http://www.dadiu.dk)
[^1]: The lead team consisted of: Project Manager, Game Director, Art Director, Lead Programmer, and Game Designer.
[^2]: [https://build.cloud.unity3d.com/landing/](https://build.cloud.unity3d.com/landing)
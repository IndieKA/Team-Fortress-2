# Team Fortress 2
www.teamfortress.com

[![Join the chat at https://gitter.im/IndieKA/Team-Fortress-2](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/IndieKA/Team-Fortress-2?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<img src = "https://images-na.ssl-images-amazon.com/images/G/01/videogames/detail-page/tf2_1_lg.jpg" width="700" height="400"/>

Team Fortress 2 is a team based FPS game created by Valve Corporation and downloadable on [Steam] (https://store.steampowered.com/apps/440). It is the continuation of Team Fortress, an original FPS from 1996. The game has gotten more than 300,000 ratings on Steam itself and was rated 4.5/5 from Metacritic. It still continues to be a great multiplayer game today.

I (IndieKA) am creating a replica of Team Fortress 2 on Khan Academy, the same site in which I will be creating my Garry's Mod KA Project w/Yokuda. Want to check it out? Go to this link: https://www.khanacademy.org/computer-programming/team-fortress-2/6360667559428096. This is an open source project, so feedback and helpful discussion is always welcome. If you would love to contribute, head over to the Contributing section.

**Creators**:
- 
Yokuda:
* https://github.com/IndieKA (shares brother's account)

IndieKA
* https://github.com/IndieKA (shares w/brother)

You might be up here too, if you contribute a lot! =)

## Table of Contents
* [About] (#about)
* [Contributing] (#contributing)
* [Credits] (#credits)

## About
Team Fortress 2 is a team-based, first person shooter developed by VALVe (Valve Corporation) and is found on Steam to download. It is the sequel to the 1996 mod Team Fortress and its 1999 remake. It was originally released for the video game compilation _The Orange Box_ on October 10th, 2007, and it was only till April 8th, 2008 that the game would become a standalone title for Windows. Eventually, it was downloadable on Linux and OS X, making the game available for more players.

In _Team Fortress 2_, players are selected to join one of two teams (red vs. blue) choosing nine different character classes, each having a special ability and trait. The game has multiple game modes and maps, such as Capture the Flag and King of the Hill. Team Fortress 2 is also featured in the 3D classic sandbox _Garry's Mod_ and is powered by VALVe's _Source_ engine. The game received much attraction from YouTubers such as Tobuscus (Toby Turner) and PewDiePie (Felix Arvid Ulf Kjellberg) for its art, humor, and efficient gameplay. VALVe continues to update Team Fortress 2, releasing new content and new maps either according to the time of year or just a usual update. 

**Game modes:**
The objective of the mode depends on what it is, so let's find out.
* In CTF (Capture The Flag) maps, the main objective for both teams is to obtain a briefcase, containing "secrets" about the other team's plans, and returning it to their base to receive a point for their team, eventually leading up to see which team has the most points of them all. A match lasts till one team gets a higher score or time runs out. 
* Control Point mode is where a team stays near a "control point" for a short amount of time to get a point. However, if you leave a point out in the open, the other team has a chance to claim it. The team with the most points at the end of the round wins.
* King of the Hill mode is where there is a single control point out in the open, at the center of the designated map. Teams will fight over it, and if one team reaches the point first, a countdown is made until the round. If the opposing team intercepts it, their countdown starts, breaking the other team's launch procedure. The winning team is judged by which team can stay the longest till their countdown is over.
* Arena is a team deathmatch mode, where you have to either support or fight till the end for your team; there is no respawning at all. Dying inside the game will immediately make you a spectator, watching over how your other teammates do. A team wins the round by either capturing the control point or eliminating all of the other team members.
* Mann vs Machine is a six player co-op mode where the mercs have to defend a structure from waves of robots. Players have the ability to buy upgrades and improvements between rounds using in-game money earned during previous waves. 

**Characters:**
Team Fortress 2 features nine different characters categorized into offense, defense, and support roles. Each class has strengths and weaknesses; and must work with other players of different classes to have their team win. 
(information from _Wikipedia_ [Team Fortress 2])

**Offense:** 
* **The Scout:** is a baseball fan and street runner. He is a fast, agile character, armed with a scattergun, a pistol and an aluminum baseball bat. The Scout can double-jump and captures control points and pushes payloads twice as fast as other classes, but has the lowest health.
* **The Soldier:**  is more durable, but slower. The Soldier is armed with a rocket launcher, shotgun, and a folding shovel. The Soldier can use his rocket launcher to rocket jump to higher positions at the cost of some health.
* **The Pyro:** is a mentally unstable maniac of unknown gender who is armed with a with a flamethrower, fire axe, and a shotgun. 

**Defense:** 
* **The Demoman:** is a one eyed, heavy-drinking person armed with a glass bottle and some grenades with sticky bombs.
* **The Heavyman:** (voiced by the same person as _The Demoman_) is a large Russian who, although is the slowest class, can deal immense amounts of damage to players using a enormous minigun labeled "Sasha".
* **The Engineer:** is a character which can build sentry turrets and other objects to help his team, and is armed with a shotgun and a wrench tool that fixes things on hit. 

**Support:**
* **The Medic:** is a doctor armed with a "Medi Gun" which heals teammates and gradually builds a power that gives effect to the Medic. He keeps doves as pets, sometimes bloody.
* **The Sniper:** is of course, a sniper armed with a kukri (for close combat) and a long range sniper for helping take out enemies. Players usually find other snipers on towers and high positions. 
* **The Spy:** is an agent with tools like a "butterfly" knife and a device used to sabotage Engineer's buildings. His "butterfly" knife can take out any character (only if it is a backstab)

## How does KAPJS work?
You may know what ProcessingJS and how it works (processingjs.org), but Khan Academy's version of PJS is rather different. Observe:
**Normal PJS Code:**
```
void setup(){
  size(200, 200);
  frameRate(10);
}

void draw(){
  background(#ffffff);
  ellipse(100, 100, random(50), random(50);
}
```

**Khan Academy's PJS Code:**
```
draw = function(){
  size(200, 200);
  frameRate(10);
  background(255, 255, 255);
  ellipse(100, 100, random(50), random(50);
};
```

Notice how there is minor changes like `void draw()` would be `draw = function()` and the `background` system in Khan Academy uses the RGB filter. Their system was mainly designed like this for beginner programmers under the age of 13, (even though Yokuda and I are over 13) we will still be developing Team Fortress 2 on Khan Academy.

## Contributing
Yes, there is a guideline for contributing to this repository. Please read it over before you solve any issues/errors with the global program. Don't forget to either check out the LICENSE to see where it is licensed from, or see Yokuda's profile for proof work on the contributions. (http://www.khanacademy.org/profile/Yokuda)

THIS COPYRIGHT LICENSE was written all by me and Yokuda. PLEASE DO NOT take this into your repositories, even with credit. It is something that took us a while to type up, and this part of the README.md is not open-source. 

### Helpful contributions
---
**IMPORTANT**: Before contributing to this repository, read the following BEFORE the margin.
"You" or "Your" (group) shall accept the following terms and conditions for your contributions to this project. You(r) name will be Featured on the Credits list, with a link attached to your GitHub profile, and/or Khan Academy/Travis/any other collaborating site. By accepting this passage you agree to having the GitHub user @IndieKA sponsoring you and your contributions.

Contribution in this group shall mean work that is original. Please provide the source name (if) needed, including minor modifications and add-ons, and credit your origins wisely. You are contributing on behalf the following project WILL and most possibly USE your provided code. (WE) the users (WILL) use your code on note that we may add improvement/changes to the syntax. IF you are not satisfied WITH what we have done w/your code, you have all means to revoke your code request and leave the collaboration. YOUR code MUST be of Khan Academy's JavaScript or normal JavaScript, otherwise WE have all rights to reject your pull request. You do Agree, on all circumstances, to notify the Team Fortress 2 project WHEN you have made a modification to your code.

Subject to this agreement, you AGREE to not abuse or in any way, DISCRIMINATE against another user who has followed the Agreement listed. Rude or argumentative behavior WILL NOT be tolerated, and creators/contributors WILL be banned from further contributions. IF we find YOUR code is not original, there is a possibility you can be KICKED from the repository. The license(s) provided by MIT and GitHub to user @IndieKA are of his and theirs copyright, giving each right to grant and authorize any system to any user who agrees this copyright. You represent, your(self), that your creation is YOUR OWN. You provide Your Contributions to This Group on Agreement it MAY be used by a third party group IN THE CONCLUSION they WILL give proper credit to not only you BUT the Following Group.

REMEMBER that YOUR CODE can be sold, imported, and transfered to another company/organization ON BEHALF they will give credit to US AS WELL (and you). You CANNOT do anything AFTER a PIECE has been sold rather than US give the link to the other franchise/company/organization. 

IF you FAIL to meet the needs of (this) repository you MAY be kicked, or banned, from the following REPOSITORY, and may never be able to contribute again. YOU ARE BEING WATCHED. 

Thank you for taking the time to read this Agreement. Copyright @ IndieKA 2015 (this is not for use in any of your Repos)

### Syntax & Code

If you would like to contribute, instead of pointing out simple mistakes you can either try to do the following:
* **Try to fix bugs**: Just above this mini section is a small, yet reasonable list of bugs in the program. See if you can try to fix them! Report to @Yokuda or @Indie on Khan Academy if you have done so, and include the code w/it in case it is fixing a long part of the script.
* **Report any disruptive behavior or any problems with the interface**: Although these might not be _so_ important, they can lead to later problems regarding users/code. 

### Code Style
* -  No line indentations.
* -  Clean code (w/spaces between commas and indented code when needed) [IF you cannot clean your code well use http://jsbeautifier.org)
* -  camelCase with variables.
* -  80 character line length. Then you must indent.
* -  New changes cannot extend the original more than 700 lines of code (unless it is something VERY important)
In general, try to make your syntax blend in w/the actual code. 

### Pull Requests
* Link to the original w/the new added code/syntax.
* Before merging state changes
* Large pull requests should be separated into new folders

### Screenshotting
Before we add a user's change, we require a screenshot of what they have done. IF YOU ARE UNABLE to provide us w/that, your changes MAY NOT be accepted! Please, if you suggest a big change in the code, include a screenshot showing what you are going to change. Most screenshots will be taken on Khan Academy.

How our screenshot system works:
- Only focus on editor/picture
- Do not display any other tabs (or put your screen onto Fullscreen mode)
- If there are no visible changes, WE MAY possibly accept it, considering it might just be a minor bug fix or so.

### CODE ADDING
The most important out of all of them. In fact, this really should go first... 

Most of our basic things are handled in the "`basics`" folder, where all the details and components of the game last. If you try to merge your new code INTO another folder besides `basics`, YOU MUST have it to do w/something else rather than the actual `basics`. 

Please inform us in our Gitter chat where you are going to add your code. (https://gitter.im/IndieKA/Team-Fortress-2)

## Credits
* License: MIT (see LICENSE file)
* Original Author (Yokuda) 
* Repository: https://github.com/IndieKA/Team-Fortress-2 (created by IndieKA for Yokuda)
* Original program: https://www.khanacademy.org/cs/-/6360667559428096

### Copyright and license

Code and documentation created by IndieKA and Yokuda. Code released under the [MIT License] (https://github.com/twbs/bootstrap/blob/master/LICENSE). All rights reserved.

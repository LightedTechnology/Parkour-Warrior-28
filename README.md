<a href="https://youtube.com/c/LightedTechnology"> <img src="https://cdn.discordapp.com/attachments/879977373859196939/1083982633769377792/Untitled-5.png"> </a>

###### `ℹ️` Parkour Warrior is the ultimate test of the player's mobility. Players are tasked with the difficult challenge of traversing a difficult parkour course, while also battling against time. Complete courses, earn medals, and prove you are worthy of being called a Parkour Warrior!

<a href="..#-1">![Progress](https://img.shields.io/badge/Progress%3A-complete-success?style=for-the-badge&logo=hackthebox) </a>
<a href="..#download-tablet"> ![Download](https://img.shields.io/badge/Download%3A-available-success?style=for-the-badge&logo=dropbox) </a>

---

### What is Parkour Warrior?
**Parkour Warrior** is a minigame, designed for both single and multiplayer. It features:
- **3 game modes**,
  1. `👟` **Run** - Run is a mode, where you have no time limit, but the one you set yourself. Run is all about maximising your score while minimising your time. You earn medals for completing challenges. Finish multipliers apply. You can interact with the course by using a Teleportation Scroll or Reset Course.
  2. `🍹` **Casual** - In casual, there is no timer ticking from the beginning of the run. Instead, every checkpoint has its own timer. With Casual you can practice the challenges you find most difficult. You do not earn anything for completing challenges. To assist you, you are provided not only with a Teleportation Scroll and Reset Course, but also Skip Section and Reset Section.
  3. `🏁` **Synchronised Run** - Synchronised Run is similar to run, except the time is synchronised between all players. There is a time limit. In this mode, you (and your team) will attempt to finish as much challenges as possible, while also ensuring you have enough time to finish the course. In case you run out of time, there is an Overtime period, by default lasting 30 seconds, during which you can still harness medals from the course and finish it, but if you fall - you are out. Scrolls are taken away at the final sections, by default at 120 seconds. You earn medals for completing challenges. Finish multipliers apply to you and your team. You can only use the Teleportation Scroll to interact with the course.
  *Note that there is no Synchronised Casual.*
  *For more information on Utility items, check the Additional part of this README*
- **18 Parkour Branches**, of those:
  - `🟢` **5 Main zones**, each housing 3 challenges (15 in total), which you must complete to get to the end. You get awarded 1 stone medal for each.
  - `🟥` **5 Side Branches**, each housing 3 challenges (15 in total), which are not necessary to complete. In every side branch, you get 1 bronze medal for completing the 1st challenge, 1 silver medal for completing the 2nd, and 1 gold medal for completing the 3rd and going through the portal. You can abandon the Side Branch at any moment and go back to completing the Main course by using the Teleportation Scroll, if you find the current challenge too hard for you.
  - `🏆` **3 Endings**: Easy (1 challenge, +x0.15 multiplier), Medium (3, +0.4x), Hard (3, +1.25x). The harder the Ending you complete, the higher your multiplier will be. You do not get any medals for completing challenges within the Ending section.
  - *For more information on scoring, check the Additional part of this README*
- Several customisations: 
  1. Cosmetic, all of which but `🏯` can be bought for 1000 coins OR acquired for completing Advancements:
    - `🌈` **Auras** - Snowflakes,  Hearts,  Sakura Flower, Rainbows, Wind, Spooky Faces, Samurai Deco.
    - `🪨` **Trails** - Candycanes,  Mini Hearts,  Mini Sakura Flowers, Rainbow Drops, Wheat, Candy, Warrior.
    - `🎩` **Hats** - Deer Antlers,  Elegant Hat,  Flower Crown, Rainbow, Straw hat, Warlock's hat, Samurai Helmet.
    - `🪄` **Items** - Sparkler,  Paper Umbrella,  Flower Bouqet, Pride Backpack, Popsicle, Broom, Katana.
    - `📦` *Additional* - Reset Course, Skip Section, Reset Section customisation, team (all event ones + spectator).
  2. Visual (individual):
    - `👁️` **Night Vision** - If TRUE, gives the player an infinite Night Vision effect.
    - `🗺️` **Bossbars** - If TRUE, shows the player a checkpoint minimap and a timer at the top of their screen.
    - `🎵` **Soundtrack** - If TRUE, plays the OST (Parkour Warrior and Overtime) to the player.
    - `🏅` **Display of Awards** If TRUE, will display +COINS instead of +MEDAL when completing challenges (Only in Synchronised Run)
    - `🧮` **Coins Per Minute display** - If TRUE, will in addition to the run timer display the amount of coins the player has and a calculated with that CPM (Run only)
    - `🎗️` **Target time** - The VALUE, which the Timer Bossbar will fill out to.
  3. Gameplay affecting (global):
    - `⏲️` **Synchronisation** - If TRUE, all players become synchronised and event-like functionality is enabled.
    - `⏳` **Time** - The VALUE, which is the amount of time the players are given in Synchronised Run.
    - `🚩` **Invisibility** - If TRUE, if two players are within a distance of 8 blocks from each other, they will become invisible.
    - `🔔` **Overtime** - The VALUE, which determines the amount of time given for OVERTIME. Also determines when the Overtime OST begins playing. If 0, there is no overtime.
    - `🍂` **Fall distance** - The VALUE, which is the distance a player must fall in order to get teleported to their last checkpoint.
    - `📜` **Scrolls take away** - The VALUE, which when the time is below, scrolls at the final stages are taken away. If 0, scrolls aren't taken away.
    - `📦` *And a few hidden ones* (item cooldown & sunset - they are hidden because changing them is not advisable)
- **7 Advancements**, for completing which you get according cosmetics:
  - `🧊` **Chill!** - Complete the course and all the bonus paths within ten minutes.
  - `💘` **Mom's Spaghetti** - Complete the course without falling once.
  - `💐` **Pacifist-ish** - Complete the course without getting any coins.
  - `🌈` **Pride et Nemesis** - Complete the course, all the bonus paths, and finish via the Hard route.
  - `🌾` **Rakes!** - Finish the course with 25 medals or more.
  - `🍬` **Can Dye Land** - Complete the course within three minutes.
  - `🏯` **The Parkour Warrior** - Complete the course with a CPM score of 6 or more.
- **Additional content**:
  - `💔` No Checkpoint Mode (idea by [Fruitless Gaming](https://www.youtube.com/@FruitlessGamingYT)) - in this mode, if you fall - you are teleported to the beginning of the course. Available only in Run.
  - `📑` Statistics - This map provides everyone with a profile (featuring their fastest run, highest CPM, and most earned coins in one run). You can also access leaderboards for those three categories. At the end of each run, you are provided with a somewhat decent rundown on what you were doing.
  - `💻` UI - The map features an easy to interact with UI (replacing the default inventory), substituting the control book. This map is also the first one to feature my implementations of variable scoreboards and bossbars in mcfunction. The GUI is no longer copying MCC, instead, it tries to add its own touch with the blue and orange color scheme.
  - `🐸` Frogtown - A playground sprinkled with parkour elements and hang out areas. Weirdly, there are no frogs...

<img src="https://cdn.discordapp.com/attachments/879977373859196939/1084060868087644220/Download.png" alt="Download">

###### Download Tablet
| ℹ️ | Bundle | Version(s) | Description | Link |
| :---: | :---: | :---: | :--- | :---: |
| 🗺️ | Map | v1.0.0 | This pack only provides the map. | <a href="https://www.dropbox.com/s/giornledqx3fbop/Parkour%20Warrior%2028%20%5Bv1.0.0%5D.zip?dl=1" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dropbox/dropbox-tile.svg" alt="download" width="30" height="30"/> </a>  |
| 🎨 | Resource Pack | v1.0p | This pack only provides the resource pack. | <a href="https://www.dropbox.com/s/x8thgov87q29xag/Parkour%20Warrior%2028%20%5Bv1.0p%5D.zip?dl=1" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dropbox/dropbox-tile.svg" alt="download" width="30" height="30"/> </a> |
| 👜 | Singleplayer | v1.0.0🗺️<br>v1.0s🎨 | This pack provides the map with the texturepack embed. | <a href="https://www.dropbox.com/s/kf5tbolaw0zk5ig/Parkour%20Warrior%2028%20%5Bv1.0.0%5D%20%5Bv1.0%5D.zip?dl=1" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dropbox/dropbox-tile.svg" alt="download" width="30" height="30"/> </a> |
| 💼 | Hosting | v1.0.0🗺️ | This pack provides the map and a server.properties file. | <a href="https://www.dropbox.com/s/pbjdj04q5cg1jhl/Parkour%20Warrior%2028%20%5Bv1.0.0%5Dh.zip?dl=1" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dropbox/dropbox-tile.svg" alt="download" width="30" height="30"/> </a> |
| 🧰 | All-In-One |↑ 1.19.3 ↑ | This pack provides everything. | <a href="https://www.dropbox.com/s/td33lb77y09j5z0/Parkour%20Warrior%2028%20%5Bv1.0.0%5D%20%5Bv1.0%5D%20AIO.zip?dl=1" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dropbox/dropbox-tile.svg" alt="download" width="30" height="30"/> </a> |

### `🔗` Useful Links:
- [How To Add A Resource Pack to Your Minecraft Server](https://youtu.be/rjBJD1caRlA)
```
https://www.dropbox.com/s/cru5msoe7580bbr/Parkour%20Warrior%2028%20%5Bv1.0s%5D.zip?dl=1
```
## <img src="https://cdn.discordapp.com/attachments/879977373859196939/1084071684321050694/Additional.png" alt="Additional">

| ℹ️ | Utility | Modes | Usage |
| :---: | :---: | :--- | :--- |
| 📜 | Teleportation Scroll | All | The Scroll activates when the player is in a Side Branch or at the final sections. When used in a Side Branch, teleports the player to their last intersection. When used in the final sections, teleports the player to the intersection, at which you can re-choose the ending to pursue. Note that Teleportation Scrolls might be taken away at the Final Sections |
| 🔁 | Course Reset | Run, Casual | When the Course Reset is used, the player is teleported back to the beginning of the course, with all of their progress reset. |
| ➡️ | Skip Section | Casual | When the Skip Section is used, the player is teleported to the checkpoint for the next challenge. If used at an intersection, teleports the player to the bonus challenge only if it had not yet been completed in this run. If used at the final sections, always chooses the Medium ending. Resets the timer every time it is used.
| ⬅️ | Reset Section | Casual | When the Reset Section is used, if the player is further than 3 blocks from the checkpoint, teleports the player back to the checkpoint. Otherwise teleports to the checkpoint of the previous challenge. Resets the timer every time it is used. |

| ℹ️ |  Medal | 1 | 2 | 3 | 4 | All |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: |
| 🎖️ | Stone Medal | 2 | 2 | 2 | 2 | 30 |
| 🥉 | Bronze Medal | 2 | 7 | 15 | 22 | 35 |
| 🥈 | Silver Medal | 5 | 20 | 40 | 70 | 100 | 
| 🥇 | Gold Medal | 10 | 40 | 80 | 130 | 200 |
| 💎 | **Bonus** | 17 | 73 | 147 | 240 | 365|

### `⏰` Coins Per Minute
<img src="https://cdn.discordapp.com/attachments/669425247606276112/1086276143956623360/Untitled2.png">

`ℹ️` **CPM** (**CPTM**) is the baseline measurement of performance in this map. CPM is dervied by the formula $\frac{120 c}{t}$, where `c` is `coins` and `t` is `time in ticks`. CPTM is the same as CPM, but multiplied by a 100. Tips to improve CPM:
- If you are yet unable to do a challenge easily, either practise it in Casual or use the Teleportation Scroll whenever you get to it. The less time you waste on a challenge, the heigher the endpoint CPM will be.
- Learn to do the Hard Ending. Even if it takes thrice as long, the boost of +1.25x is worth basically double the time spent in the course.

### `📃` Triggers

`🧮` `/trigger` is a command that does not require any permissions to be used, making it the perfect alternative to custom commands of plugins for .mcfunction based projects. This map features:
- `adminPermission`: brings up a tellraw prompt to execute a command to verify that the player has admin permissions. Grants the `admin` tag which allows to interact with global settings.
- `preferenceProfile`: brings up a list of three profiles: Classic, Competitive, and Content Creation. The profiles change the personal preferences to adhere to different types of people.
- `viewSettings`: shows all of the global settings of the world. As most changes aren't notified of, might be useful to get to know the disposition.
- `viewProfile`: shows the profile of the closest player to the point of four blocks in front of the executer. If executed while looking directly down or if no players are in the viscinity, shows the profile of the executor. The profile consists of the placement, best CPM score, fastest run, most earned coins (and total coins).

---
### `📸` Screenshots
<img src="https://cdn.discordapp.com/attachments/879978618133024778/1084057071927967804/2023-03-11_14.03.25.png">
<img src="https://cdn.discordapp.com/attachments/879978618133024778/1084057072431276092/2023-03-11_14.04.19.png">
<img src="https://cdn.discordapp.com/attachments/879978618133024778/1084057072699719801/2023-03-11_14.04.31.png">

---

### *Fun* facts about this Parkour Warrior:
  - If there are no players currently in the course, the animated stages regenerate, e.g. change their states with a different timing.
  - You can sit on chairs and benches. Worth the mention.
  - The reason Cooldown (cd - var) exists is because the right click detection is so quick, in Casual you would skip multiple sections if you didn't click for a single tick. I didn't find that a problem at first, but when zooming through the course with Skip Section, you would sometimes bug out and be teleported to M1-1. I have fixed the issue, nevertheless, it can be mildly annoying to navigate casual without it, which is why the cooldown is set to 15 ticks (0.75s) by default to appease a more general audience. You can change that number with `/scoreboard players set cooldown var <value>`. Not to mention, but the reason this isn't featured in the server settings of the UI is because I... ran out of space.
  - Some assets for this map (e.g. the sidebar) were ripped out from yet another unreleased project - Battle Box: Finale, which was supposed to have every battle box AND ones you could build yourself. Unfortunately (but fortunatelly for me), not happening. And the code for the sidebar was written by a C# program I wrote. If you want to, I will share it. And the rotating Parkour Warrior mascot thingy is also inspired from Battle Box: Finale.
  - I never planned to release this. Or even make it. I woke up one morning, iirc December 23rd and decided to compose a texturepack for Parkour Warrior. After spending the morning doing that, and building a bit of the map, I realised I should probably not do this for someone else definitely has (I was right, but they didn't leave a link). But then I got sad over the wasted morning and it turned out to be an 80 day project. But hey, if anyone shouldn't be complaining, that's me.

### `📃` Credits
[The Noxcrew](https://noxcrew.com/), as the creators of what we all aspire.<br>
[Lighted Technology](https://youtube.com/c/LightedTechnology), as a person who is unbelieavably terrible at making good decisions.<br>
[Fruitless Gaming](https://www.youtube.com/@FruitlessGamingYT), for the idea of adding a No Checkpoint mode.<br>
[Waflarter](https://www.youtube.com/@Flarsp), for the idea of being notified in Run when there is 1 minute remaining to the filling out of the timer.

<h2 align="center"> And to all of you, who supported me no matter what.<br>❤️</h2>
<h6 align="center"> till next time</h6>

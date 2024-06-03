<div align="center">

<h1>Lost City - 2004Scape</h1>

[Website](https://2004scape.org) | [Discord](https://discord.2004scape.org) | [Rune-Server](https://www.rune-server.ee/runescape-development/rs2-server/projects/701698-lost-city-225-emulation.html)

**status: alpha, in-development**  
Contributors are welcome to help out!

**All server code has been written from scratch for this project.**  
**Jagex has never had any source code leaks.**
</div>

## Mission Statement

> [!IMPORTANT]
> Our goal is to authentically, accurately, and precisely emulate old RuneScape to our best knowledge. There are countless hours behind adding and quadruple-checking every bit of logic that goes into this.

Caches and clients are sourced from old PCs that played the game at a given time. That gives us the original maps, models, and NPC / Item / Scenery configurations. Then we can unpack that data into a readable and workable format based on what we've been able to observe Jagex doing, as outsiders.

The server side (engine, quests, combat, skills) was not preserved and that's what we're recreating here. The engine takes a lot of effort and is not perfected, but you should consider it our best interpretation of behaviors we can measure.

We try to take very little liberties when it comes to guessing, our sources are era-videos, era-screenshots, and RS3/OSRS/RSC.

Our content language of choice is a recreation of RuneScript: this gives us the same limitations, and the opportunity to recreate bugs out of the same circumstances. We don't simply see a bug and add it as an edge case, we have the script and engine work together to reproduce the exact reasons behind the bug.

## Credits

Thanks to all the current contributors, every PR you submit gets us closer and closer to feature completeness.

Thanks to these indirect or external contributors
- Kris: for all your help theorycrafting and testing, and to his sources as well for teaching him
- Walied: for your work on understanding the client assets (worked on cache formats)
- Dane: for your work on understanding the client (worked on client refactors)

If anyone is not listed here, whether that's intentional to remain anonymous or an oversight, thank you for your help.  
This type of project has been a long time coming and I hope to see the trend continue.

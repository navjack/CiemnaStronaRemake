# Ciemna Strona Remake

## Developer stuff

Data folder contains asset creation stuff, and the game folder contains the Adventure Game Studio project files.

Everything should be happy if you put it in "C:\ciemna strona"

Just clone this repo there or download the zip of it and put it there so you end up with

`"C:\ciemna strona\data\*.*"`

`"C:\ciemna strona\game\*.*"`

`"C:\ciemna strona\readme.md"`

**Check the [wiki](https://github.com/navjack/CiemnaStronaRemake/wiki)!**

### Ideas & Goals

* TRANSLATE TEXT
* Better file naming conventions
* Recreate the game's main path from start to finish with no side areas or items or "quests"
* The game should be beatable following the SANCTIFIED walkthrough
* After that we fill out all the extra items and rooms
* Dynamic music system using the multitrack files of the original music to create tension or have a “hot / cold” hint system
* Censor scenes for stream safe setting

### Asset creation

#### Game Engine

[Adventure Game Studio](https://www.adventuregamestudio.co.uk/)

#### 2D Graphics

I’ve (NavJack) been playing the game in emulator and taking screenshots or lossless APNG sequences and then by hand selecting the things I want and saving them. Each screen of the game is screenshotted twice at least to get a clean version of the room using a composite of the two to remove the player sprite. Animations are ripped by capturing the game with ShareX to an animated PNG file that I extract the frames of (export as image sequence) using VirtualDub2 while resizing them to 320x256 and then using DupeGuru to remove any 100% duplicate frames to save space and cut down on files. Every final imported into the engine asset is in true color, non-palletized, color depth with a DPI of 72 and in the PNG format. Intermediate assets I losslessly compress with ImageOptim to save about 50% disk space on average compared to a normal level 9 PNG compression save with XNView.

#### Audio / Music

There is really only music in this game that can reasonably captured and converted for use. The original MOD files and the mod files rendered out to multitracks are included in this repo. To save space I'm keeping the FLAC versions of the multitracks local and only keeping OGG versions on the repo.

### Thanks & Credits

Yell at me if you want to / don't want to be mentioned here

* Dumbass who decided to do this remake and follow through with it - NavJack
* Obsessively researching and mapping and exploring the game - MP83
* Savegame Editing Research - TangoBunny
* Moral Support - TrackZero_

#### oh boy

I guess I should let it be known that NavJack hasn't actually BEATEN the game himself yet. He's watched others do it. Heck, my brain can't even remember things well enough to actually claim to have any sort of intimate knowledge of the game. I know this game is important and deserves a working copy to exist in the world. I’m hoping to get most of the legwork done in setting up this project so those smarter than me can go in and actually code it competently. My ADHD for certain means that this project will get **very close** to being finished and I’ll have to hand over ownership to someone else for them to finish it.

# What?

Ciemna Strona is a Polish developed point and click adventure game for the Amiga computer system in 1997 by:

* Coder: Michał Speier (Michal Speier)
* Graphical Artist: Jarosław Figielski (Jaroslaw Figielski)
* Musician: Marcin Jaranowski
* Publisher: Diogenes

In its current state on the Amiga, it is unable to be completed. You must resort to modifications of the game to do so. But recently a group of people online were able to complete it and they have documented the ending and the steps required to get there. This will hopefully be the modernization effort that will be able to bring this game to a wider audience with a fully working version of the game.

More details and license information will be coming soon. (But in the meantime... consider everything here like public, like, I LITERALLY don’t give a fuck what you do with anything here and I will gladly accept any requests that are forward progress)

# five five 55 five five 55 five five 55 five five 55 five five 55 five five 55 SEVEN SEVEN SEVEN SEVEN FOUR FOUR FOUR FOUR

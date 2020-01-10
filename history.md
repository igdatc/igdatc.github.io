---
title: History
permalink: /history/
layout: default
---

We will try and keep this list of events up to date on on the website.


{% assign year = "" %}

{% for post in site.categories.events %}
{% assign postyear = post.date | date: "%Y" %}

{% if year != postyear %}
{% assign year = postyear %}
### {{ year }}
{% endif %}
*   {{ post.date | date: "%m/%d/%Y" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}

<br />

Of course, even before we had a website, we had events. Here is a list of events from the days before we had a website:

### 2011

*   Jan 27th: IGDA-TC Winter Social at the Chatterbox Pub in Highland Park

<a id="2010" name="2010"></a>

### 2010

*   Dec 2nd: Minnesota Electronic Theater 2010
*   Nov 23rd: Physics Sound Unleashed - Damian Kastbauer / [Lost Chocolate Lab](http://www.waste.org/lostchocolatelab/ "http://www.waste.org/lostchocolatelab/")
    *   [Audio Implementation Greats #6: Physics Audio (Part 1)](http://designingsound.org/2010/04/audio-implementation-greats-6-physics-audio-part-1/ "http://designingsound.org/2010/04/audio-implementation-greats-6-physics-audio-part-1/")
    *   [Audio Implementation Greats #7: Physics Audio (Part 2)](http://designingsound.org/2010/04/audio-implementation-greats-7-physics-audio-part-2/ "http://designingsound.org/2010/04/audio-implementation-greats-7-physics-audio-part-2/")
    *   [Audio Implementation Greats #8: Procedural Audio Now](http://designingsound.org/2010/09/audio-implementation-greats-8-procedural-audio-now/ "http://designingsound.org/2010/09/audio-implementation-greats-8-procedural-audio-now/")
    *   Member Project: [Tantrix3D](http://www.openmicgames.com/Tantrix3d/WebPlayer.html "http://www.openmicgames.com/Tantrix3d/WebPlayer.html") - Tori Kamal and Jesse Comb
*   Oct 27th: Robot Rampage 2 postmortem - Tyler Burks and friends from [Graveck](http://www.graveck.com/ "http://www.graveck.com/")
    *   Member Project: Treasure Island app book - Richard Monson-Haefel and Joe Weber of [FlyingWord, Inc](http://flyingword.com/ "http://flyingword.com/")
*   Sep 22nd: AI and PaperDoll Fashion Reaction - Baylor Wetzel, of [Shikigami Games](http://shikigamigames.com/ "http://shikigamigames.com/")
    *   Member Project: Zogger! - Peter Eckert of [Warp the Form](http://www.warptheform.com/ "http://www.warptheform.com/")
*   Aug 4th: Solaro - Andy Korth and Scott Lembcke of [Howling Moon Software](http://howlingmoonsoftware.com/ "http://howlingmoonsoftware.com/")
    *   Member Project: [Infiltration at Dusk](http://www.zachstronaut.com/posts/2010/07/08/javascript-video-game-infiltration.html "http://www.zachstronaut.com/posts/2010/07/08/javascript-video-game-infiltration.html") - Zach Johnson
*   Jun 23rd: Best of E3 roundtable and videos
*   May 25th: Optimizing 3D Engine, Art and Animation for Android phones - Robert Green and Ryan Foss - [Battery Powered Games](http://www.batterypoweredgames.com/ "http://www.batterypoweredgames.com/")
    *   Member Project: Music, FX and Voice for [Din's Curse](http://www.soldak.com/Dins-Curse/Overview.html "http://www.soldak.com/Dins-Curse/Overview.html") - [Tori Kamal](http://voice123.com/torikamal "http://voice123.com/torikamal")
*   Apr 29th: Unity for iPhone, iPad and web - Matthew Gravelle and Tyler Burks - [Graveck](http://www.graveck.com/ "http://www.graveck.com/")
    *   Member Project: Intro to publisher finance - Peter Eckert - [Brain Farm Entertainment](http://brainfarmentertainment.com/ "http://brainfarmentertainment.com/")
*   Mar 18th: XNA: current and future - Chris Williams and Zach Wendt ([IGDATC](http://igdatc.org "http://igdatc.org") and [Twin Cities XNA](http://www.meetup.com/TwinCitiesXNA/ "http://www.meetup.com/TwinCitiesXNA/"))
*   Feb 10th: Digital Publishing on DSiWare and WiiWare - Ken Patterson - CEO, [Big John Games](http://www.bigjohngames.com/ "http://www.bigjohngames.com/")
    *   Post-mortem: [Thorium Wars](http://www.thoriumwars.com/ "http://www.thoriumwars.com/") - Matt Heinzen - Development Lead, [Big John Games](http://www.bigjohngames.com/ "http://www.bigjohngames.com/")
    *   Member Project: Porting [Mouse House](http://www.bigjohngames.com/games/mouse-house/ "http://www.bigjohngames.com/games/mouse-house/") to WiiWare, intro to Wii Dev - Chris Dillman - Owner, [Plaid World Studios](http://www.plaidworld.com/ "http://www.plaidworld.com/")
*   Jan 26th: IGDA TC Winter Social at [The Chatterbox Pub](http://www.chatterboxpub.net/ "http://www.chatterboxpub.net/")in Highland Park.

<a id="2009" name="2009"></a>

### 2009

*   Dec 3rd: Minnesota Electronic Theater 2009
*   Nov 4th - Games for Android/gPhone by Robert Green, President [Battery Powered Games, LLC](http://www.batterypoweredgames.com/ "http://www.batterypoweredgames.com/")
    *   Member Project: Nate Pacyga, Studio Head [Try Catch Games](http://trycatchgames.com/ "http://trycatchgames.com/") - Recent iPhone and Flash games

*   Oct 6th - Educational Games - Mike Palmquist, Partner and Creative Director [Portage Interactive](http://www.portageinteractive.com/ "http://www.portageinteractive.com/")
    *   Member project: [voice](http://voice123.com/torikamal "http://voice123.com/torikamal"), [audio and music](http://www.torikamal.com/ "http://www.torikamal.com/") projects - Tori Kamal

*   Sept 3rd - GPU basics and state of the art from [SIGGRAPH 2009](http://old.siggraph.org/s2009/ "http://old.siggraph.org/s2009/") - Zach Wendt
    *   Member project: 4k Dungeon Romp - Cory Petosky
    *   Member project: Multiplayer Tower Defense - Nicholas Bilyk
*   August - No meeting: [SIGGRAPH 2009](http://www.siggraph.org/s2009/ "http://www.siggraph.org/s2009/")
*   July - No meeting: [Convergence 2009](http://www.convergence-con.org/ "http://www.convergence-con.org/")
*   June 4th - E3 Highlights and MMO design roundtables
*   May 7th - How to Develop Games the Monster Way - Richard Garcia, president of [Monster Games](http://www.mgiracing.com/ "http://www.mgiracing.com/")
    *   Member project: [ActionChess](http://chesstris.com/ "http://chesstris.com/") for iPhone - Martin Grider
*   April 8th - [Dead Space](http://deadspace.ea.com/ "http://deadspace.ea.com/") â€“ Creature creation, from Concept to Gameplay - Sandra Voelker [Electronic Arts](http://www.ea.com/ "http://www.ea.com/")
    *   Member project: GDC recap - various.
*   March 5th - Indie game dev and [Arcane-FX](http://arcane-fx.com/ "http://arcane-fx.com/") miduleware - Jeff Faust [Faust Logic](http://faustlogic.com/ "http://faustlogic.com/")
    *   Member project: Recent projects and intro to [Unity](http://unity3d.com/ "http://unity3d.com/") - Matt Gravelle of [Graveck](http://www.graveck.com/ "http://www.graveck.com/")
*   Feb 5th - Making and Selling iPhone Games - Andy Korth, Scott Lembcke of [Howling Moon Software](http://howlingmoonsoftware.com/index.shtml "http://howlingmoonsoftware.com/index.shtml") and Chris Dillman of [Plaid World Studios](http://www.plaidworld.com/ "http://www.plaidworld.com/")
    *   Member Project: Crysis mod and into to Sandbox2 editor - [Jesse Comb](http://jalexcomb.wordpress.com/ "http://jalexcomb.wordpress.com/")

<a id="2008" name="2008"></a>

### 2008

*   Dec 11th - Holiday Party at [PUNY](http://punyentertainment.com/ "http://punyentertainment.com/")
*   Nov 6th: Agile Development for Games - Jesse Crafts-Finch - [Johnson Simulation Center](http://dev.johnsonsimcenter.com/index.php "http://dev.johnsonsimcenter.com/index.php")
    *   Member Project: [Mouse House](http://plaidworld.com/games_mousehouse.php "http://plaidworld.com/games_mousehouse.php") for iPhone - Chris Dillman - [Plaid World Studios](http://www.plaidworld.com/ "http://www.plaidworld.com/")
*   Sept 2nd: Deconstructing Sandbox Games - Zach Wendt
    *   Member Project: Interactive Fiction with Inform, Game Dev at Carleton - [John Mawhorter](http://griuley.res.carleton.edu/~mawhortn/ "http://griuley.res.carleton.edu/~mawhortn/")
*   Aug 7th: Member Project Night
    *   Interactive Visualization - Ryan Foss - [BAE Systems](http://www.baesystems.com/ "http://www.baesystems.com/")
    *   ScribBall for Mac and iPhone - Andy Korth, Scott Lembcke - [Howling Moon Software](http://howlingmoonsoftware.com/index.shtml "http://howlingmoonsoftware.com/index.shtml")
    *   Training and Educational games - Jesse Crafts-Finch, Brandon Schapekahm - [Johnson Simulation Center](http://dev.johnsonsimcenter.com/index.php "http://dev.johnsonsimcenter.com/index.php")
    *   Mouse House for iPhone - Chris Dillman - [Plaid World Studios](http://www.plaidworld.com/ "http://www.plaidworld.com/")
*   May 1st: Indie and DS development - Ken Patterson, Matt Heinzen and Don Patterson - [Big John Games](http://www.bigjohngames.com/ "http://www.bigjohngames.com/")
*   April 3rd: IMGDC Recap - roundtable session.
*   March 6th: Commercial Flash Games - Seth Walker and Alexis Mason - [Ham in the Fridge](http://www.haminthefridge.com/ "http://www.haminthefridge.com/")
*   February 7th: Camera-Controlled Motion Games - Yuichiro Tanabe, Cory Petosky, and Pete Border - [Puny Entertainment](http://punyentertainment.com/ "http://punyentertainment.com/")
*   January 3rd: Video and Traditional Board Games - Martin Grider [Go-Tetris](http://chesstris.com/ "http://chesstris.com/") and [Darrell Hardy](http://darrellhardy.com/ "http://darrellhardy.com/")

<a id="2007" name="2007"></a>

### 2007

*   December 6th: Holiday Social at [PUNY](http://punyentertainment.com/ "http://punyentertainment.com/")
*   November 1st: Microsoft XNA Introduction and Hands-On - Zach Wendt

<a id="2006" name="2006"></a>

### 2006

*   December 13th: Wii Demo Spotlighting ExciteTruck - Chad Jasper
*   October 11th: Organizational Meeting - Gary
*   August: No August Meeting
*   June 14th: [The Fun Factor, Machine Learning, and Gameplay Metrics](http://www.aaai.org/Conferences/AIIDE/2006/aiide06speakers.php "http://www.aaai.org/Conferences/AIIDE/2006/aiide06speakers.php") - Ben Geisler
*   April 12th: [GDC 2006](http://gdconf.com "http://gdconf.com") Wrap & [TikiWiki](http://tikiwiki.org "http://tikiwiki.org") Introduction - GDC2006 Attendees
*   February 8th: Education and Games Panel

<a id="2005" name="2005"></a>

### 2005

*   December 14th: Digital Game Distribution - Wes Pederson
*   October 12th: Tablet Development, and MN Game Jam 1 Games - Gary Dahl
*   August 10th: Sound Effect Basics for Games - Damian Kastbauer [Summary](http://www.waste.org/lostchocolatelab/IGDA/LCLPresentationSummary.pdf "http://www.waste.org/lostchocolatelab/IGDA/LCLPresentationSummary.pdf") - [Slides](http://www.waste.org/lostchocolatelab/IGDA/LCLPresentationSlides.pdf "http://www.waste.org/lostchocolatelab/IGDA/LCLPresentationSlides.pdf")
*   June 15th: Flash Game Development - Andreas Heim
*   April 13th: GDC and MN Game Jam 0 Wrap-Up - Group
*   March 9th: Teaching Journalism with [Never Winter Nights](http://nwn.bioware.com/ "http://nwn.bioware.com/") - Matt Taylor
*   February 9th: Dynamic Simulation at Pixar Animation Studios - David Baraff

<a id="2004" name="2004"></a>

### 2004

*   November 11th: [Game Maker](http://gamemaker.nl "http://gamemaker.nl") - Gary Dahl
*   October 12th: [The Video Game Revolution](http://www.pbs.org/kcts/videogamerevolution/ "http://www.pbs.org/kcts/videogamerevolution/") - PBS
*   September 14th: [Scrolling Game Development Kit](http://gamedev.sourceforge.net "http://gamedev.sourceforge.net") - Benjamin Marty
*   August 10th: [Blender](http://blender.org "http://blender.org") - Kent Mein, Joshua Seaver
*   July 13th: Pen&Paper vs Computer Game Design - Christopher Weiss


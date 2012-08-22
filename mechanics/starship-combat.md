# Starship Combat - Basic Mechanics

Starships have five main stats that are used to govern how they function.

## Size

Starships range in size from tiny to gigantic, each with a size rating.

-	**Gigantic** - *Rating: 5*. These ships are huge, think your traditional 
	capital ship, like a Super Star Destroyer (2-19km long), or maybe a Guild
	Heighliner (20km long). Just big.

-	**Huge** - *Rating: 4*. These are slightly smaller ships. Somewhere
	along the lines of a traditional Imperial-II Star Destroyer (1.5km),
	or the Alliance Cruisers seen in Firefly (1.2km long, 1.5km high).

-	**Medium** - *Rating: 3*. The average transport ship, sometimes used
	as command ships for outposts or small militias. Akin to the Galaxy-Class
	and Sovereign-Class ship from Star Trek (think the newer, larger capitals
	in Starfleet), Correlian Corvettes (the Tantive IV) from Star Wars, and
	the Galactica (and most other Battlestars).

-	**Small** - *Rating: 2*. Your standard freighter. These are the typical
	ships held by people in transportation businesses. The *Serenity* from
	Firefly, the *Millennium Falcon*, ships big enough for a small crew and a
	small cargo. The *Delta Flyer* is also a freighter.

-	**Tiny** - *Rating: 1*. Fighters and shuttles. Big enough for one to six
	people inside, without much in the way of supplies. Mostly meant to
	act as smaller support in battle. Think Vipers from Galactica, X-Wings
	from Star Wars, shuttlecraft and Danube-Class things from Star Trek.

## Shields

The shield rating of a ship determines how many hit points it has before it
starts taking hull damage. Just like most shields work. Huh...

Ships can have anywhere between ((0-50) x Size Rating) shield points. Yeah,
the smaller the ship, the smaller number of shield points possessed.

## Hull

The number of hull points the ship has. At 50% their total hull points, the
ship is considered disabled, and cannot perform any action at all.

Ships can have a range of ((1 - 10) * Size Rating) hull points. With shields,
smaller ships have a smaller amount of hull points.

## Weapons

A ship can have anywhere from ((0 - 5) ^ Size Rating) weapons stations. The
range of these weapons is (100 x Size Rating) meters, and each weapon can
deal damage of ((0 - 2) * Size Rating) points (these points are analogous with
shield and hull points).

When firing a weapon, the DC is (Distance to Target / (10 * Target's Size
Rating)). Bigger ships are easier to hit, smaller ones, less so.

Because I don't have abilities/skills figured out yet, there isn't really a
modifier that can be used (maybe in the future?). I would roll a D20, no
natural ones/twenties, just hit or miss.

## Speed

How far a ship can travel in one turn (the length of a turn has yet to be
determined). Ships can travel somewhere between (0 - 100) meters per turn.

Yeah, size rating isn't used in this one because I feel that larger ships have
large engines. Plus the speed is different for each ship. Sure, some capitals
can move 100m, but most will probably move slower, because they're bigger and
don't have the engines to compensate for their size...

## Starship Encounters

Encounters use a turned-based system. In one turn every station on a ship
(from comm (telling people you need backup, or communicating with another
ship), nav (moving your ship to somewhere else, either bringing you closer
to your enemies or farther from them), or weapons (you know, for shooting at
your enemies)) may act. Each station needs a person manning it (you can't have
one person controlling all of the weapons, you need four people for four
weapons, plus another to pilot the ship at least).
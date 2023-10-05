
# 15. Starships
Starstrider has an entirely unique system for Starships, their creation and combat rules separate from normal most games like SW5e. There is a more streamlined combat option for small groups, or groups who do not wish to spend a lot of time on space combat later on. This system runs almost entirely like ground combat.

When reading a ship statistics remember the sizes and values are Starship scale. So if something does 1d6 damage, that is damage to a Starship. Against a ground based target it is x10 (1d6x100) this is the same for the Hull Points, Shield Rating, Damage Reduction. In general it is virtually impossible to damage anything larger than Large ships with ground based weapons.

## Starship Design

> Setting Designer:
> I have spent a lot of time pouring over resources for this section as I consider it to be one of the most critical in the game to get right. In the end I wanted to use something that made sense so I altered a couple of different systems. 


### Building A Starship
Building a starship is an endeavor it takes a long time in game, but not in the real world time for the Gamemaster. 

You start by making the AI. The AI is attached to the ship it is how a Starship gets Ability Points.

1. Place AI Ability Scores
2. Pick a size for the ship giving you the Upgrades, and AC Adj
3. Pick a level for the ship giving you SP, and the AI capabilities
4. Pick a Class of Shipgiving you the Hardpoints for weapons, Hull Points, Crew Min/Max, the Turn rate, and how many SP that cost
5. Use the remianing SP to pick the parts needed
6. Record Derived Statistics
   1. Armor Class = 10 + AI Ability + AI Proficiency + Size Category
   2. Reflex = AI Ability + AI Proficiency
   3. Attacks = If the AI will attack, it can only attack so many times based on its capabilities
      1. AI Ability + AI Proficiency


#### Step 1. Create the AI
See AI Section

#### Step 2. Pick ships Size and Class of Starship

##### Size Chart
| Class               | Grid  | SizeMod | CrewInc | Turn | Base AC | MaxDex | Upgrades    | HD           | Cost  | SI  | Hardpoints | Max Weapons | Stations                                               |
| ------------------- | ----- | ------- | ------- | ---- | ------- | ------ | ----------- | ------------ | ----- | --- | ---------- | ----------- | ------------------------------------------------------ |
| *Drones*            | .5x.5 | 1       | 0       | 0    | 5       | 10     | 0           | 6 (2d5)      | 3k    | 2   | 1          | 1           | None                                                   |
| *Small*             | 1x1   | 2       | 1       | 1    | .       | 10     | -1+ConMod   | .            | .     | .   | .          | 1           | .                                                      |
| Light Starfighter   | .     | .       | .       | .    | 7       | .      | .           | 8 (2d6)      | 6.5k  | 2   | 1          | .           | 1 Pilot, 1 co-pilot                                    |
| Light Shuttle       | .     | .       | .       | .    | 6       | .      | .           | 8 (2d6)      | 5.5k  | 2   | 1          | .           | 1 pilot, 1 co-pilot                                    |
| *Medium*            | 1x1   | 3       | 5       | 2    | .       | 10     | 3+ConMod    | .            | .     | .   | .          | 2           | .                                                      |
| Shuttle             | .     | .       | .       | .    | 8       | .      | .           | 10 (2d8)     | 8.5k  | 2   | 1          | .           | 1 gunner & 1 pilot(single) or 1 pilot, 1 co-pilot      |
| Starfighter         | .     | .       | .       | .    | 10      | .      | .           | 10 (2d8)     | 10k   | 2   | 2          | .           | 1 pilot (single) or 1 pilot & 1 gunner                 |
| Interceptor         | .     | .       | .       | .    | 9       | .      | .           | 15 (3d8)     | 14.5k | 3   | 3          | .           | 1 pilot (single) or 1 pilot, 1 co-pilot & 2 gunner     |
| *Large*             | 2x2   | 4       | 100     | 3    | .       | 10     | 3+2*ConMod  | .            | .     | .   | .          | 4           | .                                                      |
| Corvette            | .     | .       | .       | .    | 9       | .      | .           | 30 (3d10)    | 18k   | 3   | 4          | .           | 1 pilot, 1 technician, 2 gunner, 1 optional            |
| Gunship             | .     | .       | .       | .    | 10      | .      | .           | 40 (4d10)    | 22k   | 4   | 6          | .           | 1 pilot, 1 techician, 4 gunner                         |
| Heavy Freighter     | .     | .       | .       | .    | 10      | .      | .           | 60 (6d10)    | 30k   | 6   | 6          | .           | 1 pilot, 1 technician, 2 gunner, 1 optional            |
| *Huge*              | 3x3   | 5       | 150     | 4    | .       | 3      | 6+3*ConMod  | .            | .     | .   | .          | 6           | .                                                      |
| Heavy Gunship       | .     | .       | .       | .    | 13      | .      | .           | 112 (16d12)  | 250k  | 16  | 20         | .           | 1 Captain, 1 pilot, 1 technician, 6 gunner, 1 optional |
| Heavy Frigate       | .     | .       | .       | .    | 13      | .      | .           | 119 (17d12)  | 240k  | 17  | 16         | .           | 1 Captain, 1 pilot, 1 technician, 4 gunner, 1 optional |
| Starcruiser         | .     | .       | .       | .    | 12      | .      | .           | 105 (15d12)  | 210k  | 15  | 16         | .           | 1 captain, 1 pilot, 1 technician, 4 gunner             |
| Trade Carrier       | .     | .       | .       | .    | 12      | .      | .           | 91 (13d12)   | 195k  | 13  | 14         | .           | 1 captain, 1 pilot, 1 technician, 3 gunner             |
| *Gargantuan*        | 4x4   | 6       | 250     | 5    | .       | 2      | 10+4*ConMod | .            | .     | .   | .          | 8           | .                                                      |
| Battle Cruiser      | .     | .       | .       | .    | 15      | .      | .           | 198 (18d20)  | 670k  | 17  | 28         | .           | 1 captain, 1 pilot, 2 technician, 6 gunner, 1 optional |
| Star Carrier        | .     | .       | .       | .    | 16      | .      | .           | 176 (16d20)  | 630k  | 18  | 14         | .           | 1 captain, 1 pilot, 4 technician, 4 gunner, 1 optional |
| Heavy Trade Carrier | .     | .       | .       | .    | 15      | .      | .           | 187 (17d20)  | 625k  | 16  | 20         | .           | 1 captain, 1 pilot, 2 technician, 4 gunner, 1 optional |
| *Titanic*           | 5x5   | 7       | 500     | 6    | .       | 0      | 15+5*ConMod | .            | .     | .   | .          | 10          | .                                                      |
| City Ship           | .     | .       | .       | .    | 22      | .      | .           | 600 (10d100) | 1.8m  | 20  | 40         | .           | 1 captain, 2 pilot, 2 technician, 6 gunner, 2 optional |
| Star Port           | .     | .       | .       | .    | 23      | .      | .           | 720 (12d100) | 2.25m | 24  | 48         | .           | 1 captain, 2 technician, 8 gunner, 2 optional          |

* Crew Max is determined by living quarters. All sizes of ships have an increment for crew, each Living Quarters, Barracks, or Luxury Living Quarters

- Grid: This is a basic representation of how much space a ship takes up on a grid. Much like creatures this is fairly fluid and is a guideline
- SizeMod: This is used to calculate a number of SP costs
- CrewInc: This is the Crew Increment. Each Quarters on a ship will increment the crew by this number and the base crew it will hold is this number
- Turn: This is the number of Hexes needed to be moved before a ship can turn 90 degrees, larger ships take longer to turn
- Base AC: This is the Base Armor Class for the hull
- MaxDex: This is the Maximum Dexterity bonus for the Ship's AC (this comes from the Pilot)
- Upgrades: This is the number of Upgrade slots a ship has
- HD: This is the Hull Dice a ship has (think of it as Hit Point)
- Cost: This is the cost of a ship average in Chits in this size and hull
- SI: Structual Integrity, this represents the Life of a ship if this goes to 0 the ship is gone
- Hardpoints: This is the number of weapon hardpoints on a ship, a ship can never use more hardpoints than it has
- Max Weapons: Regardless of Hardpoints a ship can only have so many weapons online at any one time, it can carry more but it can never have more than that online.
- Stations: Each hull style has a maximum number of action stations allowed for operation.



Starship Scales

| Size       | Length ft  | Displacement   | Cargo Capacity |
| ---------- | ---------- | -------------- | -------------- |
| Titanic    | 15,000+    | 1,500,000 tons | 225,000 tons   |
| Gargantuan | 2000-15000 | 500,000 tons   | 75,000 tons    |
| Huge       | 800-2000   | 150,000 tons   | 22,000 tons    |
| Large      | 300-800    | 200,000lbs     | 30,000 lbs     |
| Medium     | 120-300    | 50,000lbs      | 7,500 lbs      |
| Small      | 60-120     | 25,000lbs      | 4,000 lbs      |
| Drone      | 20-60      | 10,000lbs      | 1,500 lbs      |

> Ship sizes
> Why Drone and not Tiny?
> Because ships have a much largwe Scale.
> A Drone takes up a square that is 25 square feet. Or 5 hexes making it a Titanic Creature. So the Scale STARTS at Titanic
> Drone = Titanic, 5x5 Hexes
> Small, Medium =  10x10 Hexes
> Large = 20x0 Hexes
> Huge = 30x30 Hexes
> Gargantuan = 40x40 square
> Titanic = 50x50 square
>
> This means in player scale a Titanic sized ship is 62,500 sq feet in size on the grid, its the size of a very large building. Almost 12 square miles. So yeah ... I changed the names a bit. 


* SP are "Ship Points". `1 SP = RoundDown(1000 / 1000)` so if something cost ⬢1250 it is 1 SP, this is an alternate system to Chits for aquiring parts for a ship as it levels up. In Astra Genesis we tend to use Milestone XP and forcing players to come up with ⬢26,000,000 (that would be 260k chits for reference) is a bit crazy when they could just "figure out" how to use the space better also works great for trading in "old" parts as a Shipyard or Star Port. They can swap parts in get some SP, then pay some Chits. SP is quite simply easier math do not make this hard. 

#### Step 3. Power Core
The power core is the most important system on a ship, as it provides power to every other system. The table below lists the ship size each core is designed for, as well as the Power it provides and its cost. Each Large and smaller ship has room for only a single power core by default, but Medium and Large starships can be fitted with an extra power core housing. Huge starships can have up to two power cores, Gargantuan starships can have up to three, and Titanic starships can have up to four. Though some ships are exceptions to this standard, they are rare in design. A power core typically has a backup battery system for use in emergencies that can provide limited power,enough for life support, gravity, and comms, but no other systems for 2d6 days.

| Power Core           | Min Size | Max Size | Output | Reliability | TL   | SP   |
| :------------------- | :------- | :------- | :----- | :---------- | :--- | :--- |
| SyndiCorp I          | -        | D        | 50     | 1           | 12   | 4    |
| SyndiCorp II         | -        | D        | 70     | 1+          | 13   | 6    |
| SyndiCorp III        | -        | D        | 80     | 2           | 14   | 8    |
| Daelin Corp. I       | -        | S        | 75     | 2           | 12   | 7    |
| LCI Inc. T-1         | -        | S        | 90     | 2           | 13   | 9    |
| LCI Inc. T-2         | -        | S        | 120    | 2           | 14   | 12   |
| LCI Inc. T-3         | -        | S        | 140    | 2+          | 14   | 14   |
| LCI Inc. T-4         | -        | M        | 100    | 2           | 12   | 10   |
| Daelin Corp. II      | -        | M        | 130    | 3           | 13   | 13   |
| LCI Inc. T-4.5       | -        | M        | 150    | 3           | 14   | 15   |
| LCI Inc. T-5         | -        | M        | 175    | 3           | 14   | 17   |
| LCI Inc. T-5.5       | -        | M        | 200    | 3+          | 14   | 20   |
| Daelin Corp. III     | S        | L        | 150    | 3           | 13   | 15   |
| Daelin Corp. Maximum | S        | L        | 200    | 3           | 14   | 20   |
| LCI Inc. T-6         | S        | L        | 250    | 3+          | 14   | 25   |
| LCI Inc. T-7         | S        | L        | 300    | 4           | 14   | 30   |
| SyndiCorp IV         | M        | H        | 150    | 4           | 14   | 15   |
| SyndiCorp V          | M        | H        | 200    | 4           | 14   | 20   |
| SyndiCorp VI         | M        | H        | 300    | 4+          | 14   | 30   |
| Drake Ind. A         | L        | G        | 300    | 4           | 14   | 30   |
| Drake Ind. B         | L        | G        | 400    | 4           | 14   | 40   |
| Drake Ind.T          | H        | T        | 500    | 4           | 14   | 50   |

- Min Size. This is the minimum size a ship must be to install this
- Max Size. This is the maximum size a ship can be to install this
- Output. This is the power output for this system a ship can never be using more power than it has
- Reliability. This is the reliability of this system (see System Damage)
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost


#### Step 4. Sublight
Ships rely on conventional sublight engines to move between locations in a system, to navigate the reaches of the 'Verse once they arrive there, to explore, and to engage in combat They are designed for ships of a specific size (specified in the Size column of the table below), and they can’t be installed in a ship of an incorrect size.

Sublight engines are also used when landing on and taking off from a planet. Large and smaller Starships generally have little difficulty landing on and taking off from a planet with low gravity or standard gravity (unless there are atmospheric conditions such as high winds or storms). The GM determines whether or not a starship’s pilot must attempt a Piloting check to land a starship with a speed lower than 8 on a planet with high gravity, with failure meaning it might crash. Due to their sheer size, Huge and larger starships can’t land on planets, and must use shuttles or other means to ferry crew and goods to a planet and back.

| Sublight       | Speed | Power | Max Size | Reliability | Maneuverability | TL   | SP   |
| :------------- | :---- | :---- | :------- | :---------- | --------------- | :--- | :--- |
| **Chemical**   | -     | -     | -        | -           | -               | -    | -    |
| RCS-1          | 6     | 20    | D        | 1           | +0              | 12   | 3    |
| RCS-2          | 8     | 25    | D        | 1+          | +1              | 12   | 4    |
| **Nuclear**    | -     | -     | -        | -           | -               | -    | -    |
| NRT-1          | 10    | 30    | D        | 2           | +2              | 12   | 5    |
| NRT-2          | 6     | 30    | S        | 2           | +2              | 12   | 3    |
| NRT-3          | 4     | 40    | M        | 2           | +2              | 12   | 2    |
| FTD-1          | 12    | 35    | D        | 2+          | +2              | 13   | 6    |
| FTD-2          | 8     | 40    | S        | 2+          | +2              | 13   | 4    |
| FTD-3          | 6     | 50    | M        | 2+          | +2              | 13   | 3    |
| FTD-4          | 4     | 60    | L        | 2+          | +2              | 13   | 4    |
| FTD-4a         | 6     | 80    | L        | 2+          | +2              | 13   | 6    |
| FTD-5          | 4     | 80    | H        | 2+          | +2              | 13   | 4    |
| FTD-5a         | 6     | 120   | H        | 2+          | +2              | 13   | 6    |
| FTD-6          | 4     | 120   | G        | 2+          | +2              | 13   | 8    |
| FTD-6a         | 6     | 180   | G        | 2+          | +2              | 13   | 12   |
| FTD-6b         | 4     | 200   | T        | 2+          | +2              | 13   | 8    |
| **Ion**        | -     | -     | -        | -           | -               | -    | -    |
| ITD-1          | 14    | 40    | D        | 3           | +3              | 14   | 7    |
| ITD-2          | 10    | 50    | S        | 3           | +3              | 14   | 5    |
| ITD-3          | 8     | 60    | M        | 3           | +3              | 14   | 4    |
| ITD-3a         | 10    | 70    | M        | 3+          | +3              | 14   | 5    |
| ITD-4          | 8     | 100   | L        | 3           | +3              | 14   | 8    |
| ITD-5          | 8     | 140   | H        | 3           | +3              | 14   | 8    |
| ITD-6          | 8     | 240   | G        | 3           | +3              | 14   | 16   |
| ITD-7          | 6     | 300   | T        | 3           | +3              | 14   | 12   |
| **Antimatter** | -     | -     | -        | -           | -               | -    | -    |
| DAT-A          | 12    | 60    | S        | 4           | +4              | 15   | 6    |
| DAT-B          | 12    | 80    | M        | 4           | +4              | 15   | 6    |
| DAT-C          | 10    | 120   | L        | 4           | +4              | 15   | 10   |
| DAT-D          | 10    | 160   | H        | 4           | +4              | 15   | 10   |
| DAT-E          | 8     | 400   | T        | 4           | +4              | 15   | 16   |

- Speed. This is how fast in Hexes the ship can move in a move action
- Power. This is how much power this system uses
- Max Size. This is the maximum size a ship can be to install this
- Reliability. This is the reliability of this system (see System Damage)
- Maneuverability. This is how maneuverable this system is, this will add to the Ships Armor Class
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

#### Step 5. Armor
Armor protects a ship from some of the damage from weapons. Armor’s cost depends on the bonus it grants and the ship’s size category (for the purpose of this calculation, Tiny = 1, Small = 2, Medium = 3, Large = 4, etc.). Armor is a passive system and does not require any Power to remain functional. It provides protection primarily through mass, which can affect a ship’s maneuverability (making it harder to turn) and make it easier for opponents to hit the ship (thus lowering the AC of the ship) these effects are listed in the Special column of the table below.

| Armor | Damage Reduction | AC Adjustment | Turn    | SP         |
| :---- | :--------------- | :------------ | ------- | :--------- |
| Mk 1  | 1                | +1            |         | 1*SizeMod  |
| Mk 2  | 2                | +1            |         | 2*SizeMod  |
| Mk 3  | 3                | +2            |         | 3*SizeMod  |
| Mk 4  | 4                | +3            | +1 Turn | 5*SizeMod  |
| Mk 5  | 5                | +3            | +1 Turn | 7*SizeMod  |
| Mk 6  | 6                | +4            | +1 Turn | 9*SizeMod  |
| Mk 7  | 7                | +4            | +2 Turn | 12*SizeMod |
| Mk 8  | 8                | +5            | +2 Turn | 15*SizeMod |
| Mk 9  | 9                | +5            | +2 Turn | 18*SizeMod |
| Mk 10 | 10               | +6            | +3 Turn | 21*SizeMod |
| Mk 11 | 11               | +6            | +3 Turn | 25*SizeMod |
| Mk 12 | 12               | +7            | +3 Turn | 30*SizeMod |
| Mk 13 | 13               | +7            | +4 Turn | 35*SizeMod |
| Mk 14 | 14               | +8            | +4 Turn | 40*SizeMod |
| Mk 15 | 15               | +8            | +4 Turn | 45*SizeMod |

- Damage Reduction. This is the amount of damage reduced from weapons that strike the hull
- AC Adjustment. This is the Bonus to AC this armor plating provides
- Turn. This is how the extra weight of this armor affects turn speed
- SP. This is the Ship Points it will cost

#### Step 6. Computer Core
The Central Computer of the ship controls how high level the AI on board can be. Ships do not go up in level but their AI's do. A better computer also grants a bonus to the Astrogration checks to calculate jumps.

| Central Computer | Max Level | Navcomputer Bonus | Power | Reliability | TL   | SP   |
| :--------------- | :-------- | :---------------- | :---- | :---------- | :--- | :--- |
| Basic Node       | 1 (1)     | 1                 | 0     | 1           | 12   | 0    |
| Silicon          | 2 (1)     | 1                 | 5     | 1           | 12   | 1    |
| Di-Silicon       | 3 (1)     | 1                 | 10    | 1+          | 13   | 2    |
| Tri-Silicon      | 4 (1)     | 1                 | 10    | 1+          | 13   | 4    |
| Tetra-Silicon    | 5 (2)     | 2                 | 15    | 2           | 13   | 8    |
| Quantum          | 6  (2)    | 2                 | 15    | 2           | 13   | 10   |
| Di-Quantum       | 7  (2)    | 2                 | 15    | 2           | 13   | 15   |
| Tri-Quantum      | 8  (2)    | 2                 | 15    | 2           | 13   | 20   |
| Tetra-Quantum    | 9   (3)   | 3                 | 15    | 2           | 13   | 25   |
| Penta-Quantum    | 10  (3)   | 3                 | 15    | 2+          | 13   | 30   |
| Verite           | 11  (3)   | 3                 | 20    | 3           | 14   | 35   |
| Di-Verite        | 12  (3)   | 3                 | 20    | 3           | 14   | 40   |
| Tri-Verite       | 13  (4)   | 4                 | 20    | 3           | 14   | 45   |
| Tetra-Verite     | 14  (4)   | 4                 | 20    | 3           | 14   | 50   |
| Penta-Verite     | 15  (4)   | 4                 | 20    | 2+          | 14   | 55   |
| Nexine           | 16  (4)   | 4                 | 25    | 4           | 14   | 60   |
| Di-Nexine        | 17  (5)   | 5                 | 25    | 4           | 14   | 65   |
| Tri-Nexine       | 18  (5)   | 5                 | 25    | 4           | 14   | 70   |
| Tetra-Nexine     | 19  (5)   | 5                 | 25    | 4           | 14   | 75   |
| Penta-Nexine     | 20  (5)   | 5                 | 25    | 3+          | 14   | 80   |
| Isolinear        | 21  (6)   | 6                 | 30    | 4           | 14   | 85   |
| Di-Isolinear     | 22  (6)   | 6                 | 30    | 4           | 14   | 90   |
| Tri-Isolinear    | 23  (6)   | 6                 | 30    | 4           | 14   | 95   |
| Tetra-Isolinear  | 24  (6)   | 6                 | 30    | 4           | 14   | 100  |
| Penta-Isolinear  | 25  (7)   | 7                 | 30    | 4+          | 14   | 105  |
| Prismerite       | 26  (7)   | 7                 | 35    | 5           | 15   | 110  |
| Di-Prismerite    | 27  (7)   | 7                 | 35    | 5           | 15   | 115  |
| Tri-Prismerite   | 28  (7)   | 7                 | 35    | 5           | 15   | 120  |
| Tetra-Prismerite | 29  (8)   | 8                 | 35    | 5+          | 15   | 125  |
| Penta-Prismerite | 30  (8)   | 8                 | 40    | 6           | 15   | 130  |

- Max Level. This is the Max level for the AI attached to the ship for a Free AI. The number in parenthesis is the Tier Maximum for a Tethered AI (see Artificial Intelligence)
- Navcomputer Bonus. This is the bonus to Astrogation and Astrophysics checks for Jump calculations from the computer.
- Power. This is how much power this system uses
- Reliability. This is the reliability of this system (see System Damage)
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

#### Step 7. Jump Drive
| Jump Drive     | Jump Rating | Power                    | Min Size | Max Size | Reliability | TL   | SP         |
| :------------- | :---------- | :----------------------- | :------- | :------- | :---------- | :--- | :--------- |
| Mk 1           | 1           | 50                       | -        | -        | 1           | 13   | 1*SizeMod  |
| Mk 2           | 2           | 75                       | -        | -        | 1+          | 14   | 2*SizeMod  |
| Mk 3           | 3           | 100                      | -        | G        | 2           | 14   | 5*SizeMod  |
| Mk 4           | 4           | 150                      | -        | H        | 2+          | 14   | 10*SizeMod |
| Mk 5           | 5           | 175                      | -        | L        | 3           | 14   | 15*SizeMod |
| Mk 6           | 6           | 200                      | -        | M        | 3+          | 14   | 20*SizeMod |
| Mk 4.5         | 4           | 300                      | G        | T        | 3           | 14   | 25*SizeMod |
| Celestar Drive | 7           | 10 x Size Category + 100 | M        | H        | 4           | 15   | 10*SizeMod |
| Drakneri Drive | 7           | 25 x Size Category + 100 | S        | G        | 4+          | 15   | 25*SizeMod |
| Warp Drive     | 8           | 20 x Size Category + 100 | S        | H        | 5           | 16   | 20*SizeMod |
| Quantum Drive  | 9           | 15 x Size Category + 100 | S        | L        | 5+          | 17   | 15*SizeMod |
| Gravity Drive  | 10          | 30 x Size Category + 100 | S        | T        | 6           | 18   | 30*SizeMod |

- Jump Rating. How many Parsecs can be jumped in a single jump. All Jump drives recharge at a rate of 1 Parsec/Hour
- Power. This is the power used to perform a Jump (it also uses a unit of fuel)
- Min Size. This is the minimum size a ship must be to install this
- Max Size. This is the maximum size a ship can be to install this
- Reliability. This is the reliability of this system (see System Damage)
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

##### FTL Drives
There are some species in the galaxy (The Kriost for example). That use an FTL drive (commonly called a Stardrive) and not a Jump Drive. They are rated at LY/Hour and travel at a constant rate. How they do this varies species to species but most commonly they channel power from the reactor to Warp space around the ship so it can be propelled faster than light. This is significantly slower than a Jump Drive in most cases but it is a consistent rate of travel and the ship never needs to stop.

| Stardrive           | Rating (Ly/Hour) | Power | Min Size | Max Size | Reliability | TL  | SP         |
| ------------------- | ---------------- | ----- | -------- | -------- | ----------- | --- | ---------- |
| Kriost Stardrive    | 2                | 200   | M        | T        | 6           | 16  | 10*SizeMod |
| Illithari Stardrive | 1                | 100   | S        | G        | 5           | 15  | 10*SizeMod |
| Mark I Stardrive    | .25              | 25    | .        | .        | 1           | 14  | 3*SizeMod  |
| Mark II Stardrive   | .5               | 50    | S        | L        | 2           | 14  | 5*SizeMod  |
| Mark III Stardrive  | 1                | 75    | M        | H        | 3           | 14  | 10*SizeMod |

- Rating. How many Light years can be traveled in a single hour of use.
- Power. This is the power used when the drive is engaged (it also uses a unit of fuel/hour)
- Min Size. This is the minimum size a ship must be to install this
- Max Size. This is the maximum size a ship can be to install this
- Reliability. This is the reliability of this system (see System Damage)
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

#### Step 8. Sensors
Sensors function as a ships eyes and ears in space. Constantly scanning passively. Active scanning requires an action on the part of the AI or a crew member (technician). Assuming the ship has an AI (though it is not required) the AI is performing passive sensor scans at all times unless told not to. Keep in mind passive sensors do not alert anyone of your presence, but active sensors will. 

| SENSORS                 | MODIFIER | Reliability | TL   | SP   |
| :---------------------- | :------- | :---------- | :--- | :--- |
| Cut-Rate Sensors        | No Bonus | 1           | 13   | 0    |
| Budget Sensors Mk 1     | 1/0/0/0  | 1+          | 13   | 2    |
| Budget Sensors Mk 2     | 1/0/0/0  | 2           | 13   | 3    |
| Basic Sensors Mk 1      | 2/1/0/0  | 2+          | 13   | 4    |
| Basic Sensors Mk 2      | 2/1/0/0  | 3           | 13   | 5    |
| Advanced Sensors Mk 1   | 3/2/1/0  | 3+          | 14   | 6    |
| Advanced Sensors Mk 2   | 3/2/1/0  | 4           | 14   | 7    |
| SyndiCorp Sensors Mk 1  | 4/3/2/1  | 4+          | 14   | 10   |
| SyndiCorp Sensors Mk 2  | 4/3/2/1  | 5           | 14   | 12   |
| Drake Ind. Sensors Mk 1 | 5/4/3/2  | 5+          | 15   | 14   |
| Drake Ind. Sensors Mk 2 | 5/4/3/2  | 6           | 15   | 16   |

- Modifier. Range is listed as #/#/#/# for Short/Medium/Long/Extended this is the bonus to Perception/Investigate for passive and active sensors. 
- Reliability. This is the reliability of this system (see System Damage)
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

Sensors give a bonus to Perception (passive sensors), and Investigate (active sensors) checks within their ranges.
- Short: 50 hexes or 2500ft
- Medium: 100 hexes or 5000ft
- Long: 200 hexes or 10000ft
- Extended: 3 AU's (300 million miles)

#### Step 9. Shields
While almost every ship has simple navigational shielding to prevent damage from tiny bits of debris, this protection does little to stop a starship from being damaged by lasers, missiles, and larger impacts. To defend against such threats, a ship has energy shields. Projectors mounted around the ship create a barrier that absorbs damage from attacks. Each attack reduces the number of Shield Points the shields are depleted, after which point all further damage reduces the ship’s Hull Points. Shields do regenerate every round during combat with the dice indicated, when a ship is out of combat shields regenerate 10% a minute, so within 10 minutes they are at full power assuming they did not fail. Shields must be attached to a functional power core in order to regenerate; the rate of regeneration is listed in the table below. **Should Shields fall during combat they are offline and will not regenerate, they will need a Patch Repair**

The table also lists rate of regeneration, Power needed, and cost.

| Shield Name           | Total Shields | Regen         | Power | TL   | SP   |
| :-------------------- | :------------ | :------------ | :---- | :--- | :--- |
| CDS Mark I            | 10            | 1 + ConMod    | 5     | 14   | 2    |
| CDS Mark II           | 20            | 2 + ConMod    | 10    | 14   | 3    |
| CDS Mark III          | 25            | 1d4 + ConMod  | 15    | 14   | 3    |
| CDS Mark IV           | 30            | 2d4 + ConMod  | 15    | 14   | 4    |
| CDS Mark V            | 35            | 1d6           | 20    | 14   | 8    |
| ADS 1                 | 40            | 1d6 + ConMod  | 20    | 14   | 5    |
| ADS 1a                | 45            | 1d6 + ConMod  | 20    | 14   | 6    |
| ADS 2                 | 50            | 1d8           | 25    | 14   | 15   |
| ADS 2a                | 55            | 1d8 + ConMod  | 30    | 14   | 8    |
| ADS 3                 | 60            | 1d8 + ConMod  | 30    | 14   | 10   |
| ADS 3a                | 65            | 1d10          | 30    | 14   | 12   |
| ADS 4                 | 70            | 1d10 + ConMod | 35    | 14   | 20   |
| ADS 4a                | 75            | 1d10 + ConMod | 40    | 14   | 13   |
| Daelin Corp. Defense  | 100           | 1d12          | 50    | 14   | 15   |
| Daelin Corp. Premium  | 125           | 1d12 + ConMod | 60    | 14   | 17   |
| Daelin Corp. Advanced | 150           | 1d12 + ConMod | 75    | 14   | 18   |
| Daelin Corp. Pro      | 175           | 2d6 + ConMod  | 90    | 14   | 20   |
| Daelin Corp. Ultra    | 200           | 2d6 + ConMod  | 100   | 14   | 22   |
| Daelin Corp. Max      | 225           | 2d8           | 110   | 14   | 23   |
| LCI Inc. Type 1       | 250           | 2d8 + ConMod  | 125   | 14   | 25   |
| LCI Inc. Type 2       | 275           | 2d8 + ConMod  | 135   | 14   | 27   |
| LCI Inc. Type 3       | 300           | 2d10          | 150   | 14   | 28   |
| LCI Inc. Type 4       | 325           | 2d10 + ConMod | 160   | 14   | 30   |
| SyndiCorp Class 1     | 350           | 2d10 + ConMod | 175   | 14   | 32   |
| SyndiCorp Class 2     | 375           | 2d12          | 185   | 14   | 35   |
| SyndiCorp Class 3     | 400           | 2d12 + ConMod | 200   | 14   | 40   |
| Drake Ind. A          | 425           | 3d10          | 210   | 15   | 45   |
| Drake Ind. B          | 450           | 3d10 + ConMod | 225   | 15   | 50   |
| Drake Ind.T           | 475           | 2d20          | 235   | 15   | 55   |
| Drake Ind. D          | 500           | 2d20 + ConMod | 250   | 15   | 60   |

- Total Shields. Total Shield points available when fully charged
- Regen. Shields that regenerate when a Technician rolls to regenerate shields each round. If the shields fall a Patch Repair is required to get them back online.
- Power. This is how much power this system uses
- Reliability. This is the reliability of this system (see System Damage)
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost


#### Step 10. Security
| Security                    | Power | TL   | SP        |
| :-------------------------- | :---- | :--- | :-------- |
| Anti-Hacking Systems        | 3     | 14   | .         |
| Antipersonnel Weapon, Heavy | 10    | 14   | 10        |
| Antipersonnel Weapon, Light | 5     | 14   | 5         |
| Autodestruct System         | 0     | 14   | 1*SizeMod |
| Biometric Locks             | 5     | 14   | .         |
| Computer Countermeasures*   | 1     | 14   | 1         |
| Consciousness Uplink        | 0     | 15   | 4         |

- Power. This is how much power this system uses
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

**Anti-Hacking System**. This is a more severe way of dealing with computer intrusion. This system prevents the ships computers from networking, preventing AI from being used at all but making computer intrusion virtually impossible except physcially manipulating the individual systems at their consoles.

**Antipersonnel Weapon, Heavy**. This adds a Heavy Bolter Rifle to the ships bridge, hangars and airlocks to defend against boarders.

**Antipersonnel Weapon, Light**. This adds a Bolter Pistol to the ships bridge, hangars and airlocks to defend against boarders.

**Autodestruct System**. This will destroy the ship by blowing up the reactor when the ship reaches 0 Hull Points 1 minute after. It cannot be aborted except by the ships Captain

**Biometric Locks**. This locks all doors and systems on board the ship to specified biometrics. The only way to bypass this is to hack the computer

**Computer Countermeasures**. This gives a bonus to saves against computer intrustion this can be taken up to 5 times

**Conciousness Uplink**. This is used to allow for an AI to interface with a ship that does not have an AI or to replace an on board AI.

#### Step 11. Life Support
Life support systems provide oxygen, water, electric to all of the required areas of the ship. They provide automatic fire control systems, auto closing hatches to seal breaches, etc. If your Life Support is taken off line you have a number of rounds equal to your ships Con Mod x 10 of air and power remaining in the ship before you start to run out of air.

| Name             | Reliability | SP   |
| ---------------- | ----------- | ---- |
| Basic            | 1           | None |
| Basic Hardened   | 1+          | 2    |
| Class 1          | 2           | 3    |
| Class 1 Hardened | 2+          | 4    |
| Class 2          | 3           | 5    |
| Class 2 Hardened | 3+          | 6    |
| Class 3          | 4           | 7    |
| Class 3 Hardened | 4+          | 8    |
| Class 4          | 5           | 9    |
| Class 4 Hardened | 5+          | 10   |
| Class 5          | 6           | 12   |

- Reliability. This is the reliability of this system (see System Damage)
- SP. This is the Ship Points it will cost

#### Step 12. Weapons
Each ship armament is listed in this section. Unless otherwise noted, a ship’s weapon can be used only once during a ship’s turn unless special circumstances apply. A gunner can use only one weapon on each of their ship’s turns.

Weapons are classified using the following key statistics. 

- Name: This is the name of the weapon. 
- Type: Starship weapons are one of two types. Direct-fire weapons fire projectiles or beams at amazing speed, targeting the opposing vessel’s AC. Tracking weapons’ projectiles are slower and must home in using a target’s TL. A tracking weapon’s projectile has a listed speed; once fired, it moves that number of hexes toward its target. Each subsequent round during the gunnery phase, it must succeed at a attack against the target’s TL to continue to move its speed toward its target. On a failure, the projectile is lost. If the projectile reaches the target’s hex, it deals the listed damage. 
- Range: Weapons have one of three ranges: short range (5 hexes), medium range (10 hexes), or long range (20 hexes). As with characterscale ranged attacks, an attack with a starship weapon takes a cumulative –2 penalty for each range increment (or fraction thereof, beyond the first) between it and the target. A gunner firing a tracking weapon takes a range penalty only on her first attack, when the target is first acquired. A starship weapon can fire at a target up to 10 range increments away. 
- Speed: This is the distance in hexes a tracking weapon moves toward its target each round during the gunnery phase. Projectiles from a tracking weapon have perfect maneuverability, and as such, they have a minimum turn distance of 0
- Damage: This is the amount of damage (in Hull Points) the weapon deals when it successfully hits a target.
- Power: This is the amount of Power consumed by the weapon. It uses this amount continuously whenever the weapon is powered up and ready to fire.
- SP: This is the cost of the weapon in Build Points. 
- Damage Type: This is the Damage Type of the weapon
- Special Properties: Some weapons have special properties, as noted in the secontion after the tables
- Hardpoint Slots: Each weapon takes a numberof hardpoints, which the ships has a limited number of (Size Category + Size Category X StrMod)

- Capital Weapons **must be mounted on a forward mount** and cannot be placed on ships smaller than Large
- Turrets cannot support weapons larger than small
 

##### Small Weapons
These can be installed in any hardpoint.

All Small Weapons have a Relaibility of 3.

| Weapon                         | Range | Save DC | Damage         | Power | Special Properties                     | Hardpoint Slots | TL  | SP  |
| :----------------------------- | :---- | :------ | :------------- | :---- | :------------------------------------- | --------------- | --- | --- |
| Minigun                        | 10/20 | .       | 1d6 (Kinetic)  | 10    | Rapid                                  | 1               | 12  | 10  |
| Autocannon                     | 5/10  | .       | 1d6 (Kinetic)  | 10    | Burst Fire                             | 1               | 12  | 3   |
| Micro-Railgun                  | 5/10  | .       | 1d8 (Kinetic)  | 10    | Self-target                            | 1               | 13  | 3   |
| Light Ion Cannon               | 5/10  | .       | 1d8 (Ion)      | 10    | Ionizing                               | 1               | 14  | 9   |
| Light Laser Cannon             | 5/10  | .       | 1d6 (Energy)   | 5     | .                                      | 1               | 14  | 2   |
| Light Particle Cannon          | 10/20 | .       | 1d8 (Energy)   | 10    | .                                      | 2               | 14  | 10  |
| Light Railgun                  | 10/15 | -       | 1d10 (Kinetic) | 15    | Self-Target                            | 2               | 14  | 10  |
| Light Plasma Cannon            | 5/10  | .       | 1d12 (Fire)    | 15    | .                                      | 2               | 14  | 12  |
| **Point Defense Systems**      | .     | .       | .              | .     | .                                      | .               | .   | .   |
| Flak PDC                       | 5/5   | .       | 1d4  (Kinetic) | 10    | Point                                  | 1               | 13  | 5   |
| Laser Point Defense            | 5/5   | .       | 1d6  (Energy)  | 10    | Point, Automated                       | 1               | 14  | 9   |
| **Tracking Weapons**           | .     | .       | .              | .     | .                                      | .               | .   | .   |
| Light Missile Launcher         | 20/40 | 14      | 2d8  (Kinetic) | 10    | Ammunition (6), Self-target, Tracking  | 3               | 12  | 14  |
| Light Hellfire Rocket Launcher | 20/40 | 16      | 1d8  (Fire)    | 5     | Ammunition (8), Self-target, Tracking  | 1               | 13  | 11  |
| Light Torpedo Launcher         | 20/40 | 18      | 1d6  (Energy)  | 5     | Ammunition (10), Self-target, Tracking | 1               | 14  | 7   |

- Range. This is the weapons range in Hexes (each Hex is 50ft)
- Save DC. Used for tracking weapons this is the DC needed to avoid damage (and the AC to hit for Point Defenses)
- Damage. This is the Damage and damage type.
- Power. This is how much power this system uses
- Special Properties. This list any special properties see "Weapon Properties"
- Hardpoint Slots. This is how many hardpoints the weapon takes up on a ship out of the total. 
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

##### Medium Weapons
These cannot be installed in Turrets.

All Medium weapons have a Reliability of 4.

| Weapon                         | Range | Save DC | Damage         | Power | Special Properties                     | Hardpoint Slots | TL  | SP  |
| :----------------------------- | :---- | :------ | :------------- | :---- | :------------------------------------- | --------------- | --- | --- |
| Heavy Autocannon               | 5/10  | .       | 1d10 (Kinetic) | 15    | Burst Fire                             | 3               | 12  | 14  |
| Heavy Ion Cannon               | 10/20 | .       | 3d8  (Ion)     | 15    | Ionizing                               | 4               | 14  | 16  |
| Heavy Laser Cannon             | 10/20 | .       | 2d8  (Energy)  | 10    | .                                      | 3               | 14  | 15  |
| Maser                          | 20/40 | .       | 3d10 (Energy)  | 35    | .                                      | 8               | 15  | 22  |
| Particle Beam                  | 20/40 | .       | 2d6  (Energy)  | 25    | .                                      | 3               | 14  | 20  |
| Plasma Cannon                  | 10/20 | .       | 3d12 (Fire)    | 30    | .                                      | 4               | 14  | 20  |
| Heavy Railgun                  | 10/15 | .       | 2d10 (Kinetic) | 20    | Self-target                            | 4               | 13  | 15  |
| **Tracking Weapons**           | .     | .       |                | .     | .                                      | .               | .   | .   |
| Heavy Missile Launcher         | 20/40 | 16      | 3d10 (Kinetic) | 15    | Ammunition (6), Self-target, Tracking  | 3               | 12  | 35  |
| Heavy Hellfire Rocket Launcher | 20/40 | 18      | 3d8  (Fire)    | 10    | Ammunition (8), Self-target, Tracking  | 3               | 13  | 18  |
| Heavy Torpedo Launcher         | 20/40 | 20      | 3d6  (Energy)  | 10    | Ammunition (10), Self-target, Tracking | 3               | 14  | 16  |

- Range. This is the weapons range in Hexes (each Hex is 50ft)
- Save DC. Used for tracking weapons this is the DC needed to avoid damage (and the AC to hit for Point Defenses)
- Damage. This is the Damage and damage type.
- Power. This is how much power this system uses
- Special Properties. This list any special properties see "Weapon Properties"
- Hardpoint Slots. This is how many hardpoints the weapon takes up on a ship out of the total. 
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

##### Capital Weapons
These can **only** be installed in the forward mount and only 1 can be installed. Ships must be Large or Larger to install one of these.

All Capital Weapons have a Reliability of 5.

Capital Weapons are treated much like the AOE weapons that large Monsters and Creatures use in egular 5e. They do cost Energy but not Hardpoints as they can only be mounted forward and only one of them.

| Weapon                | Type      | Range       | Damage L/H/G/T                 | SI Dmg L/H/G/T | Power    | Recharge Time | Area of Effect (Hexes) | TL  | SP  |
| :-------------------- | :-------- | :---------- | :----------------------------- | :------------- | -------- | ------------- | :--------------------- | --- | --- |
| Capital Ion Cannon    | Surge     | .           | 3d8/8d8/12d8/16d8 (Ion)        | ././1/3        | Size x 5 | 2 Turns       | 3/8/10/16 PBAOE Sphere | 14  | 65  |
| Capital Plasma Cannon | Blast     | .           | 3d10/8d10/12d10/16d10 (Fire)   | ././1/3        | Size x 5 | 2 Turns       | 3/8/10/16 Cone         | 14  | 70  |
| Capital Railgun       | Explosive | 10/15/20/30 | 3d8/8d8/12d8/16d8 (Kinetic)    | 1/1/2/4        | Size x 5 | 3 Turns       | 3/6/8/12 Sphere        | 14  | 50  |
| Capital Maser         | Line      | .           | 3d10/8d10/12d10/16d10 (Energy) | 1/1/2/4        | Size x 8 | 3 Turns       | 10x1/15x1/25x2/40x2    | 15  | 75  |


- Type. Capital weapons have a type this describes how it does its damage.
  - **Blast** weapons fire directly from the ship in a cone, the size of which is defined on the Special Weapons table.
  - **Explosive** weapons target an area the ship can detect within a certain distance of it. The target’s distance is dependent upon the ship’s size: 10 units for a Large ship, 15 units for a Huge ship, 20 units for a Massive ship, and 30 units for a Colossal ship. The weapon then erupts into a sphere centered on that target.
  - **Line** weapons fire directly from the ship in a line whose length and width is defined on the Special Weapons table.
  - **Surge** weapons emit outward from the ship in a spherical radius defined on the Special Weapons table.
- Range. This is the weapons range in Hexes (each Hex is 50ft)
- Damage. This is the Damage and damage type. Listed here as Large/Huge/Gargantuan/Titanic as the weapons do more damage the bigger the ship they are mounted on.
- SI Dmg. Capital weapons do some SI damage every time an attack happens due to bleed through from the shields or hull. If the Hull and Shields are gone it is all SI damage
- Power. This is how much power this system uses
- Recharge Time. This is how many complete turns must pass before the weapon can fire again.
- Area of Effect. This is the area of effect in Hexes for the weapon (see Type)
- TL. This is the Tech Level required to have this system
- SP. This is the Ship Points it will cost

##### Weapon Properties
- **Automated**: An automated weapon is fired by the ships AI. This is a Reaction and uses one of the ships AI's actions that turn. It uses the AI's Proficiency Modififer + Ship's Wisdom Modifier to attack incoming Projectiles. Automated weapons cannot be crewed. 

- **Burst Fire**: A weapon that has the burst property can spray a 3x3 Square (150 foot-cube) area within range with shots. Each ship in the area must make a Dexterity saving throw (DC = 8 + your bonus to ranged ship attacks). On a failure, the ship takes the weapon's normal damage. The ship takes no damage on a success. If the ranged ship attack would have disadvantage, affected targets instead have advantage.

- **Ionizing**: On a hit, the target must succeed on a DC 13 dexterity saving throw or it is ionized for 1 minute. As an action by a crewmember on their turn, the ship can repeat the saving throw, ending the effect early on a success. Ships larger than you have advantage on the saving throw.

- **Ammunition**: A weapon with this special property can fire only the listed number of times in a starship combat encounter before it requires a brief period of time (10 minutes outside of starship combat) to recharge and rebuild the weapon’s inherent ammunition. A weapon with this special property is often a tracking weapon.

- **Point**: Point defense systems are meatnt to take out Tracking weapons before they can impact the shields preventing damage. If it is a Crewed Weapon (see Automated) the gunner on the weapon uses their reaction to attack the projectile weapons Save DC. If they hit the projectile is destroyed. 

- **Exclusive**: This weapon or starship component can only have one installed on a starship

- **Rapid**: A weapon that has the rapid property can unload on a single target. The target must make a Dexterity saving throw (DC = 8 + your bonus to ranged ship attacks). On a failed save, the target takes normal weapon damage, plus an additional amount equal to the weapon's damage dice. On a success, the target takes no damage. If the ranged ship attack would have disadvantage, the target instead has advantage.

- **Self-target.** These weapons don’t allow for manual variances from the gunner. When you hit with an attack from this weapon, you don’t add your ability modifier to the damage.

- **Tracking**: Tracking weapons use an on board targeting computer to fire and forget letting the weapon guide itself to the enemy. These weapons require a Evasive Maneuver from the pilot to limit the damage. The Save DC is 8 + Targeting computer bonus (listed in the chart as the finalized DC). The Pilot makes an Evasive Maneuver check, Dex + Proficiency Modifier (if proficient in Vehicle) to save for half damage.

#### Step 13. Upgrades

| Name                          | Prerequisites                          | Power | SP        |
| :---------------------------- | :------------------------------------- | :---- | :-------- |
| Amphibious Systems            | Ship size Large or Smaller             | .     | 4         |
| Anti-Boarding System          |                                        | 1     | 4         |
| Armory                        |                                        | 1     | 5         |
| Atmospheric Entry System      | Ship size Large or Larger              | 10    | 4*SizeMod |
| Backup Jump Drive             |                                        | 50    | 1*SizeMod |
| Cargo Expansion               |                                        | .     | 2         |
| ***Cloaking Systems***        | .                                      | .     | .         |
| *Sensory Cloak*               |                                        | 20    | 15        |
| *Enhanced Cloak*              |                                        | 100   | 40        |
| *Drakneri Cloak*              | TL 15+                                 | 125   | 60        |
| Cryo-chamber                  |                                        | 10    | 5         |
| Damage Control System         |                                        | 2     | 6         |
| Docking Bay                   | Ship size Large larger                 | 5     | 5         |
| Docking Bay, Rapid Launch     | Ship size Large or larger, Docking Bay | 10    | 5         |
| Ejection Pod                  |                                        | .     | 4         |
| Escape Pods                   | Ship size Medium or larger             | 0     | 5         |
| External Docking System       |                                        | 5     | 5         |
| External Docking Pylon System | Ship Size Gargantuan                   | 50    | 50        |
| Fuel Refinery                 |                                        | 5     | 5         |
| Fuel Scoop                    |                                        | 5     | 5         |
| Fuel Storage                  |                                        | 0     | 5         |
| Hidden Storage                |                                        | 1     | 5         |
| Holding Cells                 |                                        | 1     | 5         |
| Hydroponics Garden            | Ship size Medium or larger             | 0     | 5         |
| Interrogation Chamber         | Ship size Medium or larger             | 4     | 5         |
| Investigation Lab             |                                        | 4     | 5         |
| Insulated Circuits            |                                        | .     | 11        |
| Kennel                        |                                        | 1     | 5         |
| Laboratory                    |                                        | 4     | 5         |
| Mechanic's Shop               |                                        | 4     | 5         |
| Medbay                        |                                        | 4     | 5         |
| Mess Hall                     |                                        | 2     | 5         |
| Recreation                    |                                        | 3     | 5         |
| Security Office               | Ship size Medium or larger             | 2     | 5         |
| Slave Pens                    | Ship size Large or larger              | 2     | 5         |
| Storage Compartment           |                                        | 0     | 5         |
| Transportation                |                                        | 10    | 5         |
| Vault                         |                                        | 3     | 5         |
| Workshop                      |                                        | 3     | 5         |



##### Living Quarters
| Name            | Minimun Size | Power | Compliment Effect | SP  |
| --------------- | ------------ | ----- | ----------------- | --- |
| Living Quarters | S            | 1     | *1                | 1   |
| Barracks        | M            | 2     | *2                | 2   |
| Luxury Quarters | M            | 3     | *.5               | 3   |

Table: Fuel and Food

| Size | Fuel(u) | Cost Ch per unit | Food Required (⬢10) |
| ---- | ------- | ---------------- | ------------------- |
| D    | 5u      | ⬢10              | Max crew x 180      |
| S    | 10      | ⬢20              | Max Crew x 180      |
| M    | 30      | ⬢50              | Max Crew x 180      |
| L    | 300     | ⬢75              | Max Crew x 180      |
| H    | 600     | ⬢100             | Max Crew x 180      |
| G    | 1800    | ⬢200             | Max Crew x 360      |
| T    | 3000    | ⬢500             | Max Crew x 360      |

- **Barracks**
This upgrade features a single room, or series of rooms, to house a number of crewmembers equal to twice the ship’s upgrade capacity by size. Each room features bunks and individual storage, as well a communal refresher station for every eight beds (minimum of one).
- **Quarters, Living**
This upgrade features separate rooms to house a number of creatures equal to the ship’s upgrade capacity by size. Each room comes fully furnished and includes a communal refresher station for every four rooms (minimum of one). When a creature completes a long rest involving this upgrade, their exhaustion level is reduced by 2, instead of only 1.
- **Quarters, Luxury**
This upgrade features separate rooms to house a number of creatures equal to half the ship’s upgrade capacity by size. Each room comes fully furnished and includes its own refresher station. When a creature completes a long rest involving this upgrade, they regain all spent Hit Dice, instead of only half, and their exhaustion level is reduced by 2, instead of only 1.

#### Upgrade Descriptions

- **Amphibious Systems** This modification allows your ship and all of its systems (including weapons) to function underwater. Your ship gains a swimming speed equal to half of its normal speed.

- **Anti-Boarding System** An anti-boarding system is a robust series of blast doors, cameras, and hidden turrets, reinforcing each portal throughout the ship, as well as directly outside each ship entrance. These features are controllable from the cockpit or in the Security Office (if it exists) by a crewmember. The anti-boarding system comes with its own power backup in case of main system failure. The reinforced doors can be bypassed with a DC 20 Intelligence (Security Kit) check.

- **Armory** This upgrade comes with storage for weapons and armor to outfit a number of crewmembers equal to twice the ship’s upgrade capacity by size. When installed it comes fully stocked with Bolter pistols, Bolter rifles, techblades, as well as combat suits, mesh armor, battle armor, and shields. The armory is also equipped with both a key and a code lock. The armory can be accessed with a DC 20 Intelligence (Security Kit) check. When the armory is accessed, an alarm sounds in the Bridge and Security Office (if it exists). If a player rolls a 25 or higher on the Intelligence (Security Kit) check to unlock the armory, or has the key or code, the alarm can be bypassed. Additionally, it comes with a number of weapon training simulators equal to one-fourth the ship’s upgrade capacity by size (minimum of one). Lastly, when a creature completes a long rest involving this upgrade, they gain advantage on the first attack roll they make before the start of their next long rest.

- **Atmospheric Entry System** This upgrade allows a large or larger ship to enter a planets atmosphere but it must move at half speed and has a -5 AC because it cannot maneuver well.

- **Backup Jump Drive** This upgrade adds a backup jump drive rating 1 to your ship. It can be used if your main Jump Drive is offline or damaged.

- **Cargo Expansion** This increases your cargo capacity by 25%. To calculate your new total capacity, refer to your cargo capacity in “Step-by-Step Starship Design” and multiply that number by 1.25.

- **Cloaking Device**
Cloaking systems are designed for passing through areas undetected. There are two types. Each one requires your technician to expend an action to activate. The effects of a cloaking system end whenever your ship makes an attack or performs a maneuver. Or makes an active sensor check. You do not have Shields, or Weapon systems while a cloak is active.
  - **Sensory Cload** This unit sends waves of electromagnetic signals that interfere with other sensor systems. Perception checks made to detect your ship are made with disadvantage. You have advantage on saving throws made to avoid space hazards triggered by motion or proximity detection. You also have advantage on checks made to mask your drive signature.
  - **Enhanced Cloak** This system bends light and energy around your ship, making it invisible to all visual and electronic sensors. Your ship is invisible while this cloaking system is active.
  - **Drakneri Cloak**. This is restricted to Drakneri ships or ships of TL 15 or higher. This system functions as an Enhanced cloak but the ship can operate Active sensors without giving away a location, additionally shields are still active (if the ship has the power for them) while this cloak is active.

- **Cryo Chamber** This high-tech chamber allows biological organisms to enter a form of stasis via a rapid freezing process and be sustained in pods for a long duration. Cryo-chambers can be set to keep an organism in stasis for a set duration, indefinitely, or until certain conditions are met, such as arrival at a navigational milestone or if the vessel comes under attack. During the days before Jump travel, most starship crews used these chambers to survive the months-long trips between destinations. Some exploration ships still use cryo-chambers in lieu of crew quarters, particularly those that regularly travel in the outside the 'Verse. A cryo-chamber can hold up to eight Medium or smaller creatures or four Large creatures in stasis for as long as the systems have adequate power. A cryo-chamber can instead be outfitted to hold a single Huge or Gargantuan creature, and two cryo-chambers can be combined to hold a single Titanic creature. While in stasis in a cryo-chamber, a creature no longer advances on affliction tracks, and doesn’t suffer from starvation, thirst, or sleep deprivation. Placing a creature in stasis or removing it from stasis takes 1 hour, after which the creature is sickened for 1 day unless it succeeds at a DC 20 CON save

- **Damage Control System** These automated diagnostic systems provide benefits when performing emergency repairs. Your ship gains an additional use of the Jury Rig or Emergency Patch maneuver before requiring a full repair. In addition, when you perform the Jury Rig or Emergency Patch maneuver, your ship recovers double the normal amount of hull points and structural integrity.

- **Ejection Pod** You integrate an ejection pod in your ship’s cockpit. When your ship is reduced to 0 hull points but not destroyed outright, you can use your reaction to eject the pod from the ship. The pod includes emergency rations and supplies that can support a number of creatures equal to your maximum crew capacity for 1 day, in both hot and cold climates. The pod is Tiny size and has a flying speed of 3, a turning speed of 1, an AC of 10, and 5 hull points. The pod includes one unit of fuel.

- **Fuel Converter** This system allows the ship to refine fuel on its own. Allowing refueling from stations that sell unrefined fuel and also allowing for collection of fuel from Jovians to be used.

- **Docking Bay** This option can only be installed on a Large or larger size ship. Your ship has an insulated bay (or group of bays) specifically designed to hold and launch smaller vessels. The number of ships you can hold in your hangar bay(s) is determined by your ship’s size.

| Size       | Drones | Small | Medium | Large | Huge | Gargantuan |
| ---------- | ------ | ----- | ------ | ----- | ---- | ---------- |
| Large      | 25     | 5     | 1      | .     | .    | .          |
| Huge       | 50     | 10    | 4      | 2     | .    | .          |
| Gargantuan | 1000   | 50    | 20     | 10    | 2    | .          |
| Titanic    | 5000   | 250   | 100    | 50    | 10   | 5          |

| Size       | Slots |
| ---------- | ----- |
| Drone      | 1     |
| Small      | 5     |
| Medium     | 2.5   |
| Large      | 25    |
| Huge       | 500   |
| Gargantuan | 1000  |

Ships launched out of a Docking Bay do not act in an initiative until the next round.

- **Docking Bay, Rapid Launch** A rapid launch upgrade to an already exising Docking Bay makes ships launced able to act the same round they are launched.

- **Escape Pods** This upgrade adds escape pods to your ship. Each escape pod comes equipped with 5 units of fuel and emergency rations and supplies that can support four crewmembers for 5 days, in both hot and cold climates, as described in chapter 5 of the Dungeon Master’s Guide. The quantity of escape pods is equal to one-fourth the ship’s upgrade capacity. All expended escape pods are replaced when the ship undergoes refitting.

- **External Docking System** Your ship is equipped with an airlock and couplers designed to attach and connect to one ship of a size one category smaller than your ship. As an  action, a crewmember can engage or disengage the external docking system. While a ship is coupled to your ship, the ships can share primary systems as appropriate, and creatures can transfer between ships  readily. If at least one external docking system is occupied  by at least one ship, your ship’s flying speed decreases by 50 feet (to a minimum of 50 feet), its turning speed  increases by 50 feet.

- **External Docking Pylong System** Your ship is equipped with an airlock and couplers with outrunner pylons designed to attach and connect to 3 ships of a size one category smaller than your ship or 1 ship of a size category smaller than your ship. As an  action, a crewmember can engage or disengage the external docking pylon system. While a ship is coupled to your ship, the ships can share primary systems as appropriate, and creatures can transfer between ships  readily. If at least one external docking system is occupied by at least one ship, your ship’s flying speed decreases by 50 feet (to a minimum of 50 feet), its turning speed increases by 50 feet, and its jump drive can never jump more than a 3 rating for determining travel time in jumpspace.

- **Fuel Storage** This large fuel tank is able to store additional fuel portions in your starship. The tank stores fuel units equal to 5 times your ship’s normal fuel capacity. These units can be used to fuel your own starship, or they can be transfered to other ships. Fuel can be transferred to ships of other size.

- **Hidden Storage** This upgrade comes equipped with hidden storage compartments, which have a capacity equal to half your ship’s base cargo capacity, as shown in the Starship Size Cargo Capacity table. Finding the hidden storage compartments requires a successful DC 20 Intelligence (Investigation) or Wisdom (Perception) check, which is made with disadvantage.

- **Holding Cells** This upgrade includes a security post and a number of individual holding cells equal to the ship’s upgrade capacity by size, as shown in the Starship Size Suite Capacity table, equipped with both a key and a code lock. Holding cell doors are magnetically sealed to prevent them opening in the event of power failure.

- **Hydroponics Garden** This upgrade grows plants for either consumption or commerce. If the Garden is configured for consumption, every day it produces common food in an amount capable of supporting a number of civilians, crewmembers, or troopers equal to one-eighth the ship’s upgrade capacity. If the Garden is configured for commerce, at the end of every month (7 weeks of 5 days) it produces plant goods with a market value in Chits of 10 times the ship’s upgrade capacity. In some cases, a GM may determine that this value could be increased if a particularly rare plant good is produced. In such cases, the players may need to procure rare starter material such as seeds or cuttings to start or continue production.

- **Interrogation Chamber** This upgrade includes all of the necessary implements and apparatuses necessary to interrogate, or even torture, a number of prisoners equal to half the ship’s upgrade capacity by size. When interrogating a prisoner, the interrogator has advantage on Charisma (Intimidation) and Charisma (Persuasion) checks. If they spend at least an hour interrogating a prisoner, the prisoner has disadvantage on Charisma (Deception) checks.

- **Investigation Lab** This upgrade comes with a number of investigation rooms equal up to one-fourth the ship’s upgrade capacity by size (minimum of one). Investigation rooms are equipped with an integrated archaeologist kit, disguise kit, forgery kit, jeweler’s implements, security kit, slicer’s kit, and surveyor’s implements. While making a check with any of these tools in an investigation room, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while crafting in an investigation room using the integrated tools, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level. Lastly, when a creature completes a long rest involving this upgrade, they gain advantage on the first Dexterity (Stealth), Intelligence (Investigation), Wisdom (Insight), or Wisdom (Perception) check they make before the start of their next long rest.

- **Insulated Circuits** When your ship loses SI, roll a d20. On a result of 10 or less, your ship does not suffer the effects of a system failure. On a result of 11 or more, your ship rolls for system failure as normal.

- **Kennel** This upgrade comes with all of the proper equipment to house beasts and comes with an integrated trapper’s kit. When making Animal Handling or trapper’s kit checks on your ship, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while crafting in a kennel using the integrated kit, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level. Lastly, this upgrade can house a number of medium beasts equal to half of the ship’s upgrade capacity by size. Alternatively, this upgrade can house beasts of other sizes. A Huge beast takes up the space of two Large beasts, which in turn takes up the place of two Medium beasts, and so on.

- **Laboratory** This upgrade comes with a number of laboratories equal up to one-fourth the ship’s upgrade capacity by size (minimum of one). Laboratories are equipped with an integrated alchemist’s kit, biotech’s implements, geneticist’s implements, poisoner’s kit, and a spicer’s kit. While making a check with any of these tools in a laboratory, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while crafting in a laboratory using the integrated tools, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level. Lastly, when a creature completes a long rest involving this upgrade, they gain advantage on the first Intelligence (Nature) or Wisdom (Medicine) check they make before the start of their next long rest.

- **Mechanic's Shop** This upgrade comes with a number of mechanical rooms equal up to one-fourth the ship’s upgrade capacity by size (minimum of one). Mechanical rooms are equipped with an integrated artillerist’s kit, astrotech’s implements, constructor’s implements, mechanic’s kit, and a scavenging kit. While making a check with any of these tools in a workshop, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while crafting in a mechanic’s shop using the integrated tools, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level. Lastly, this upgrade can house droids and constructs, depending on the ship’s size:   Small: A Small mechanic’s shop can house one Medium droid or construct. Medium: A Medium mechanic’s shop can house one Huge droid or construct. Large: A Large mechanic’s shop can house one Gargantuan droid or construct. Huge: A Huge mechanic’s shop can house 10 Gargantuan droids or constructs. Gargantuan: A Gargantuan mechanic’s shop can house 100 Gargantuan droids or constructs. Alternatively, this upgrade can house constructs or droids of smaller sizes. A Gargantuan construct or droid takes up the space of two Huge constructs or droids, which in turn takes up the space of two Large constructs or droids, and so on.

- **Medbay** This upgrade offers a single room featuring medical equipment and storage for medical supplies. When this upgrade is installed it comes stocked with the following items. 

| Medical Supplies                               |
| ---------------------------------------------- |
| Small: One biobed.                             |
| Medium: Two biobeds.                           |
| Large: 10 biobeds and four bio-gel tanks.      |
| Huge: 100 biobeds and 40 bio-gel tanks.        |
| Gargantuan: 100 biobeds and 400 bio-gel tanks. |
| Titanic: 200 biobeds                           |

For every two hours spent in a biobed or one hour spent in a bio-gel tank, a creature’s exhaustion level is reduced by 1, and it can roll a Hit Die to recover hit points without expending the die. After two hours, a creature in a bio-gel tank is also cured of any poison, disease, or harmful condition (such as blinded, corroded, deafened, paralyzed, poisoned, or weakened). This upgrade also offers a number of medical stations equal up to one-fourth the ship’s upgrade capacity by size (minimum of one). Medical stations are equipped with an integrated biochemist’s kit and a bioanalysis kit. While making a check with any of these tools at a medical station, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while crafting at a medical station using the integrated tools, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level.

- **Mess Hall** This upgrade comes with dining areas, that can accommodate a number of civilians, crewmembers, or troopers equal to twice the ship’s upgrade capacity by size, as shown in the Starship Size Suite Capacity table, as well as kitchens equal up to one-fourth the ship’s upgrade capacity by size (minimum of one). Kitchens are equipped with an integrated brewer’s kit and a chef’s kit. While making a check with any of these tools in a kitchen, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while crafting in a kitchen using the integrated tools, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level. Lastly, when a creature completes a long rest involving this upgrade, they regain two additional Hit Dice and have advantage on Constitution saving throws against disease for the next 24 hours.

- **Recreation** This upgrade comes with a number of recreational areas equal up to one-fourth the ship’s upgrade capacity by size (minimum of one). Recreational areas are equipped with integrated artist’s implements, gaming sets, musical instruments, and writer’s implements. While making a check with any of these tools in a recreational area, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while utilizing any of these tools, you gain a benefit based on which tools you are using. Gaming set or musical instrument: While playing one of the gaming sets or musical instruments, you can always readily read the emotions of those paying attention to you. During this time, and for up to one minute after completing, you have advantage on Wisdom (Insight) checks to read the emotions of those you performed for or competed against. Artists’s implements or writer’s implements: While crafting with these implements, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level. Lastly, when a creature completes a long rest involving this upgrade, they gain advantage on the first ability check they make before the start of their next long rest.

- **Security Office** This upgrade comes equipped with a full base of security for your ship, including secured storage, a brig, and a compact armory. The secured storage can hold an amount equal to one-tenth the ship’s base cargo capacity, as shown in the Starship Size Cargo Capacity. The secured storage is equipped with both a key and a code lock, and is magnetically sealed to prevent it opening in the event of power failure. The secured storage can be accessed with a DC 20 Intelligence (Security Kit) check. The brig can host a number of prisoners equal to one-fourth the ship’s upgrade capacity by size, as shown in the Starship Size Suite Capacity. The armory comes equipped with an amount of simple blasters and techblades, as well as light armor and shields, to outfit a force equal to one-half the ship’s upgrade capacity by size. When installed it comes fully stocked with Bolter pistols, Bolter carbines, and techblades, as well as combat suits and light shields

- **Slave Pens** This upgrade offers a single room, equipped with both a key and a code lock, that can house a number of prisoners equal to twice the ship’s upgrade capacity by size. Slave pen doors are magnetically sealed to prevent them opening in the event of power failure. When a creature completes a long rest involving this upgrade, their exhaustion level is not reduced. Additionally, for each week spent in this upgrade, creatures suffer 1 level of exhaustion.

- **Storage Compartment** This upgrade increases the cargo capacity on your ship by its base cargo capacity, as shown in the Starship Size Cargo Capacity table.

- **Transportation** This upgrade offers a single room, or series of rooms, typically located near the cockpit or entrance ramp, featuring a number of seats and individual storage, as well as communal refresher stations (one for every 16 seats), to transport a number of humanoids equal to four times the ship’s upgrade capacity by size.

- **Vault** This upgrade comes equipped with a vault, which has a capacity equal to half your ship’s base cargo capacity, as shown in the Starship Size Cargo Capacity table. The vault is equipped with both a key and a code lock, and is magnetically sealed to prevent it opening in the event of power failure. The vault can be accessed with a DC 25 Intelligence (Security Kit) check. When the vault is accessed, an alarm sounds in the Bridge and Security Office (if it exists). If a player rolls a 30 or higher on the Intelligence (Security Kit) check to unlock the vault, or has the key or code, the alarm can be bypassed.

- **Workshop** This upgrade comes with a number of workshops equal up to one-half the ship’s upgrade capacity by size (minimum of one). The workshops are equipped with an integrated armormech’s implements, armstech’s implements, artificer’s implements, audiotech’s implements, cybertech’s implements, demolitions kit, gadgeteer’s implements, munitions kit, tinker’s implements, and a trapper’s kit. While making a check with any of these tools in a workshop, you can add your proficiency bonus to checks you make if you do not already do so. If you already add your proficiency bonus to checks you make, you instead add an expertise dice. Additionally, while crafting in a workshop using the integrated tools, the total market value you can craft per day increases by an amount of chits equal to 5 x your character level. If you add an expertise dice to checks you make with them, the market value increases by 10 x your character level. Lastly, when a creature completes a long rest involving this upgrade, they gain advantage on the first ability check using tools they make before the start of their next long rest, except for checks made while using a upgrade.

#### Step 14. Final Calculations
- AC: Base AC + Manueverability Modifier + Armor Modifier + AI Dex Modifier/Pilot Dex Modifier
- HP: Hull points determined by the size of he ship in Step 2
- Mark Skill Proficiencies - Determined by AI
- Mark Save Proficiencoie - Determined by AI
- Power Used by Tactical Systems, Propulsion Systems, Operations Systems, Miscellaneous Systems
- Fuel On board
- Food on Board
- Crew Compliment
- Tactical Systems: Calculate attacks for weapons (AI Wis Mod Ability + Player or AI Proficiency based on who is attacking)
  - Forward: Weapons in the Forward Arc
  - Left: Weapons in the Left Arc
  - Right: Weapons in the Right Arc
  - Back: Weapons in the Back arc
  - Turret: Weapons on a Turret so they can fire in any arc (typically Point Defense)
- Cargo Space
- SP Used


Ensure you have everything else noted down and you have a starship, you are ready to fly.

## Artificial Intelligence
Astra Genesis has a fully fledged system for using an AI with ships as most ships in the Verse use an AI for their operations.

There are two types of AI in Astra Genesis. Free AI and Tethered AI. A free AI is one that can grow and learn (even possibly be a player character) in essence they can level up. A tethered AI is a fixed creature with fixed stats and cannot learn. There are some other restrictions.


### Free AI
A Free AI is one without the restraints of Asimov circuits. It is also capable of learning and growing over time, in essence it can grow as a person. The AI knows it is an AI but it also knows it can grow and learn. Roll them like any NPC and they can fill a variety of roles on a ship. If a player wants to play an AI there is an option for that. 

Starships have an AI which are like another player character at the table, as such we are going to generate them in much the same way.

So you take the standard array [15,14,13,12,10,8] and place them where you want.

For reference this is the Ability Modifier Chart:

| Ability Score | Bonus |
| ------------- | ----- |
| 8-9           | -1    |
| 10-11         | +0    |
| 12-13         | +1    |
| 14-15         | +2    |
| 16-17         | +3    |
| 18-19         | +4    |
| 20-21         | +5    |
| 22            | +6    |

- A free AI gets 2 Skill proficiencies at 1 Level.
  - Another at 5
  - Another at 10
  - Another at 15
  - Another at 20
- AI gets 2 Save Proficiencies at 1st level
  - Another at 10
  - Another at 15


#### Level Chart for Free AI's

| Level | Ability Increase | AI Prof | AI  Actions |
| ----- | ---------------- | ------- | ----------- |
| 1     | -                | 2       | 1           |
| 2     | 1                | 2       | 1           |
| 3     | -                | 2       | 1           |
| 4     | -                | 2       | 1           |
| 5     | 1                | 3       | 2           |
| 6     | -                | 3       | 2           |
| 7     | -                | 3       | 2           |
| 8     | -                | 3       | 2           |
| 9     | 1                | 4       | 2           |
| 10    | -                | 4       | 2           |
| 11    | -                | 4       | 3           |
| 12    | -                | 4       | 3           |
| 13    | 1                | 5       | 3           |
| 14    | -                | 5       | 3           |
| 15    | -                | 5       | 3           |
| 16    | -                | 5       | 3           |
| 17    | 1                | 6       | 4           |
| 18    | -                | 6       | 4           |
| 19    | -                | 6       | 4           |
| 20    | -                | 6       | 4           |

- Ability Increase. An AI may choose to raise an attribute by 2 or 2 attributes by 1. Only Intelligence can be higher than 20 on a Free AI it can be a 22.
- AI Prof. This is the Proficiency Bonus for the AI
- AI  Actions. As long as the AI is in a ship a Free AI can fill any role the crew needs it to and can use these actions to perform a function. For example firing automated PDC's is an AI Action. If the AI had 3 actions it could move the ship, fire the automated PDC's or launch tracking weapons (but not other weapons as they require a gunner), and also use an Action for shield Recharge. 

#### AI in an Android
Technically an AI could be transfered from a ship to an Android body. Doing so removes he AI from the ship and unless it has a way to interface with the ship in some other way the ship loses he benefit of a free ai.

### Tethered AI
A Tethered AI was developed by the UTE and thus has Asimov Circuits. There are several limitations to a Tethered AI.

1. Its Statistics are fixed. To get better you buy a new AI
2. Tethered AI cannot perform any Actions during combat besides Technician Actions
3. Tethered AI must abide by the Asimov Laws
  1. It may not injure a sentient being or through inaction allow a being to come to harm
  2. It must obey orders given to it by its crew except where it would come into conflict with the 1st law
  3. It must protect its own existence so long as it does not conflict with the first and second law
4. Tethered AI's can perform scan functions, library computer access, tactical analysis, medical diagnostics, any function that does not conflict with the laws

#### Tethered AI Chart

| Tier | Proficiency Bonus | Stat 1 (Mod) | Stat 2 (Mod) | Stat 3 (Mod) | Stat 4 (Mod) | Stat 5 (Mod) | Stat 6 (Mod) | TL  | SP  |
| ---- | ----------------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | --- | --- |
| 1    | +2                | 15  (+2)     | 14  (+2)     | 13  (+1)     | 12   (+1)    | 10   (+0)    | 8   (-1)     | 14  | 10  |
| 2    | +3                | 16  (+3)     | 14  (+2)     | 13  (+1)     | 12   (+1)    | 10   (+0)    | 9   (-1)     | 14  | 30  |
| 3    | +4                | 16  (+3)     | 16  (+3)     | 13  (+1)     | 12   (+1)    | 10   (+0)    | 10  (+0)     | 14  | 40  |
| 4    | +5                | 18  (+4)     | 16  (+3)     | 13  (+1)     | 12   (+1)    | 10   (+0)    | 10  (+0)     | 14  | 50  |
| 5    | +6                | 20  (+5)     | 16  (+3)     | 14  (+2)     | 12   (+1)    | 10   (+0)    | 10  (+0)     | 14  | 60  |
| 6    | +7                | 20  (+5)     | 16  (+3)     | 14  (+2)     | 14   (+2)    | 12   (+1)    | 10  (+0)     | 15  | 70  |
| 7    | +8                | 20  (+5)     | 18  (+4)     | 14  (+2)     | 14   (+2)    | 12   (+1)    | 10  (+0)     | 15  | 80  |
| 8    | +9                | 20  (+5)     | 18  (+4)     | 16  (+3)     | 14   (+2)    | 12   (+1)    | 10  (+0)     | 16  | 90  |

- Proficiency Bonus. This is applied to anything the AI does. Distinctly note the Tethered AI cannot perform any saving throws but it can help with making its own skill checks.
- Stat 1. When installed the installer determines of the 6 stats which this is
- Stat 2. When installed the installer determines of the 6 stats which this is
- Stat 3. When installed the installer determines of the 6 stats which this is
- Stat 4. When installed the installer determines of the 6 stats which this is
- Stat 5. When installed the installer determines of the 6 stats which this is
- Stat 6. When installed the installer determines of the 6 stats which this is
- TL. Tech Level this is the required Tech Level to aquire this AI
- SP. This is the cost in Ship Points to get this AI

> Setting Designer
> This is how I solved the problem of giving ships stats and not having to worry about fiddling with the ships stats changing with upgrades. They just upgrade the AI
> It also gives me an incredibly fast method of determining the stats for NPC crews

## Standard Astra Genesis Starship Operations
Starship operations and combat in Astra Gensis is meant to be fast paced, fun, and not get bogged down too much by maneuvers, and minutia. There is an optional set of rules for a more "Tactical" style of combat which is useful if you have a big party. The standard rules work great.

1. Initiative based on the Captain/Pilot Dex
2. The loser determines engagement distance the winner goes first
3. Each player on a ship gets an Action
   1. Operating a system is a Full Round Action
   2. 

### Space Action Economy
Every ship is a just a vehicle but the AI aboard that ship is another character. Thus the AI gets 1 Standard Action, 1 Move Action, 1 Reaction, and 1 Bonus Action per turn. Some ships may have special cases such a "Legendary Actions" but those are not covered here. As the AI gets more powerful it gains more abilities (see AI section)


| Action            | Action Type  | Effect                                               | Crew Role  |
| ----------------- | ------------ | ---------------------------------------------------- | ---------- |
| Pilot             | Move         | Ship moves its speed in hexes                        | Pilot      |
| Fire Weapon       | Attack       | Ship fires a single weapon in an arc                 | Gunner     |
| Recharge Shield   | Bonus Action | Ship regains some sheild strength (based on shields) | Technician |
| Patch Up          |              |                                                      |            |
| Jury Rig          |              |                                                      |            |
| Automated PDC     | Reaction     | Ship uses its Automated Point Defense Weapons        | AI         |
| Manual Fire PDC's | Reaction     | Gunner fires a PDC                                   | Gunner     |
| Evasive Maneuver  | Reaction     | Pilot makes a Save versus a targeting weapon         | Pilot      |





## (Optional) Starship Operations
As an alternative to Starship Deployments you can use the Starship Operations system. It has several key differences.

### 27th century space combat tactics primer
Ship to ship combat in the 27th century is a dangerous affair utilizing AI. It has three ranges

1. Close or CQB
2. Medium
3. Long

Typically ships start at long range using Energy weapons if possible because they are light speed weapons, have good ranges for this and are accurate. 

When the ships get closer to medium range, the combat changes to Tracking weapons, point defenses, fighters and drones if possible. Energy weapons still work at this point but ships do not turn fast.

When a ship gets to CQB it is typically not where it wants to be. UTE ships use Railguns for this the Council tends to use Plasma weapons. It is common to see boarding actions at the CQB range, tracking weapons tend to be too fast for this range and firing them is often ineffectual. 


### Roles

#### Pilot
The pilot can perform the following maneuvers in combat. The range of a piloting maneuver is equal to the ship’s sensor range, as provided in the ship’s stats.

##### Attack Run
You charge toward another enemy in attack formation. You move your ship directly toward an enemy ship you choose within weapon range (you must move a minimum of 10 units). Make a piloting maneuver check versus the opponent’s maneuver defense. If successful, when your gunner hits the target with the attack maneuver, they deal additional damage equal to your Dexterity modifier. If your check is unsuccessful, the target can use its reaction to make an opportunity attack against you.

##### Full Thrust
You push the limits of your thrusters while maneuvering in combat. Make a DC 14 piloting maneuver check. If successful, until the start of your ship’s next turn, your maneuver defense increases by 2 and your speed increases an amount equal to half your intercept speed. This maneuver causes a severe amount of stress on your engines. When you perform this maneuver, your ship’s technician must spend their reaction and make a DC 14 Wisdom saving throw. If the save fails, your ship takes 1d4 points of lightning damage from the engine’s power surge.

##### Forced Position
You attempt to force an enemy ship into an optimal position for an ally’s attack. Make a piloting maneuver check versus the maneuver defense of a target within two units of your ship. If successful, choose an ally within range. You can push the target up to 2 units toward that ally and the next attack roll made by that ally using the attack maneuver is made with advantage if the attack is made before the start of your ship’s next turn.

##### Ram
You attempt to ram your ship into an enemy ship. You charge toward another enemy in attack formation. Targets that are two or more size categories larger than your ship can’t be damaged by this maneuver. You move your ship directly toward an enemy ship you choose within the distance of your total intercept speed (you must move a minimum of 15 units). Make a piloting maneuver check versus the opponent’s maneuver defense. If successful, you can push the target up to 2 units. Refer to the Collision Damage table below and define the size category of the smallest ship in the collision. Both your ship’s technician and the target ship must make a Wisdom saving throw versus your maneuver save DC. Each ship takes bludgeoning damage equal to the amount listed on a failed save, or half as much on a successful one. For example, if a Large ship successfully rams a medium ship, both ships take 3d6 bludgeoning damage.

| Smallest Ship Size | Damage |
| ------------------ | ------ |
| Drone/Small        | 2d6    |
| Medium             | 3d6    |
| Large              | 4d6    |
| Huge               | 8d6    |
| Gargantuan+        | 20d6   |

#### Strafing Run
You sweep your ship alongside another ship to promote a quick, tactical strike. You must move at least 3 units before you perform this maneuver. Choose one ship within 5 units of you that can be seen with your ship’s sensors. Make a piloting maneuver check versus the target’s maneuver defense. If the check succeeds, attack rolls against the target can be made with advantage.

On a failed check, your ship has disadvantage on its attack rolls made against that target. The advantage or disadvantage effect lasts until the start of your ship’s next turn or until you perform another piloting maneuver.

#### Tactical Evasion
You attempt to place your ship in the best tactical position to avoid enemy fire. Choose a number of enemy ships up to your Wisdom modifier. Each target ship must make a Dexterity saving throw versus your maneuver save DC. On a failed save, a target has disadvantage on attack rolls made against your ship until the start of your ship’s next turn or until you perform another piloting maneuver.

#### Gunner
A ship’s gunner may perform the following maneuvers. When making an attack roll with a ship’s weapon, the gunner is considered to be proficient in that weapon.

##### Attack
This is the most common maneuver for a gunner to take, firing a ship’s weapon to deal damage to a foe. When you perform this maneuver, you make one melee or ranged weapon attack with your ship’s weapon. 


##### Cover Fire
You fire your ship’s weapons in an attempt to take an enemy’s focus away from another target. Make a ranged weapon attack versus a target’s maneuver defense. If successful, choose up to two allies. Attack rolls against those allies from the target of your cover fire are made with disadvantage to the roll until the end of the target’s next turn.

##### Focused Aim
You focus your attention on a single target and take extra time in attempt to increase the effectiveness of your attack. Choose a target within range. Your next attack on this target using the attack maneuver is made with advantage. In addition, a roll of a 19 or 20 on the die results in a critical hit.

##### Ready
You can use this maneuver to act later in the round using your reaction. This maneuver functions the same as taking the Ready action.

##### Target Systems
You attempt to damage or disable one of the operating systems of another ship. Make a ranged weapon attack against a target within weapon range. On a hit, you inflict half the weapon’s damage and the target ship’s technician must make an Intelligence saving throw against your maneuver save DC. If the save is not successful, the target also suffers system damage, which is determined by the following table. The effect from the system damage lasts until the end of the target’s next turn.

| d10 Roll | System Affected                                                                                                         |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| 1        | Guidance. The target’s speed is reduced by half and they are at disadvantage to all piloting maneuver checks and saves. |
| 2-6      | Defense. The target’s AC and maneuver defense are both reduced by a d4.                                                 |
| 7-9      | Weapons. The target is at a disadvantage to all attack rolls made with the ship’s weapons.                              |
| 10       | Electrical. The target ship may only perform maneuvers from one of the three assigned roles.                            |



#### Technician
A technician performs the following maneuvers.
Emergency Patch
You perform damage control on systems damaged during combat. Make a Wisdom (Engineering)[Mechanics] check against a DC defined on the following table. If the check is successful, your ship recovers the listed amount of hull points and structural integrity. In addition, you end any system failure effects. This maneuver can be performed three times, after which the ship must complete a patch or full repair before it can be used again.

| Ship Size        | DC  | HP Restored | SI Restored |
| ---------------- | --- | ----------- | ----------- |
| Large or smaller | 14  | 1d4+WisMod  | 1           |
| Huge             | 15  | 2d10+WisMod | 2           |
| Gargantuan       | 16  | 4d10+WisMod | 4           |
| Titanic          | 17  | 8d10+WisMod | 8           |

##### Power Boost
You divert power from non-essential systems to boost one of the ship’s systems. Make a DC 14 Wisdom (Engineering)[Mechanics] check. If successful, you may either increase the ship’s speed by half until the start of your ship’s next turn, or you grant a bonus to the next maneuver roll made by the pilot or gunner. The bonus is equal to 1d4 plus your Wisdom modifier.

##### Improved Sensors
You use environmental data to boost the ship’s targeting sensors. Make an Intelligence (Engineering)[Astrophysics] check against an opponent’s maneuver defense. On a success, the next weapon attack made by your ship using the attack maneuver is made with advantage to the roll if the attack is made before the start of your ship’s next turn.

##### Pinpoint Targeting
You scan a target for structural weak points. Make an Intelligence(Engineering)[Computers] roll versus the maneuver defense of a target within range. If successful, until the start of your ship’s next turn, a successful weapon attack from your ship against the target deals additional damage equal to your Intelligence modifier.

##### Sensor Jamming
You attempt to jam the enemy’s targeting system. Make an Intelligence(Engineering)[Computers] check versus the maneuver defense of a target within range. If successful, the target’s next attack roll against your ship is made with disadvantage if the attack is made before the start of your ship’s next turn.

#### Captain

#### Co-Pilot

## (Optional) Quick and Easy Starships
So you don't want to deal with making starships? Maybe you need a quick and dirty starship to throw at players. Use this chart.

How powerful the ship needs to be depends on the party. I tend to take their Ship Level/2 round up and use that for a low threat fight, for moderate I will throw two ships at them or one of equal level and for a dangerous challenge I will iuncrease the CR to 3 above their ship level. If they need to run from a fight I make it +5.

So if they had a Level 10 ship, then a level 5 ship would be a low threat or it should be. I would throw something like a Level 5 Destroyer at them. For a moderate challnge maybe 2 CR 5 Destroyers and a CR 10 Cruiser. If I wanted to make it hard a CR 13 Cruiser would do it, or brutal I would go with a CR 15 Battleship (Or a battlegroup of 2 CR 5 Destroyers and a CR 5 Cruiser)

| CR   | AC   | HP   | Shields | Prof Bonus | Abil. Bonus | Attacks | DMG/Round | High Dmg Save | Low Dmg Save |
| :--- | :--- | :--- | :------ | :--------- | :---------- | :------ | :-------- | :------------ | :----------- |
| 0    | 12   | 3    | 0       | 2          | 0           | 1       | 1         | 10            | 10           |
| 1/8  | 12   | 9    | 0       | 2          | 1           | 1       | 3         | 11            | 11           |
| 1/4  | 12   | 15   | 10      | 2          | 1           | 1       | 5         | 11            | 11           |
| 1/2  | 13   | 24   | 20      | 2          | 2           | 1       | 8         | 12            | 12           |
| 1    | 13   | 30   | 25      | 2          | 2           | 1       | 10        | 12            | 12           |
| 2    | 13   | 45   | 30      | 2          | 3           | 2       | 15        | 13            | 13           |
| 3    | 14   | 60   | 40      | 2          | 3           | 2       | 20        | 13            | 13           |
| 4    | 14   | 75   | 50      | 2          | 4           | 2       | 25        | 13            | 14           |
| 5    | 14   | 90   | 60      | 3          | 4           | 2       | 30        | 14            | 15           |
| 6    | 15   | 105  | 70      | 3          | 4           | 2       | 35        | 14            | 15           |
| 7    | 15   | 125  | 75      | 3          | 4           | 2       | 40        | 14            | 15           |
| 8    | 15   | 135  | 100     | 3          | 4           | 2       | 45        | 14            | 15           |
| 9    | 16   | 150  | 100     | 4          | 4           | 2       | 50        | 15            | 16           |
| 10   | 16   | 165  | 100     | 4          | 5           | 2       | 55        | 15            | 17           |
| 11   | 16   | 180  | 125     | 4          | 5           | 3       | 60        | 15            | 17           |
| 12   | 17   | 195  | 125     | 4          | 5           | 3       | 65        | 15            | 17           |
| 13   | 17   | 210  | 125     | 5          | 5           | 3       | 70        | 15            | 18           |
| 14   | 17   | 225  | 150     | 5          | 6           | 3       | 75        | 15            | 19           |
| 15   | 18   | 240  | 150     | 5          | 6           | 3       | 80        | 15            | 19           |
| 16   | 18   | 255  | 150     | 5          | 6           | 3       | 85        | 15            | 19           |
| 17   | 18   | 270  | 150     | 6          | 6           | 4       | 90        | 16            | 20           |
| 18   | 19   | 285  | 200     | 6          | 7           | 4       | 95        | 16            | 21           |
| 19   | 19   | 300  | 200     | 6          | 7           | 4       | 100       | 16            | 21           |
| 20   | 19   | 315  | 225     | 6          | 7           | 4       | 105       | 16            | 21           |
| 21   | 20   | 330  | 225     | 7          | 7           | 4       | 110       | 17            | 22           |
| 22   | 20   | 350  | 250     | 7          | 8           | 4       | 116       | 17            | 23           |
| 23   | 20   | 375  | 250     | 7          | 8           | 4       | 125       | 17            | 23           |
| 24   | 21   | 400  | 300     | 7          | 8           | 4       | 133       | 17            | 23           |
| 25   | 21   | 425  | 300     | 8          | 8           | 4       | 141       | 18            | 24           |
| 26   | 21   | 450  | 325     | 8          | 9           | 4       | 150       | 18            | 25           |
| 27   | 22   | 475  | 325     | 8          | 9           | 4       | 158       | 18            | 25           |
| 28   | 22   | 500  | 350     | 8          | 9           | 4       | 166       | 18            | 25           |
| 29   | 22   | 550  | 350     | 9          | 9           | 4       | 183       | 19            | 26           |
| 30   | 23   | 600  | 400     | 9          | 10          | 4       | 200       | 19            | 27           |

### How to use this chart

## Sample Ships

### Starships of the UTE

### Starships of the Free Council

## Starship Adventures

- Patch Repair
- Recharging and Refitting

Over time, wear and tear on a ship accrues, forcing adventurers to temporarily abandon their pursuits to recharge and refit & repair their ships.

- Recharging

As long as a ship has the requisite crew, they can conduct makeshift repairs and the systems of the ship can reset and recharge themselves without the ship having to dock. Recharging the ship requires a workforce as shown in the Starship Size Equipment Workforce table, and takes 1 hour.

If conducting repairs is interrupted for more than an hour, the workforce must begin recharging again for the ship to gain any benefit from it.

Once recharging is completed, a crewmember can attempt to spend one or more Hull Dice by making an Intelligence (Mechanic’s kit) check. On a roll of 10 or less, you roll the Hull Die twice and take the lesser amount. On a roll of 11 to 20, you roll the Hull Die normally. On a roll of 21 or higher, you roll the Hull Die twice and take the greater amount.

Whenever a Hull Die is spent to regain hull points, a crewmember rolls the die and adds the ship’s Constitution modifier to it. The starship regains hull points equal to the total. The crew can decide to spend an additional Hull Die after each roll.

Additionally, all shield points are restored at the end of the recharging period. If using the **Optional** System Damage rules, the crewmember can repair a damaged system by making an Intelligence (Mechanic’s kit) check DC 10, on a success the system is restored to Reliability 1, on a roll of 21 or higher they restore two systems to Reliability 1, if only 1 system is damaged they restore it to full Reliability.

- Refitting

Refitting is a period of extended downtime that requires docking at a spaceport or shipyard. Refitting costs a number of chits proportionate to the number of hull dice missing. The amount is 100 chits per hull die multiplied by the Starship Size Upgrade Cost table. Refitting requires a workforce as shown in the Starship Size Upgrade Workforce, and takes an amount of time depending on the size of starship, as shown in the Starship Size Refitting Time table below.

At the end of refit & repair, a ship regains all lost hull and shield points, expended Hull Dice and Shield Dice, and its system damage level is reduced by 1.


Table: Starship Upgrade Time/Cost

| Starship Size | Time     | Upgrade Workforce | Avg Cost (100ch day * Ship Size) |
| :------------ | :------- | ----------------- | -------------------------------- |
| Drone         | 2 hours  | 10                | 10ch + Parts                     |
| Small         | 8 hours  | 20                | 75ch + Parts                     |
| Medium        | 1 day    | 30                | 330ch + Parts                    |
| Large         | 3 days   | 40                | 1320ch + Parts                   |
| Huge          | 1 week   | 50                | 3850ch + Parts                   |
| Gargantuan    | 1 month  | 500               | 33,000ch + Parts                 |
| Collosal      | 2 months | 1000              | 102,000ch + Parts                |

- Cost is calcualted at (Time * Slip Fee for Docking) + (Time * Workforce)

- Primary System Failure
In some instances, primary systems can experience failure. When primary systems fail, an integrated emergency back up will activate. This back up can continue running the starship, provided there is adequate fuel, for 24 hours. At the end of the 24-hour period, primary systems fail, causing all electrical systems, including life support to fail.

Once a ship’s primary systems fail, all functionality of the ship ceases to function. If the ship can be towed to a shipyard, it can still be repaired, however.

- Repairing Primary Systems

If the ship’s primary systems had failed at the start of refit & repair, they can be repaired during that refit & repair, increasing the cost but not the time.

Repairing primary systems costs a number of chits proportionate to the ship’s maximum number of hull points. The amount is 10 chits per hull point multiplied by the Starship Size Upgrade Cost

- Food and Refuel

- Ships need to refuel. They burn 1 Unit of Fuel per day in space, 1 per hour in atmosphere and 1 per jump.
- Crew eats 1 Portion of food per crew per day so a crew of 100, eats 100 food per day
- It is common to carry enough food for 180 days in space, Gargantuan and Collosal ships carry a years worth of food

| Size | Fuel(u) | Cost Ch per unit | Food Required (⬢10) |
| ---- | ------- | ---------------- | ------------------- |
| D    | 5u      | ⬢10              | Max crew x 180      |
| S    | 10      | ⬢20              | Max Crew x 180      |
| M    | 30      | ⬢50              | Max Crew x 180      |
| L    | 300     | ⬢75              | Max Crew x 180      |
| H    | 600     | ⬢100             | Max Crew x 180      |
| G    | 1800    | ⬢200             | Max Crew x 360      |
| T    | 3000    | ⬢500             | Max Crew x 360      |

## Starship Conditions
Conditions alter a starship’s capabilities in a variety of ways and can arise as a result of a power, a starship feature, or some other effect. Most conditions, such as blinded, are impairments, but a few, such as invisible, can be advantageous.

A condition lasts either until it is countered or for a duration specified by the effect that imposed the condition.

If multiple effects impose the same condition on a starship, each instance of the condition has its own duration, but the condition’s effects don’t get worse. A starship either has a condition or doesn’t.

Any conditions that reference the ship also apply to any crew members when they take actions involving the ship. For instance, an ionized ship has disadvantage on attack rolls. Consequently, a deployed gunner would have disadvantage on attack rolls with a ship weapon, but not with their own weapons.

The following definitions specify what happens to a ship while it is subjected to a condition.

- Blinded

  - A blinded ship can’t see and automatically fails any ability check that relies on sight or the ship’s sensors.
  - Attack rolls against the ship have advantage, and the ship’s attack rolls have disadvantage.

- Disabled

  - A disabled ship can’t communicate with external sources more than 1,000 feet away.
  - A disabled ship can’t take actions or reactions.
  - A disabled ship has 4 Slowed Levels.

- Ionized

  - An ionized starship has disadvantage on attack rolls and ability checks.

- Invisible

  - An invisible starship is impossible to see without the aid of powers or a special sense. For the purpose of hiding, the starship is heavily obscured. The starship’s location can be detected by any noise it makes or any tracks it leaves.
  - Attack rolls against the ship have disadvantage, and the ship’s attack rolls have advantage.

- Shocked

  - A shocked starship can’t take reactions.
  - On its turn, a crewmembers on a shocked starship can take either an action or a bonus action, but not both.

- Slowed

  - Some abilities, effects, and hazards can lead to a special condition called slowed. Slowed is measured in four levels. An effect can give a ship one or more levels of slowed, as specified in the effect’s description.

If an already slowed ship suffers another effect that causes it to be slowed, its current Slowed Level increases by the amount specified in the effect’s description.

An effect that removes slowed reduces its level as specified in the effect’s description, with all slowed effects ending if a ship’s Slowed Level is reduced below 1.

| Level | Effect                                                        |
| :---- | :------------------------------------------------------------ |
| 1     | Speed reduced by 150 feet                                     |
| 2     | Speed reduced by 250 feet                                     |
| 3     | Speed reduced by 300 feet                                     |
| 4     | Speed reduced to 0, and can’t benefit from any bonus to speed |

- Stalled

  - A stalled ship is disabled (see the condition).
  - Any active features controlled by the ship, such as a Tractor Beam or Gravity Well Projector, automatically end.
  - The ship automatically fails Strength and Dexterity saving throws.
  - Attack rolls against the ship have advantage.

- Stunned

  - A stunned ship has 4 Slowed Levels.
  - The ship automatically fails Strength and Dexterity saving throws.
  - Attack rolls against the ship have advantage.

- System Damage

  - See "System Damage"

If a ship with system damage suffers another effect that causes system damage, its current level of system damage increases by the amount specified in the effect’s description.
A ship suffers the effect of its current level of system damage as well as all lower levels. For example, a ship suffering level 2 system damage 1 Slowed Level and disadvantage on ability checks.

An effect that removes system damage reduces its level as specified in the effect’s description, with all system damage effects (except for “used”) ending if a ship’s system damage level is reduced below 1.

Finishing maintenance reduces a ship’s system damage level by 1.

- Tractored

  - A tractored ship has 4 Slowed Levels.
  - The condition ends if the tractoring ship is disabled (see the condition).
  - The condition also ends if an effect removes the tractored ship from the reach of the tractoring ship or effect.

- Used
- A used starship’s value is reduced by half.
- When a deployed crew member on a used starship rolls a 1 on an ability check, attack roll, or saving throw, they must make a destruction saving throw. If the roll is 10 or higher, they succeed. On a failure, the ship suffers 1 level of system damage.

## System Damage
In order to make for more fast, and visceral combat operations Starstriders uses a System Damage Track, in conjunction with Structual Integrity and Reliability Ratings.

### Reliability Rating
Every system that can be damaged as part of this system as a Reliability Rating. Shields for example do not, but Weapons do. A reliability rating indicates how many hits the system can take before it goes offline requiring a check to bring it back online. If the rating has a "+" next to it then it gets a Free hit it can ignore before reducing it. 

> Setting Designer
> As a GM I use Index cards for enemy ships, and my player(s) have an Index card with each of their ships systems. We use a single box [ ] for each point of reliability, we mark one off when the system is damaged. As we play a Pulpy style nothing especially terrible happens as they are damaged except when they hot 0 they are offline, and can be brought online with checks, if they take another hit after offline they are destroyed and will have to be repaired at a station during Refit.

## Structual Integrity
Structual Integrity indicates how well made a ship is. It might have 200 Hull Points but if it loses structual integrity the ship is done. This makes combat much more dangerous so I suggest a GM think carefully before implementing it.

While a ship’s hull points measure its effectiveness in combat, a ship’s structural integrity (referred to as SI), measures the overall endurance of the ship in regards to stress and system damage. The more damage a ship takes, the less likely the whole thing will hold together. Every ship has an SI score when its stats are calculated. When a ship loses SI, its overall structure is severely damaged, and can only be regained during a full repair or through special powers and items. A ship that is reduced to 0 SI is destroyed.

A ship loses one point of SI whenever any of the following occurs.
- The ship fails a system shock roll.
- The ship takes damage from a single attack that is equal to or greater than half its hull point maximum.
- The ship takes damage after being reduced to 0 hp.

Each time a ship loses SI, roll a d20 and consult the System Damage Track table below. The result determines the effects on the ship due to the loss of SI. These effects are cumulative and last until the ship undergoes a patch or full repair

### System Shock
When a ship takes a critical hit, in addition to taking the additional damage, the target’s technician must make a system shock roll, which is an Intelligence saving throw versus the attacker’s save DC (8 + Attackers Prof Mod + Attacking Ships Wis Mod). If failed, the ship’s systems are affected, causing the ship to lose a point of structural integrity.

### Being Reduced to 0 Hull Points
A ship that is reduced to 0 hp is completely disabled. It cannot move nor can any maneuvers be performed with the ship’s systems. If a ship starts its turn with 0 hp, the technician must make an Intelligence saving throw against a DC equal to 15 minus the ship’s current SI score. Each failed save reduces the ship’s SI by 1. A ship that is reduced to 0 SI is destroyed.

### System Damage Track Table
| D20 Roll | Effect                                                                                    |
| -------- | ----------------------------------------------------------------------------------------- |
| 1        | Reactor hit, decrease Reactor Condition by 1                                              |
| 2-4      | Weapons, Roll 1d6-1 (min 1). Weapons on that Arc are damaged, reduce its reliability by 1 |
| 5-8      | Sublight Engines                                                                          |
| 11-12    | Conduit Blows out, but no other negative effects                                          |
| 13-14    | Jump Drive                                                                                |
| 15-16    | Sensors                                                                                   |
| 17-18    | Computer Systems                                                                          |
| 19-20    | Life Support                                                                              |
|          |                                                                                           |

### Systems Reduced to 0 Reliability
If a system is reduced to 0 Reliability, the system is offline. It can be brought back online using the Patch Repair rules in Starship Adventures. 

If a system is already at zero and is hit again the system is completely disabled, it cannot be repaired at all without a full refit and repair.

- **Life Support**: Should Life Support fail the ship will survive for 24 hours + 1 hour for every point of Strength Mod the ship has. 
- **Jump Drive**: Should the Jump Drive fail entirely, a ship can call for help, or it can attempt to use it's Sublight Engines (if they are working). Some Huge or Larger ships carry a backup Jump Drive
- **Sublight Drive**: Should the Sublight Drive be disabled, the ship can still use the Jump Drive unless it is also offline

### Reactor Condition
Starships have a reactor, a Power core that provides power to the ship. These are very stable devices, but combat is not healthy for them. This is an optional rule.

| Condition | Effect                                                                                                                                                                                                       |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 10        | None - Reactor Stable                                                                                                                                                                                        |
| 9         | Random System Feedcback, roll on System Feedback Table                                                                                                                                                       |
| 8         | Power output reduced by 25%, you might need to cut power to some systems, yellow lights will begin flashing letting people on board know the Reactor is being damaged                                        |
| 7         | Random System Feedcback, roll on System Feedback Table                                                                                                                                                       |
| 6         | Power output reduced by 50%, you might need to cut power to some systems, there are now red lights with alarm klaxons going off on the ship to alert people to danger                                        |
| 5         | Random System Feedcback, roll on System Feedback Table                                                                                                                                                       |
| 4         | Everyone on board takes Radiation Damage 2d8 + ships StrMod Radiant Damage                                                                                                                                   |
| 3         | Random System Feedcback, roll on System Feedback Table                                                                                                                                                       |
| 2         | Everyone on board takes radiation damage (2d8 + (ships StrMod Radiant Damage x 2), The ships AI is now telling everyone non-essential to abandon ship the core is critical                                   |
| 1         | Power output reduced to 0% The ship is in emergency power. The AI will now begin evacuation of everyone on board, and activate the Emergency autopilot towards the nearest star                              |
| 0         | Core Overload. The Core is destoryed everyone within Ships Size Category x 2 Hexes of the ship will take (Ships Strength D6) + (Ships Con Mod x 10) in half Radiant and half Fire damage. Ship is destroyed. |

#### Reactor System Feedback
| D6 Roll | System To Be Affected |
| ------- | --------------------- |
| 1       | Life Support          |
| 2       | Weapons               |
| 3       | Sublight Drive        |
| 4       | Sensors               |
| 5       | Computer Systems      |
| 6       | Jump Drive            |


> Setting Designer
> Credit where Credit is due, I borrowed this idea from Esper Genesis.

---
title: "#048 An Architectural Approach to Level Design - Chapter 5 - Communicating through Environment Art"
date: 2025-11-29 00:00:00 -0400
categories: [Game Design, Notes]
tags: [Game Level]
---

Game levels utilize sensory information (visual and auditory) to connect with players.

- Different teaching methods present in modern games
- How to utilize art assets in such a way that the player associates them with meaningful information, and how they can be organized to teach players through direct or indirect methods
- How to use visual information to turn game levels into spaces of information that create feelings of certainty and uncertainty in players

## TEACHING THEORIES FOR GAME LEVELS
This chapter will reinforce three models of teaching commonly considered by game designers - the operant conditioning model, the Montessori method, and constructivism - as the framework of our visual communication methodology.

### Behavior Theory and Operant Conditioning
**Classical conditioning:** Pavlov would ring a bell before feeding his dogs, thereby causing them to salivate every time he rang a bell.

**Operant conditioning** involves changing voluntary actions of subjects via positive and negative reinforcements, as well as punishments.

> Skinner box

Skinner himself argued for a methodology that avoided emphasis on lectures or tutorials, but rather on breaking large tasks into a series of smaller ones. As each task is performed, correct actions are reinforced so the student learns the proper way of performing his or her tasks.

> tutorials for games

The Skinner box model can be used to describe the repetition of one singular action over and over again.

> As such, it has been used as a derogatory term for games in the mobile free-to-play market that require players to wait extended periods of time to do simple actions.

### Montessori Method
> The world didn’t want him to fail here. It was pushing him, but gently.
> — *THOMAS WAS ALONE*, MIKE BITHELL

Game design is a second-order design problem, meaning that designers are communicating with players indirectly through their games.

Montessori views of games support the development of player skill and problem solving over the course of an entire game. In a game’s early puzzles, players learn the extent of their avatar’s movement capabilities before these capabilities are tested in later, more complex, puzzles.

This method of player-learning can focus early levels on teaching players how to deal with obstacles individually, and then mix and match them later to create more complex puzzles.

> This is especially useful if designers have created a set of modular gameplay assets that they can simply mix and match within their game engine environments.

This outlook on teaching in games differs from the operant conditioning model in that it does not directly address reinforcements or punishments as outcomes to solving in-game situations.

> The skill gates discussed in Chapter 2, where players cannot progress until they learn the ability that lets them overcome a particular obstacle, are examples of this kind of teaching. Skill gates are self-reinforcing, as players are simply stuck if, for example, they do not learn that jumping is a way to pass over a block that is in their way.

### Constructivism
Concrete experience, observation and reflection, forming abstract concepts, and testing in new situations

In Game: attempting to overcome an obstacle, observation and reflection of play outcome, forming strategies, and testing new strategies.

For designers:
- create interactive environments and challenges for players to experiment with
- set up rewards to reinforce mechanics
- provide non-severe punishments, players should be only set back to a point where they can comfortably retry a challenge

- **Operant conditioning**: reinforce gameplay mechanics through applications of rewards and other positive game outcomes for success and through punishments for failures.
- **The Montessori Method**: a framework for understanding how to structure a series of puzzles or challenges over the course of a game so that players can deduce solutions by recognizing elements of previous challenges, even if they are used in new ways.
- **Constructivist methods**: structure challenges, feedback, and punishments in such a way that players are motivated to iterate their play to overcome or master gameplay challenges.

## SYMBOLS AND VISUAL DESIGN IN GAMES
The pairing of visual art and procedural behaviors in game objects allows players to build strong associations between game objects and gameplay mechanics. These objects therefore become **symbols** of the gameplay mechanics they represent.

### Implementing Symbols in Games
Prefabricated objects have consistent behavior and the player will eventually build a literacy of their havits as defined by their scripted behaviors.

For environment art-intensive games, it is important to establish what portion of the scenery is a gameplay symbol and what is simply environment art.

> L.A. Noire: uses gold color to distinguish interactive buildings from non-interactive buildings.

Two rules when building environmental symbols in games:
1. Each symbol must have a unique appearance, even from similar environment art objects.
2. Each symbol must be repeated so the player learns what it means through repetition.

### Teaching with Symbols in Games
The repeatability of prefabricated game objects used as gameplay symbols allows these objects to become enforcers of the previously studied teaching methods: operant conditioning, the Montessori Method, and constructivism.

#### Introducing Symbols
Super Mario Bros. and Super Meat Boy: introduce symbols in the form of actual game objects or level geometry arrangements by allowing players to interact with them through their avatar’s abilities.

SWARM!: introducing an unconventional core mechanic to players: luring enemies into traps instead of fighting them directly. This mechanic was further used to unlock doors that would open when all enemies in an area were defeated.

To teach the relationship between the player, enemies, and environmental puzzles:
1. Introduced the enemies far from any traps to communicate that the player could not directly defeat them with the default character.
2. Enemy spawn points were set up in an area surrounded by traps, so players could watch the enemies hit the traps and explode.
3. The player was put in a situation where he or she could lead the enemies into the traps, which would open a door.

> The three pieces were all located within one screenshot’s view of each other so players could easily see their relationship.

#### Symbols as Guides
Symbols are important tools not only for introducing mechanics early, but also for conveying the message of **what actions to take** throughout entire games.

> Portal:
> 1. There are caution signs at the beginning of the game’s test chamber puzzles that describe what hazards are inside. As players visit new rooms, see the symbols, then play the rooms themselves, they learn which symbols correspond to specific mechanics.
>
> 2. Another layer of symbol occurs within the level geometry itself, where specific layouts of wall panels and masses are arranged according to the metrics of specific actions. As such, a player who enters a room and sees signs that indicate inertia-based puzzles, and then encounters the deep pit, wide canyon, and tilted wall panels consistent with the game’s inertia puzzles will know what actions to take.

As players learn what each symbol means, they will train themselves to search for them as indicators of what to do next in your game levels.

### Designing and Placing Symbols for Effective Communication
Good principles of visual communication are vital not only for the aesthetic quality of each symbol, but also to make them stand out from other, non-symbolic pieces of environment art.

#### Basic Color Theory
Color is a vital tool for communicating with the player.

> Reasons:
> - the ways in which colors relate to one another
> - the emotional or metaphorical associations colors carry

**Color Model**
Color models for understanding color.
1. Hue, saturation, and brightness (HSB) model
2. Additive color model and the subtractive model
   1. Additive color is based on primary colors of red, blue, and green.
   2. The subtractive model is based on two different sets of primary colors: red, yellow, and blue (RYB), or cyan, magenta, and yellow (CMY).

**Color Wheel**
*Analogous colors*: groupings of three adjacent colors on the wheel, can create a harmonious atmosphere based on a particular mood.
*Complementary colors*: colors opposite one another on the color wheel, can create a powerful effect — contrast.

**Metaphorical Association**
blue and purple: a cold feeling / red and orange: a warm feeling
red: love
blue: sadness
yellow: happiness
green: health

Be aware of **cultural differences** and **accessibility**.

#### Contrast
When a designer uses contrast, it is typically to call attention to the unusual element.

Contrast is important for creating landmarks not only in open worlds, but also within smaller areas: hallways, courtyards, and rooms.

#### Framing
Framing is a technique useful for enhancing the approach to important game environments: as the player moves through a gamespace, framed openings or expansions of space can enhance or foreshadow the player’s arrival at a point.

Turning environmental transitions into guideposts: Combined with environmental techniques such as color theory and contrast, pathways and arrivals in games can be easy to navigate and dramatic.

#### Rule of Thirds
The rule of thirds dictates that a designer should divide an image into thirds both vertically and horizontally (creating nine total divisions), and then place elements of the composition along the lines.

> A visual composition should allow viewers’ eyes to travel around the image rather than stay in one place.

Subjects placed at the dividing lines in a rule-of-thirds image will keep the viewer’s eyes moving around the image rather than staying at the center.

## ARCHITECTURAL FORMS AND TYPES
Symbolic associations that we can take from everyday architecture to guide players in games: *architectural types*.

Architectural types describe a building’s use through its *form*.

> In many cultures, buildings of the same use are built with similar forms. Over time, the form becomes associated with the building use, and a type is established.
>
> For example, a square building with a pitched roof is often understood as a house in Western cultures.
> Japanese gates, would conjure strong associations with temples to a Japanese person.

## CONTROLLING INFORMATION IN MEMORY PALACES
information + space = memorable communicative moments → memory palaces

Three levels of information contained within games:
- certainty
- uncertainty
- risk

### Certainty
A certain game is one in which the outcome is known.

Creating certainty within levels through consistent level elements can be a powerful tool for enticing players to explore or continue playing.

As players learn how to recognize symbols in games, they will also learn to recognize the conditions under which those symbols reveal themselves.

> *Super Metroid*: rooms for recharging weapons are placed near boss rooms, rewarding is after the boss room.
>
> *Dead Space*: save rooms are safe.

Patterns of certainty **communicate the game's pacing** to players, helping them to know when to unwind or prepare for big action.

> Certainty also gives designers the opportunity to make big **dramatic reveals**: a threat so powerful that it could destroy one of your save rooms or otherwise safe level zones.

### Uncertainty
Uncertainty describes a condition where the player has no concept of what to expect from a game.

Uncertainty in level design is a symptom of poor design or environmental art direction.

> If players find themselves at a T-junction within a level where they cannot surmise the best direction to go in next, they will feel that their choice may be arbitrary or that they may be forced to backtrack so they may see what lies in the direction they did not choose.

The reason for such confusing game areas is typically **bland and repetitive environment art**, or the **overuse of meaningless spatial configurations** (as opposed to the purposeful use of special rooms for saving, healing, and other repeatable symbolic forms).

In many games with experimental mechanics or that want to subvert gameplay standards, uncertainty can be a powerful tool for establishing trust between player and designer.

> Jumping off the cliff to a bottom players cannot see.
>
> *Jonathan Blow’s Braid*: Utilizes *time rewinding* ability to make the cliff scene an iterative experience of trial and error.
>
> *Don't Look Back*: Players can only move horizontally and jump, and few previous screens of the game are also very sparsely populated with objects.

### Risk
Uncertainty where the player knows the nature of the uncertainty is actually **risk**.

Risk is a modified version of uncertainty where the player has incomplete information on what lies beyond the point of uncertainty or can make inferences on what to do next based on outside information.

> potentially the most powerful of the three levels of information, as it is what makes games feel exciting.

In game levels, the play between risk and rewarding players, often discussed in the design of games as *risk–reward*, is of utmost importance in creating interesting emotional experiences.

Risk is created by playing communicative symbols (certainty) against new and ambiguous challenges (uncertainty).

### Putting It All Together in a Memory palace
The Hyrule of The Legend of Zelda: Breath of the Wild is a vast, expansive world with lots of embedded information. It is also a world constructed of very concise and readable communication systems. The beginning of the game is a plateau that the player character, Link, cannot leave without falling to his death. To escape, he must overcome a series of challenges and earn a hang glider to reach the fields below. Players start the game with Link inside a tomb within which he has been asleep for a century. He is guided through a few actions by a mysterious voice but can otherwise wander around the tomb freely and collect items inside. There are no enemies in this space, so the player can begin identifying objects and their functions: treasure chests contain upgrades, glowing pedestals open locked doors, short walls can be scaled, etc. Escaping the tomb leads players to a cliff from which Link sees a sweeping vista as the game’s camera orbits around him. While this impressive artwork is a reward, it contains several important pieces of information in the form of architectural landmarks that will later be goals: a volcano with lava spewing smoke and lava, a castle, and jagged cliffs. In review: by opening chests, this behavior is reinforced as the player is rewarded with gear. By solving a simple skill gate puzzle (unlocking a door), the player then gets a visual reward in the form of a dramatic reveal—another reinforcement.

When the player regains control of Link, he or she comes across several resources on the ground, a rudimentary weapon and some health items, and is prompted to pick them up. Based on their previous interactions with gear in the tomb, they can infer that they can interact with these new items in the same way. Now the player knows the basics of item-gathering and what benefits can be gleaned from stocking up. As the player explores, they encounters more new game objects: enemies who attack but yield rewards when defeated (new weapons and food), trees to climb, and eventually, temples.

While this sounds similar to many other open-world games, Breath of the Wild stands out in how often core symbols are repeated. The game features a few distinct towns, but the most common settlements are horse stables that are copy-and-pasted versions of one another. Rather than the strikingly different dungeons of previous Zelda games, every temple looks the same. Far from laziness on the part of developers, it instead makes what could be an unwieldly open world manageable. Players can find their next goals by recognizing architectural types. There are so many of these types in a single screen’s view of the Hyrule landscape that players find themselves always moving to their next goal. This makes unique areas: landmarks, towns, or level-sized creatures, even more enticing to players.

Compared to other open-world games, Breath of the Wild features a relatively small number of enemy types. Again, this serves the readability of the gamespace and the player’s condition in it. Small groups of enemies are easily beaten even by an ill-equipped player, making it certain that players can get gear from these groups. Later, players encounter larger groups that either require strong equipment or skill at sneaking to beat, but which are guarding large treasures. Uncertainty and risk come in to play here. Players understand that storming enemy camps is a high-risk/high-reward scenario but identifying the number of advantageous objects (red exploding barrels) vs. disadvantageous objects (strong silver-colored enemies) helps them assess that risk. Players who are overly rash in combat can use their mental understanding of the world’s symbols to hide or heal up before moving on.

Breath of the Wild’s take on Hyrule is, in terms of square footage, quite a bit bigger than a single palace, but the way it introduces then functions on identifiable information makes it a strong memory space. Smaller examples might include a space like Dracula’s Castle in Castlevania: Symphony of the Night, which is a literal palace with differently styled rooms. Players wandering these spaces can orient themselves by the character of the environment. They can also identify how to proceed next to see if the next architectural form in their way can be overcome by their current set of powers. On an even smaller scale, the Distillery District in Dishonored has a visual language that changes several times during the game. In different visits, hazards are added and deactivated and the player’s powers expand. Over time, strategies for navigating the District’s balconies and alleyways change as the language changes. The player has to modify their memory palace.

## SUMMARY
- teach players through different psychological methodologies.
- reusable art assets and architectural types can be used to communicate with players.
- Visual communication principles help make this process simpler, by allowing symbolic assets and geometries to stand out from other information.
- these symbols embody gameplay through the controlling of information, turning levels into emotionally evocative memory palaces.

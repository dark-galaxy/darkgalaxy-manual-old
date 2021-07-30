# Darkgalaxy Manual
Welcome to the Dark Galaxy Manual project.

This project exists to allow the community to assist with the creation of a game manual, in a generally central location, designed to ease general contributions, with a relatively quick update time.

Firstly, a couple of ground rules.
* Please keep all documentation as consise as possible, using clean understandable language.
* Use of screenshots is allowed, but please focus only on the item being documented (Win + Shift + S may help you)
* No direct instruction. We would like players to discover things for themselves, feel free to provide options, guides etc, but do not provide anything explicity telling them what they should do, such as build orders.

If you'd like to contribute, and are tech savvy, please feel free to submit pull requests to this repository, they'll be reviewed and added. If you're not so tech savvy, but would still like to contribute, feel free to submit pages via the [Dark Galaxy Manual Forum](https://forums.darkgalaxy.com/c/community-contributions/manual) where we'll get them merged into the main manual.

# Macros

The Dark Galaxy manual supports using 'Macros' to extract certain information from the game engine directly at build time (before deploying to https://manual.darkgalaxy.com), these macros exist in the format:

`[!<UNIT_NAME>:<LOOKUP_TYPE>:<RESOURCE>!]`
  
Unit names are the names as presented in-game, with underscores (\_) replacing spaces, and formatted in Camel_Case.

Lookup Type can be one of the following:
  * **CONDITION** - the amount of \<RESOURCE\> required to build a unit.
  * **UPKEEP** - The income of \<RESOURCE\> received per turn, assuming an abundance of 100%
  * **STORAGE** - The amount of units that can be stored in \<RESOURCE\> (eg. Soliders in Army_Barracks)
  * **CREATE** - A Create Condition, the resource can be any of the following:
    * **Turns** - The Number of Turns Required to build the unit.
  * **SCORE**  - Score of a unit, \<RESOURCE\> is the 'Score Group', can be any of:
    * **Asset** - The base score as presented in the turn
  
**The following list require \<RESOURCE\> to be set to 0, as it's unused**
  * **REQUIREMENTS** - A comma separated list of pre-requisites before this unit can be built.
  
**The following macros are boolean values, they will currently return 'Yes' for true, or a blank space for false. They also require \<RESOURCE\> to be set to 0.**
  * **RESEARCH** - Whether this unit requires research to be available.
  * **DEMOLISH** - Whether this unit can be destroyed.
  * **UNIQUE** - Whether more than one of this unit can be built at a location
  
This list will be updated with more macros, as and when they become available.


If you have any questions, feel free to poke us in #manual on [Discord](https://discord.gg/rmsMdPM).

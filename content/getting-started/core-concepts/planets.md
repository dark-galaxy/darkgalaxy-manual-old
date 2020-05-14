A planet is comprised of many elements, on this page, we'll take a look at a planet's various components and detail what they all are, and what they are for, and how they are used.

This page primarily focuses on the planet header, and describes the numbers and what they mean. For information on other parts of the planet page, check out the [Planets Section](/content/interface-gameplay/planets.md) in [Interface & Gameplay](/content/interface-gameplay.md).



## Planet Header

The planet header contains a lot of information about a planet, and looks a little like this:

![Planet Header](/assets/planet/planet-header.png)

A more compact version of this data is also available on the [Planet List](/content/interface-gameplay/planets/planets-list.md).

To help explain all the information provided, I'm going to break it down into smaller chunks and explain each part of the header.



## Basic Information

![Basic Information](/assets/planet/basic-info.png)

This section provides you with the following pieces of information (in order):

* The planets ![Coord][coord] coordinate (place in the universe)
* The planets Name
* The ![Worker][worker] Workers Available / Capacity / Income / Usage
* The ![Soldier][soldier] Soldier Count / Capacity
* The available ![Ground][ground] Ground Space
* The available ![Orbit][orbit] Orbit Space



The planets ![Coord][coord] coordinate is defined by it's place in [the universe](/content/getting-started/core-concepts/the-universe.md), and you set the name when you signed up / colonised / invaded, so those are straight foward. The ![Worker][worker] information is split into four pieces:

* The number of ![Worker][worker] Workers available, and ready to work, these can be used on Structures, Ships or Training
* The total ![Worker][worker]Worker capacity of the planet, this can be increased with Structures such as the Living Quarters
* The Amount of workers being generated per-turn, this can be influenced by structures such as Farms
* The number of ![Worker][worker] Worker's which are currently Occupied performing other tasks

![Soldier][soldier] Soldiers are there to help protect your planet, or be used for invasion. The numbers here show how many soldiers are present on a planet, as well as the maximum soldier capacity of a planet. The Army Barracks can be used to train soldiers, as well as increase the soldier capacity on a planet.

The ![Ground][ground] Ground and ![Orbit][orbit]  Orbit section define how much space you have on your planet. The building of structures will consume this space as they are built. Some structures are built on the ground, but after you've built your launch site, there are some structures which will sit in orbit, consuming space there.



## Resource Information

Now for the slightly more complicated part, resources and what they mean.

![Planet Resources](/assets/planet/resources.png)

This box defines how much of each resource you have stored, the combined output of all the structures on your planet, as well as the abundance.

The stored amount denotes immediately available resources for Construction, or Production. If you have a structure that requires 50,000 metal, it will not start until the stored number has reached 50,000. A higher output will result in reaching that number faster.

Output is the combined output of all resource producing structures on your planet, (mines, extractors, generators, et al). As each turn ticks, the number shown here is added to the Stored count for the planet.

The abundance value is a multiplier for structure output. In the example above, the ![Metal][metal]Metal Abundance is at 70%, from the [list of structures](/content/reference/list-of-structures.md) we know that a metal mine has a metal output of of ![Metal][metal]300, so the metal output of a Metal Mine on that Planet will be 300 / 100 * 70 = 210. Different planets have different abundances (some up to 150%), and having a higher abundance will result in a higher output on a planet, meaning a much higher resource output.



So that's the basic planet information, and how it relates to gameplay, hopefully now you'll be able to look at, evaluate, and understand planets with relative ease!





[coord]: /assets/misc/coords.gif	"Coordinate"
[ worker ]: /assets/resources/worker.gif "Worker"
[soldier]: /assets/colonists/soldier.gif "Soldier"
[ground]: /assets/resources/ground.gif "Ground"
[orbit]: /assets/resources/orbit.gif "Orbit"
[metal]: /assets/resources/metal.gif "Metal"
[mineral]: /assets/resources/mineral.gif "Mineral"
[energy]: /assets/resources/energy.gif "Energy"


# Core Concepts

## Game format

Dark Galaxy is a tick-based strategy game - that means turns update synchronously for all players over a fixed period of time.

* A `standard` round consists of ~2600 turns, with each turn lasting `1 hour`. This ends up with a round length of ~3 months.
* A `speed` round usually consists of ~3000 turns, with each turn lasting `1 minute`. This format produces a round length of 2-3 days.

Once the round is over, there is usually a brief cool-off period before the next round starts. The exact times above are subject to change at the discretion of the game admin. It has been known for some rounds to go on much longer than the above.

# The Universe / Navigation

The [Universe](/content/interface-gameplay/navigation.md) consists of 3 'rings' of galaxies.

* Centre gal (G1)
    * 64 systems, each containing 6 planets (total 384 planets)
    * Highest resource planets
    * Greatest competition
* Middle ring (G2-13)
    * 12 * 9 systems, each containing 6 planets (total 648 planets)
    * Average resource planets
* Outer ring (G14-49)
    * 36 * 4 systems, each containing 6 planets (total 864 planets)
    * Lowest resource planets
    * Least competition


## Planets

You'll start the game on your home planet - which is your safe space - and cannot be travelled to by any other player.

Your planet will produce [resources](/content/reference/list-of-resources.md), which you can then choose to spend on buildings, ships or soldiers.

As you get into the game, you'll be able to expand by colonising other uninhabited planets, or invading planets belonging to other players.


## Resources

There are 3 main [resource types](/content/reference/list-of-resources.md) in the game.

* ![Metal][metal] Metal
* ![Mineral][mineral] Mineral
* ![Energy][energy] Energy

In general ![Metal][metal] Metal and ![Mineral][mineral] Mineral are the most important, and will be what you spend when [building structures](/content/interface-gameplay/planets/building.md) and [ships](/content/interface-gameplay/planets/ship-yard.md).


## Ships

You'll build ships to visit other planets. The four ship types are:

* Combat/war ships
* Transport ships
* [Colonisation](/content/getting-started/colonisation.md) ships
* [Invasion](/content/getting-started/invasion.md) ships

See the full [ship list](/content/reference/list-of-ships.md) for full details of each ship type.


## Training

On each planet where you have constructed a Barracks, you'll have access to [train soldiers](/content/interface-gameplay/planets/barracks.md). Soldiers can be used to defend your planets and invade the planets of others.


## Research

Each tick your empire will produce 1 Research Point. This is a flat amount and does not increase with empire size.

Once you have accrued enough points you can choose to spend them to advance your empire. For full details of all research options please see the [Tech Tree](/content/reference/tech-tree.md).


[metal]: /assets/resources/metal.gif "Metal"
[mineral]: /assets/resources/mineral.gif "Mineral"
[energy]: /assets/resources/energy.gif "Energy"

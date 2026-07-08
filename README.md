# Alchemy

## Background

The year is 2104.  Magic is seeping into our universe.  Alchemists roam the Earth battling one another.

## Elements

The [four elements](https://en.wikipedia.org/wiki/Classical_element) are taken from classical philosophy.  

          Air
           |
    Fire ----- Water
           |
         Earth

## Resources

Symbols and colors for resources follow the [alchemical symbols](https://en.wikipedia.org/wiki/Alchemical_symbol).

| Element | Symbol | Color  |
| ------- | ------ | ------ |
| Air     | 🜁      | Yellow |
| Fire    | 🜂      | Red    |
| Water   | 🜄      | Blue   |
| Earth   | 🜃      | Green  |

## Types

Alchemy extends JRUCS base types:

* Object
  * Creature
  * Resource
  * Artifact
    * Win Condition
* Event
  * Spell

## Tokens

There is a token for each element:

* Fire - Inflict 1 damage
* Water - Prevent 2 damage
* Earth - Gain 🜁, 🜂, 🜄 or 🜃
* Air - Draw 1 card

The 5th element is sprit.  You start the game with 10 spirit tokens.  For each elemental in your deck, you start with 1 token of their type, up to 10.  If you take a damage, you lose a token of your choice.  If you end a phase with 0 tokens, you lose.  

## Abilities

* **Flying** - Can only be blocked by other flying creatures.
* **Formation** - Creatures with formation can combine into a single creature.
* **Ranged** - If a creature would destroy another creature without ranged comabat, its opponent deals no damage in combat as it is destroyed at range.
* **Swimming** - Creatures with swimming cannot attack unless the defending player controls a water resource.
* **Overflow** - Damage beyond defender's defense overflows.

## Properties of Elements

Cards within particular elements play to a particular theme.  Each element has a distinct character with paths to a victory unique to it.  Card design and art are unique for each element.

The overall genre is cyberpunk, though air is technology focused with it being more of a side thought in the other elements.  Fire and water focus heavily on magic.  Earth focuses on the natural world.

* **Air**
  * **Philosphy** - Technology, Ephemeral
  * **Power**
    * Knowledge - Draw Cards.  Benefits from hand size.  Shuffle and Search.  Deck->Play/Hand/Discard
    * Time - Add / Skip Turns.  Add / Skip Phases.  Tap.
    * Copy and Steal
    * Buff creature
  * **Win** - Weird things happening with turns and phases.  Killed by buffed creatures or drawing too many cards.
* **Fire**
  * **Philosphy** - Entropy and Anger
  * **Power**
    * Damage
    * Discard from hand
    * Destroy cards in play
  * **Win** - Direct damage and dragons, crippled by no cards in hand or in play.
* **Water**
  * **Philosphy** - Calm, Patience
  * **Power**
    * Defense
    * Prevent Damage and Destruction
    * Counterspell
    * Slow Things Down
  * **Win** - Crushed by whales that won't die, unable to damage player as their life total climbs.
* **Earth**
  * **Philosphy** - Nature, Persistent
  * **Power**
    * Resources
    * Regrowth - Discard->Play/Hand/Deck.  Untap.
    * Traps for card draw
  * **Win** - Crushed by expensive megafauna that keep coming back from the dead.

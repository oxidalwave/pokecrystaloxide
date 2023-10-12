# Pokémon Crystal Oxide [![Build Status][ci-badge]][ci]

This is a QoL improvement of Pokémon Crystal, based on the disassembly project. The goals are threefold:

 - Remain compatibility with vanilla saves. This includes trading/battling functionality.
 - All Pokemon introduced in Gold and Silver are catchable in Johto. Note that this does not mean that all 251 Pokemon are catchable; thanks to trade compatibility, missing Kanto Pokemon can be traded from Red or Blue.
 - QoL improvements including
   - Running Shoes
   - Reusable TMs
   - No need to teach HMs (Pending item)

# Pokemon Locations

## Houndour
Houndour has been added to the first floor of the Burned Tower. They have a 20% encounter rate at nighttime.

## Slugma
Slugma has been added to the first floor of the Burned Tower. They have a 5% encounter rate during the morning and daytime.

## Misdreavus
Misdreavus has been added to the Ruins of Alph. They have a 1% encounter rate at nighttime.

## Girafarig
Girafarig has been restored to their original encounter route from Gold and Silver.

## Mankey
Mankey has been restored to their original encounter route from Gold.  See Revised Routes.

## Mareep/Flaafy
Mareep and Flaafy have been restored to their original encounter routes from Gold and Silver. See Revised Routes.

## Revised Routes

### Route 33

| Pokemon    | Morning | Daytime | Nighttime |
| Ekans      | 30%     | 30%     |           |
| Bellsprout | 30%     | 30%     | 20%       |
| Mareep     | 20%     | 20%     | 10%       |
| Hoppip     | 10%     | 10%     |           |
| Pidgey     | 5%      |         |           |
| Wooper     |         |         | 30%       |
| Rattata    | 5%      | 10%     | 30%       |
| Zubat      |         |         | 5%        |
| Gastly     |         |         | 5%        |

### Route 42

| Pokemon    | Morning | Daytime | Nighttime |
| Mankey     | 30%     | 30%     | 30%       |
| Mareep     | 30%     | 30%     | 30%       |
| Flaaffy    | 10%     | 10%     | 10%       |
| Spearow    | 25%     | 25%     |           |
| Fearow     | 5%      | 5%      |           |
| Zubat      |         |         | 20%       |
| Golbat     |         |         | 5%        |
| Marill     |         |         | 5%        |

### Route 43

| Pokemon    | Morning | Daytime | Nighttime |
| Girafarig  | 30%     | 30%     | 30%       |
| Mareep     | 10%     | 5%      | 5%        |
| Flaaffy    | 30%     | 30%     | 30%       |
| Pidgeotto  | 20%     | 20%     |           |
| Noctowl    |         |         | 20%       |
| Farfetch'd | 5%      | 5%      |           |
| Venonat    | 5%      |         | 10%       |
| Venomoth   |         |         | 5%        |

## Special Cases

### Heracross
Haracross has been added to the Bug Catching Contest. Though Heracross is technically catchable in Johto, the method of obtaining it is incredibly roundabout. I may revert this in the future.

New rates are:
- Scyther: 4%
- Pinsir: 3%
- Heracross: 3%

### Qwilfish
Qwilfish has been left untouched. Catching Qwilfish requires the Super Rod, which is not available until Kanto--however, the goal is to make all new Pokemon catchable in Johto; it is not to make all Pokemon catchable before Kanto.

# Credits

Thanks to the below sources, used often as reference.

 - [Superegz's Pokemon Perfect Crystal](https://github.com/Superegz/Pokemon-Perfect-Crystal/tree/9ceb36e6cb1984b8ee1ac7378b5d366ff0705317)

# Building

This repository builds the following ROMs:

- Pokemon - Crystal Version (UE) (V1.0) [C][!].gbc `sha1: f4cd194bdee0d04ca4eac29e09b8e4e9d818c133`
- Pokemon - Crystal Version (UE) (V1.1) [C][!].gbc `sha1: f2f52230b536214ef7c9924f483392993e226cfb`
- Pokemon - Crystal Version (A) [C][!].gbc `sha1: a0fc810f1d4e124434f7be2c989ab5b5892ddf36`
- CRYSTAL_ps3_010328d.bin `sha1: c60d57a24bbe8ecf7cba54ab3f90669f97bd330d`
- CRYSTAL_ps3_us_revise_010710d.bin `sha1: 391ae86b1d5a26db712ffe6c28bbf2a1f804c3c4`
- CGBBYTE1.784.patch `sha1: a25517f60ca0e887d39ec698aa56a0040532a4b3`

To set up the repository, see [INSTALL.md](INSTALL.md).


## See also

- [**FAQ**](FAQ.md)
- [**Documentation**][docs]
- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]

Other disassembly and/or decompilation projects:
* [**Pokémon Red and Blue**](https://github.com/pret/pokered)
* [**Pokémon Gold and Silver (Space World '97 demo)**](https://github.com/pret/pokegold-spaceworld)
* [**Pokémon Yellow**](https://github.com/pret/pokeyellow)
* [**Pokémon Trading Card Game**](https://github.com/pret/poketcg)
* [**Pokémon Pinball**](https://github.com/pret/pokepinball)
* [**Pokémon Stadium**](https://github.com/pret/pokestadium)
* [**Pokémon Gold and Silver**](https://github.com/pret/pokegold)
* [**Pokémon Ruby and Sapphire**](https://github.com/pret/pokeruby)
* [**Pokémon Pinball: Ruby & Sapphire**](https://github.com/pret/pokepinballrs)
* [**Pokémon FireRed and LeafGreen**](https://github.com/pret/pokefirered)
* [**Pokémon Emerald**](https://github.com/pret/pokeemerald)
* [**Pokémon Mystery Dungeon: Red Rescue Team**](https://github.com/pret/pmd-red)
* [**Pokémon Diamond and Pearl**](https://github.com/pret/pokediamond)
* [**Pokémon Platinum**](https://github.com/pret/pokeplatinum) 
* [**Pokémon HeartGold and SoulSilver**](https://github.com/pret/pokeheartgold)
* [**Pokémon Mystery Dungeon: Explorers of Sky**](https://github.com/pret/pmd-sky)

## Contacts

You can find us on:

* [Discord (PRET, #pokecrystal)](https://discord.gg/d5dubZ3)
* [IRC](https://web.libera.chat/?#pret)

[docs]: https://pret.github.io/pokecrystal/
[wiki]: https://github.com/pret/pokecrystal/wiki
[tutorials]: https://github.com/pret/pokecrystal/wiki/Tutorials
[symbols]: https://github.com/pret/pokecrystal/tree/symbols
[ci]: https://github.com/pret/pokecrystal/actions
[ci-badge]: https://github.com/pret/pokecrystal/actions/workflows/main.yml/badge.svg

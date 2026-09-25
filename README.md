# Last Light

## Team Members

[Joshua Antonio-Rodriguez](https://github.com/JoshR011), [Jacob Krinsky](https://github.com/krin-j), [Qingzhe Song](https://github.com/Qingzhe-Song)

## Game Summary

*Last Light* is a first-person survival-horror shooter set across a dark outdoor zone and an abandoned warehouse. The player must explore the map, fight enemies, and complete four puzzles to collect the objects needed to escape. Limited visibility and scarce supplies make every encounter dangerous, while fast movement gives the player the tools to survive.

The warehouse contains the final boss and an optional generator. Restoring power makes the battle easier by illuminating the arena, but a player who reaches the warehouse without activating the generator can still attempt the fight in darkness.

## Genres

* First-person shooter
* Survival horror
* Puzzle

## Inspiration

### Left 4 Dead

*Left 4 Dead* is a major influence on the game's survival-horror atmosphere and objective-based exploration. Its dark environments, constant enemy pressure, and emphasis on moving through dangerous spaces inspire the tension we want to create in *Last Light*. Our game will build on these ideas by asking the player to explore hostile areas, locate resources, and search for puzzle components while remaining vulnerable to nearby enemies.

<img src="https://www.co-optimus.com/images/upload/image/l4d_horde_hallway.jpg" alt="Left 4 Dead gameplay inspiration" width="500"/>

[Left 4 Dead Steam Page](https://store.steampowered.com/app/500/Left_4_Dead/)

### Lethal Company

*Lethal Company* is the main inspiration for the flashlight system and the tension created by limited visibility. Its handheld flashlight makes light feel like a valuable tool while the player explores dark, unfamiliar environments. *Last Light* will adapt this idea by giving the flashlight limited battery power and placing replacement batteries throughout the map. The player must decide when light is worth consuming, making the flashlight an important resource rather than only a visual effect.

<img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1966720/ss_08fa3ef83b6eb70313119096f82285fa411f02e5.1920x1080.jpg?t=1775380053" alt="Lethal Company flashlight inspiration" width="500"/>

[Lethal Company Steam Page](https://store.steampowered.com/app/1966720/Lethal_Company/)

### DOOM (2016)

*DOOM* is the main inspiration for the game's movement and shooting. Its fast, fluid combat demonstrates how mobility can keep first-person encounters exciting and encourage the player to stay active. *Last Light* will adapt that feeling through sprinting, sliding, a midair dash, and hip-fire-focused weapons, while movement-based crosshair bloom will make accurate shooting more difficult when the player is moving quickly.

<img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/379720/ss_f989e793786bf1d6459da1139a484203efef1447.1920x1080.jpg?t=1750784856" alt="DOOM gameplay inspiration" width="500"/>

[DOOM Steam Page](https://store.steampowered.com/app/379720/DOOM/)

## Gameplay

* The player begins at a random location in the map's outdoor zone and must find the warehouse.
* Four puzzles and challenges are spread throughout the map. Completing them rewards the player with the objects needed to unlock the path forward and, ultimately, the final escape door.
* Access codes and other puzzle components must be discovered by exploring the environment, defeating enemies, and clearing challenges.
* The player can walk, sprint, slide, jump, and dash in midair. Moving creates noise that can alert nearby enemies, and sprinting increases the noise radius.
* Combat uses first-person aiming and shooting. Crosshair bloom reduces accuracy while the player is moving.
* A flashlight helps the player navigate dark areas but has limited battery power. Replacement batteries can be collected throughout the map.
* Health items restore lost health, while perks can provide upgrades such as life steal or increased weapon damage.
* The player can activate a generator to illuminate the warehouse before fighting the final boss. Skipping the generator is possible, but it makes the encounter more difficult.
* After defeating the boss, the player must use the objects earned from the four puzzles to unlock the final escape door.
* The game uses keyboard-and-mouse controls: WASD movement and mouse aiming, with additional inputs for jumping, sprinting, sliding, dashing, interacting, and toggling the flashlight.
* The interface will display a crosshair along with the player's health and remaining flashlight battery.

## Graphics

* First-person perspective with low-poly visuals inspired by classic shooters.
* A dark, low-visibility environment in which the flashlight and weapon fire provide important sources of light.
* Strong lighting contrast between the unpowered warehouse and the illuminated arena after the generator is activated.

## Development Plan

### Project Checkpoint 1-2: Basic Mechanics and Scripting (Ch. 5-9)

* Implement the core movement system:
  * Walking
  * Sprinting
  * Jumping and midair dashing
  * Sliding
* Create a basic blockout of the outdoor zone and warehouse to test scale, navigation, and movement.
* Implement the flashlight system:
  * Toggleable light
  * Limited battery charge
  * Battery pickups
* Add a simple HUD for the crosshair and flashlight battery level.
* Playtest the movement and flashlight systems together in the blockout and adjust their values as needed.

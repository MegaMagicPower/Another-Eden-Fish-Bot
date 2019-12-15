# Change Log

## 1.5
- Updated for game version 2.0.200.
- Fixed the jump rope minigame functionality. After trying it again myself from reports of people having issues, I now have the same problem as them when I wasn't before. Turns out the MSD threshold was way too low. I have no idea why now I'm suddenly getting a higher MSD than I was before, but it should hopefully now work for those it wasn't before, and likewise may break for those it was working for before. If it keeps giving people issues, I can add some debugging output and more variables to change so people can fix it themselves for their specific instance.

## 1.4.2

- Added jump rope minigame functionality

## 1.4.1

- Fixed Nilva

## 1.4

- Added Moonlight Forest, Snake Neck Igoma, Ancient Battlefield, and Zol Plains fishing pools.
- Updated Present time period to account for new starting map location after finishing the Ogre Wars arc.

## 1.3

- Fixed Greater Whale horror detection.

## 1.2

- Fixed calculation of fish points during bait purchase so it should now purchase FP baits in the correct quantity every time.
- Fixed a rare occassion where the Karek Swamp macro would break due to entering a battle right before getting to the lake.

## 1.1

- Fixed a case in Man-Eating Swamp where it would not re-enter the lake after a battle.
- Changed the logic to horror/lake lord detection to attempt to detect them for every battle, not just after a certain bait level. The previous method turned out to not work very well because fish occasionally respawn while fishing, so it was possible to catch a normal battle with horror level bait.

## 1.0

- Initial release
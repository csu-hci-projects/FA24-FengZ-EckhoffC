# FA24-FengZ-EckhoffC


# HW1

## Cody Eckhoff
* Created the new project
* Made the Ammo pickup
* Made the Health pickup
* Made the Spike Trap
* Made the Targets
* Made the UI

## Ziqiu Feng
* Made the level design for level 1
* Made the level design for level 2
* Applied the static meshes in the level designs
* Showcased the levels in the youtube video

## How does it work?
  Our game works by first loading the menu level, where you can hit play or quit, hitting play will send you to the first level where then you have to walk past the traps and shoot the targets to advance to the next level, once you hit all of the targets
  you will then be automatically teleported to the second level, which functions the same as the first level but is a different layout

## What was used
  We used all of the lab videos which allowed us to make most of the required assets, we used the corresponding book chapters as well, and then we also used the following items:
  * https://www.youtube.com/watch?app=desktop&v=PVgMkUwhtoM
  * https://www.youtube.com/watch?v=iUsZrBfWEIQ

## Meeting times
  * Set meeting at: Saturday at 1PM
  * Labs on Friday at 10am

  | Date | What was discussed |
  |------|--------------------|
  | 10/5  | Met each other and got aquanited, didnt discuss homework 1 yet |
  | 10/11 | Talked in class, got our hardware, and breifly dicussed the homework but not in detail |
  | 10/12 | Went over the HW 1 document and discussed possible ways of dividing the work |
  | 10/18 | Breifly met at lab but did not discuss HW1, decided to wait until next day |
  | 10/19 | Went over what had gotten done, what was left, and who exactly was going to do what  |
  | 10/25 | No Lab |

  # HW2
  
  ## Cody Eckhoff
  * Created the VR project
  * Created the teleportation area
  * added 3 Unique grab interactables
  * Added delayed reload feature
  * added Targets
  * Modifyed the level blueprint to track targets destroyed
  * Created unloackable no-teleport area
  * Created Win Level
  * Did gameplay demo

  ## Ziqiu Feng
  * Added pistol UI
  * Added ammo count decrement and spatial ui update
  * Added limits to stop shooting at 0 ammo
  * added basic reload function
  * Wrote most of AI report
  * Did blueprint detail video
  * Wrote readme explanation sections


  ## How does it work?
  Our game first starts off with the player actor spawning into the first VR level, where the player is confined to a nav mesh and the teleportation area is limited, the world has a pistol and 3 grabbale objects laid out in front of the player where they can grab using their VR controllers.
  The pistol has limited ammo (30 max) and every shot decrements the ammo count by 1, once the ammo count reaches zero the pistol does not spawn any more projectiles (cannot shoot), then the player has to press reload to get back to 30 ammo again to continue shooting.
  Beside the pistol and objects, there are three targets that the player must destroy by shooting them with the pistol. Every target takes two shots to destroy, the color of the target indicates how many times it's been shot. After 3 targets have been destroyed, the nav mesh locked area surrounding the targets is lifted, allowing the player to teleport freely. After all targets have been destroyed, the player passes the level and will be teleported to the win screen level indicating that they have won.

  ## What was used
  * We used all of the lab videos, specifically VR video 3-5 which gave us almost everything we needed to complete most of the blueprints. We used the corresponding book chapters, and also additional sources from unreal engine documentation.
  * https://dev.epicgames.com/documentation/en-us/unreal-engine/custom-events-in-unreal-engine
  * https://dev.epicgames.com/documentation/en-us/unreal-engine/sound-cue-editor-ui-in-unreal-engine



  ## Meeting times


  | Date | What was discussed |
  |------|--------------------|
  |  |  |
  |  |  |
  |  |  |
  |  |  |
  |  |  |
  |  |  |

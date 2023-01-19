# VR Redux
A collection of VR related tweaks, trying to make the game more `VR native`.

## New Interactions: 
* Doors, using lockpicks, crowbars and keycard hackers
* Doors, using a new virtual key and and keycard (representing the keys and keycards you have collected in the level) 
* CCTV recorder (punch the keyboard)
* Fire alarms

## Tiny Head Collider
* Shrinks the size of the head collider in VR, which makes agility actions (climbing, ledge walking, etc) less clunky

## Hip Holster (Pistols)
* Adds a second holster to your hip exclusively for pistols
* Drop pistol in about the right place to holster, move hand towards visible stashed pistol to retrieve
* Caveats
  * I haven't found a way to only pick up the gun on pressing 'grip', so for now, moving your hand to it will grab it every time :(
  * There's a small timer to reduce accidental double grabs. If you try to grab it straight after stashing, move your hand away and back again
  * The pistol that appears on your hip has to be hardcoded, so it won't be a model match for the pistol you actually bring
  * I've chosen to have the holster not actually attached to 47, as the positioning in VR is funky, it seems to work much better slightly off the body

## Recommended options:
* VR Collision fade to black: Off
* VR Head based movement: Off

## Other generic VR thoughts:
* I recommend not trying to play roomscale, the game really isn't designed for it at all - it's much smoother if you grab a chair and use pure virtual locomotion :(
* Throwing turns out to be ok, once you've got the hang of it. What I find works is: lock on with left trigger, and do a tiny sideways flick with you only your right hand - don't use your arm at all.
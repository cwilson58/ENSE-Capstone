# Roadmap
Note: subject to change

## MVP #1 – Playtest, Completed by November 20th​
    Demo Level Complete​
    Basic products (~2) that can be made within 2 machines​
    Contract Selections (~4 contract options)​
    Single lab layout (not yet random)​
    Post play screen implementation for pass and failure​
    Simple Audio assets (music nice to have, not need to have)​

## MVP #2 – Increase Randomness!  Completed by February 16th
    Create end of play breakdown and review screen (generate story) - Michael/Cameron
    Increase products​ (~4-6, with existing machines / add more)
    Add Machine animations​
    Sprites/Assets (undefined amount) - Nic

    Random level generation Step 1 - Julian, Nic
    Multiplayer Step 1 - Michael, Cameron

## MVP #3 – Implement RAMS! Completed by project day (April 6th?)
    Player has increased methods of failure (slips, trips, falls, explosions?)​
    Add more dangerous machines and recipes​
    Clients are now characters instead of abstract names​
    Mini Game implementation for 2 machines​
    Master list of unlockable items​

    Random level generation Step 2

## MVP #4 – Beta release
    Store implementation​
    6 Machines, 25 recipes (loose numbers)​
    Character augmentations / customizations​
    Tiered Machines​
    Meta store​
    In game store​
    Mini Game implementation for most machines​
    Music for menus, normal play and “near failure” states​

    Random level generation Step 3
    Multiplayer Step 2

## MVP #5 – Version 1.0, Increased Complexity!
    Stock is no longer infinite, it costs money (in-game, not real)!​
    Product Purity​
    Mini Game implementation for all machines​

## Random Level Generation​
    1. Static lab layout with zoning for types to separate machines and depots. 
    Depot zones don't have counter, but machine zones have them. Zone sizes and number of depots/machines/counters within them to be researched by implementer.
    2. Move zones to a random location within the static lab layout. Ensure zones are minimum 3x3 to allow walking around.
    3. Build lab layout around random zone placements.
    4. Build phase - can move machines, not depots.

    Note: Subject to change after research and proof of concepts

## Multiplayer
    1. Headed Server that clients can connect to over LAN.
    2. Headed & Headless Server over Internet

    Note: None of this has been researched and very likely subject to change
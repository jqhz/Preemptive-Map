# Jahzz's Preemptive Spike Map

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/15436815-55b6-4d1a-877b-a4516d32412d" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b6c81b09-fc41-4cf5-bed0-4b7e123d29b0" />

My map to help you identify the preemptive spike values of your different spawners.  

## Usage

For the *regular spikes*:  
Render distance: `8`   
Entity distance: `500%`  
Chunk borders: `off`  
Hitboxes (hovering): `on`  
Hitboxes (not hovering): `off`  

For the *mutlispikes*:  
Render distance: `14`   
Entity distance: `500%`  
Chunk borders: `off`  
Hitboxes: `off`  
*Note: the main difference in the multispawner spikes come from having hitboxes off, and the orientations that are setup in the map*

## Motive

Lama's Map made in 2022 is still usable as is, but we haven't had a new map for preemptive spikes since.  
Additionally, the map had a few minor subtleties that this map solves, notably:
- Lightning, oh my god the lightning
- Peaceful mode to prevent mobs spawning from the spawners
- Always South facing to make a 'chest behind' spike on spider spawners actually chest behind 
- Skeleton spawner close enough to not unload the entities (cows) on 8rd 

## Features
- Spawners
  - Silverfish
  - Cave Spider
  - Skeleton
- Chest variations for spawners
  - Pure (No chests)
  - Chest infront
  - Chest behind
  - TP pads to switch between the 3 spikes
- Cute cow zoo
- Tiny centralized hub
- Multispawner spikes
  - Silverfish + Cave Spider
  - Silverfish + Skeleton
  - Cave Spider + Cave Spider
  - Skeleton + Skeleton
  - Cave Spider + Skeleton
  - Skeleton + Cave Spider
- Multispawner permutation variations
  - Spawner infront
  - Spanwer behind
  - Spawner infront + Chest infront
  - Spawner + Chest behind

## Playground

This map is meant for exploration and experimentation. I only included what I thought was relevant for a boilerplate map to get your spikes.

Feel free to add more chests or more/less mobs in the pit to see what your spikes would look like on certain T valued strongholds, and with Hitboxes on or off, and with or without hovering blocks.

> [!NOTE]
> The spawners are south facing by intention. Since each of the spawners and chests are contained within the **same chunk**:
> 
> Chest Above, South, and East get `Chest Behind`  
> Chest Below, North, and West get `Chest Infront`
> 
> Vertical takes precedence. Then if they are on the same y-level, North/South. Finally, East/West.

## Installation Instructions
1. Open the **Releases** tab on the right side of the page
2. Download the latest `.zip` file of the map
3. Unzip the file  
   I recommend WinRAR or 7zip to avoid file issues
4. Open the unzipped folder and verify the structure  
   There must be **no folder inside another folder**
   If there is, drag the inner folder out
5. Move the map folder into the `saves` folder of you Minecraft instance
6. Start Minecraft and select the world. Minecraft Version 1.16.1

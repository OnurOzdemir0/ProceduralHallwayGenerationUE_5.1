# ProceduralHallwayGenerationUE_5.1

## Project Demo on YouTube 📺

Check out the project in action on YouTube:

[![Procedural Hallway Generation UE 5.1 Demo](https://img.youtube.com/vi/IqnP_dSTLzw/0.jpg)](https://youtu.be/IqnP_dSTLzw)


## Overview

This project is a real-time, procedurally generated hallway inspired by The Shining. It showcases a dynamically changing environment as the player moves through the hallway, complete with flickering lights, color transitions, and an evolving soundtrack.

![image](https://user-images.githubusercontent.com/94066846/226165812-843fb5bd-060a-4440-85d6-662cb54ffdb7.png)

![image](https://user-images.githubusercontent.com/94066846/226165711-15d8ce92-861a-425d-a4de-1d4b2f6a91fb.png)

## Blueprints

**Click** the image for better quality
### BP_BackgroundMusic:

![image](https://user-images.githubusercontent.com/94066846/226169015-c6dc168f-be01-4f0e-897b-fe7cba0a40f0.png)

### BP_MeshGenerator:

![image](https://user-images.githubusercontent.com/94066846/226169236-fc12d26c-a19c-4f31-abc8-8e6dec476659.png)
![image](https://user-images.githubusercontent.com/94066846/226169612-b2fdeb91-3542-4f91-8a9d-45f6ad902a2c.png)
![image](https://user-images.githubusercontent.com/94066846/226169795-adf63c25-43a5-4f9f-bc99-70630f4e79e8.png)
![image](https://user-images.githubusercontent.com/94066846/226170128-35ce3bb3-f0ce-4812-8c46-e4a54c86968b.png)



## Features
### As the player progresses:
- hallway sections are generated in real-time. 
- famous art pieces and 3D models are randomly selected. (after some point all of the art turns into the photo from The Shining)
- background music becomes more distorted and pitch gets lower.
- lights start to flicker, and gradually turn into red.

These are calculated using distance of the player's current location (achieved in Event Tick) to the player's first location (achieved in BeginPlay).


*the photo from The Shining: * ![image](https://user-images.githubusercontent.com/94066846/226166495-9a5b5afc-48af-44b9-84c1-8d99028e9db6.png)

## Credits and Acknowledgements

### Artwork
- The Creation of Adam
- Cupid's Hunting Fields
- Ocean Undulations Revealing Particles of Sand and Coral
- The Assumption of the Virgin
- The Veil of Veronica
- Overlook Hotel July 4th Ball Picture (The Shining)

### 3D Model
- [Protection of the Mother of God](https://sketchfab.com/3d-models/protection-of-the-mother-of-god-9da3a0c9a5f547e58d663016ea097bc8), uploaded by Virtual Museums of Malopolska

### Music
- Midnight, the Stars and You by Ray Noble and His Orchestra

### Materials
- MegaScan Materials

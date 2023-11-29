# Practical 9.2: Cinemachine & Particle System

In the last lecture, you learned about the Cinemachine system and the particle system. In this practical, you are going to further extend the haunted house scene to add some camera effects and particles

By the end of this practical you will be able to:

-	Implement a basic cinemachine camera
-	Add a dolly track and provide a flyover of the scene
- Add particles using the Unity particle system

To get started, open up your haunted house scene from practical 9.1  Don't worry if you didn't finish the practical, you can still use the scene provided from the 'StartingPoint' scene provided.


## Task 1: Cinemachine follow cam

Add a cinemachine virtual camera that follows the ghost. Note:

- You may need to disable your FPS camera to see the ghost camera
- Play around with the Cinemachine settings to the camera works off the speed of the ghost and tracks it

## Task 2: Introduction to the scene via flythrough

Create a multiple camera setup that showcases the following in order:

- The whole scene from top down view
- Zooms into the house
- Zooms back to the start location of the player

## Task 3: Player hint via camera with dolly 

Add a dolly track that, after the flythrough, tracks from the player to one of the hills on the map. 

This could silently hint to the player that this could be a safe spot even if they can't see the NavMesh (more in this next week in the game design lecture!) 

## Task 4: Particle effects

Add some particle effects to the scene. For example: 

- Cauldron bubbles
- Fire under the cauldron
- A ghostly shimmer behind the ghost
- Bright sparks on the cherry

You may wish to download some of the standard particle materials from the Standard Assets package. 

## Task 5: Optional Extensions

If you complete all of the above tasks before the end of the practical, or would like to continue to develop your skills in your free study time, then you should consider attempting the following tasks:

- Add a script and cameras such that you can switch from FPS view to ghost view (see https://fanzhongzeng78.medium.com/switching-cameras-in-unity-174ef13ec6e)
- Change the particles of the ghost or the cauldron when the player picks up a cherry (see https://docs.unity3d.com/ScriptReference/ParticleSystem.html) 


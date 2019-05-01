This zip file contains an example project where you can spawn cannonballs.  Press c to spawn a cannonball.

How to get here from the previous .zip
1. Add spawn cannonball blueprint to character
2. Add scene component to catapult
	a. It's better to do this inside the viewport, so that the scene is for sure inherited from the actor
3. Place the scene where the cannonball should spawn inside the viewport
4. Create cannonball
	a. Content Browser -> New Blueprint Class -> Actor
	b. Add sphere with cannonball material
	c. Simulate physics on sphere
5. Add spawn cannonball blueprint to catapult
6. If you want, add catapult blueprint logic to only spawn cannonball once
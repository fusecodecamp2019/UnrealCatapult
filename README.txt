This zip file contains an example project with a catapult that you can load.  Press e to load catapult.

How to get here from the previous .zip
1. Add collision to catapult body and arm
	a. Double click catapult mesh
	b. Collision -> Use Complex Collision as Simple
2. Create an empty actor as the catapult
3. Attach catapult body and arm meshes to the catapult actor
4. Place the arm in the upright position
5. Add box collision (Components -> Box Collision) to catapult actor
6. Resize the collision box to cover the entire catapult plus a bit
7. Add nextToCatapult variable to character
8. Create new blueprint class for catapult.  Save in Content/ThirdPersonBP/Blueprints
9. Add nextToCatapult logic to catapult
10. Add loadCatapult button to character
11. Add loadCatapult logic to catapult
# Homogeneous Volumetric Scattering

## Team Members: Justin Lam and Simone Wright

![blackSmoke](https://github.com/LiquidPeach/cse168-final-project/assets/44417069/b461ad9c-0b26-495a-9607-a9368794f12a)
![whiteSmoke](https://github.com/LiquidPeach/cse168-final-project/assets/44417069/6ae23e32-a63e-48d6-a36f-c4af199485ef)

## Documentation
We added a new material for volumetric objects and new commands for the test files `smoke` and `density`. `smoke` is a boolean that tells us whether or not the object is volumetric. `density` is the density of the material. We attempted to render the Cornell Box scene but with the two objects in the room as smoke. Unfortunately, we had trouble reconciling our implementation of next event estimation and Russian roulette with volumetric scattering. Thus, our rendered scenes fail to show the objects as smoke, and instead, render them as black and white.

What we plan to achieve can be seen in the image below:
![aaaa](https://x.com/i/status/1566126155484336128)

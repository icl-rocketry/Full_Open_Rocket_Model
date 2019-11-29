# Open-Rocket-First-Iteration-
First complete competition rocket layout.

Saving file as rockSim format has issues. OpenRocket model preferred.

When opening the rocket, the main motor may not show up, since it is a custom defined engine.
To add it, follow these steps:

1) Go to `Edit>Preferences`
2) In `General`, under user-defined thrust curves, click `Add`.
3) Select the `.eng` file from the same Github repo, and click `Add`
4) Click `Close` and restart openRocket and load Sporadic Impulse
5) In `Motors and Configuration`, click on Inner Tube #2 to add a motor
6) Search for `ICLR` which has a motor called N909, manufacturer ICLR
7) Load that motor into the appropriate Inner Tube.

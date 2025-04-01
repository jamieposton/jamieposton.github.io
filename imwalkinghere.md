---
layout: page
title: I'm Walking Here!
subtitle: Pedestrian Intent Recognition. Identifying Future Pedestrian Trajectory Using Machine Learning On-Board an Autonomous Vehicle
---

It's a long title, but it boils down to infering where a pedestrian is going to walk based on their posture at the time. If someone is standing at a crosswalk and facing away from the street, they're probably not going to cross. If someone is looking back and forth at cars, they're more likely to begin to cross the street. This information should allow an autonomous vehicle to predict their future tractory and plan accordingly.

For this project, I worked on a team with four other senior engineering students: Houston Lucas, Cayler Miley, and Gaetano Evagelista. We each had our specific areas that we focused on, but mainly worked together to solve issues and come up with solutions. My main focus was training a Recurrent Neural Network with a motion capture dataset. The network was given the full posture data of the motion capture figure and attempted to predict the location of the center mass a few frames into the future. As you can imagine, this worked better in some scenarios than others, and was ultimately not the model we ended up using for the final version of our project.

TODO: Add our group photo, and a photo of configuration/motion capture?

[Here's a link to a video capturing our final results.](https://www.youtube.com/watch?v=Ev3GRIP66KA) Be warned, there is a good amount of silly walking involved.

[And here's a link to the Github page.](https://github.com/cmiley/mkzintent) Unfortunately, a lot of my contributions were under Houston's GH account due to working on the same machine.

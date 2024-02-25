# SpongeGogh

## Inspiration
We were inspired by painters such as Pablo Picasso and Vincent Van Gogh, to make a robot that is able to take a realistic image and turn it into an abstract sketch. 
## What it does
Our image processing algorithm was built from the ground up and is able to take an image capture/file and turn it into a path for the robot to follow. SpongeGogh is initialized by remotely accessing the device's raspberry pi and running ```run.py```. It follows the path given by the image capture and draws it on the floor with a marker.
## How we built it
We built it with two servo motors, two wheels, a battery pack, a raspberry pi and a pihat. We also used a pre-made chassis and battery pack holder. As for the software, we relied on python packages sys, math, numpy, opencv and matplotlib.
## Challenges we ran into
We had issues with runtime in rendering the images, which we eventually solved by cutting down on the number of points in our contours. This also simplified and cleaned up the robot's motion. Additionally, not having access to a gyroscope caused there to be issues with turning precision.
## Accomplishments that we're proud of
We're proud of being able to take an image and convert it to a map. This was by far the most difficult part of the whole project, and we're glad that we could get it done with minimal runtime.
## What we learned
We learned how to remotely access a raspberry pi, and got a lot more accustomed to git. We also gained some experience working with the GPIO ports on the raspberry pi.
## What's next for SpongeGogh
As mentioned before, a gyroscope would really help to improve precision and make more complicated images. Additionally, we started working on (but did not finish) code for a servo to raise and lower the marker.

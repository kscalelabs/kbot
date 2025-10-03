# Mechanical Design

- See the CAD model for the robot [here](https://cad.onshape.com/publications/e15cf8edefacbba3009917c0/).
- Watch a teardown of the K-Bot hardware [here](https://www.youtube.com/watch?v=qhZi9rtdEKg)

The K-Bot is designed with the following principles in mind:

- _Easy to repair_: Robots break a lot, especially when they're moving around real environments. We designed the K-Bot to be easy for anyone with some amount of technical knowledge to quickly repair.
- _Easy to mass manufacture_: We want to make the K-Bot as accessible as possible to as many people as possible. We use with COTS components and designed the robot to be easy to mold.
- _Easy to upgrade_: Humanoid robots are a fast-growing field, and it is painful to have to upgrade an entire robot every time new components come out. To that end, we made the K-Bot modular and upgradable:
  - The hands can be easily swapped, using a lens mount interface, and piggyback onto the same 48 volt power and CAN bus lines that the arm actuators use.
  - The head can also be easily swapped out - the robot is basically a single USB device

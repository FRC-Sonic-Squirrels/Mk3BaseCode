# Mk3BaseCode
Contains bare bones code for a robot with Mk3 modules,

*When Cloning, make sure to use Clone(Recursive) as there is another repository attached to the Repo*

This code was provided by FRC Team 2910 Jack in the Bot and repurposed by FRC Team 2930 Sonic Squirrels for a 2021 off season Swerve Drive Project. 

Team 2930 would like to thank 2910 for their Generosity for allowing us to utilize their code. 

## CAN Ids

CAN Ids for the swerve modules are assigned as follows. Drive motors are in the range 1-9, steering motors in the range 11-19, and encoders in the range 21-29. The left front swerve modules CAN ids all end in 1. I.e they are assigned CAN IDs 1, 11, and 21 for the drive motor, steering motor, and steering encoder sensor respectively. Similarly the right front CAN ids end in 2, the right rear CAN ids end in 3, and the left rear CAN ids end in 4. Numbered clockwise starting with the left front.

## CAN Wiring

NOTE: On the first swervebot, the encoder CAN wires are blue and white, with blue being wired to the logical CAN yellow wire and white being the CAN green wire. This is counter-intuitive for most, so be aware if the CAN bus is wonky check this first.

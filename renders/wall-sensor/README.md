## Note ##

The schematics and board layouts currently in this directory are for illustration, and do not necessarily form part of the documentation.

When the boards are released, the full Eagle files will be made available in the repository.

Meanwhile, these files are presented for discussion and should not be regarded as definitive.

## wall sensors ##

The basic wall sensor board has three pairs of emitters and detectors. One pair points directly forwards to measure the distance to a wall ahead if there is one.

The two side sensors allow the robot to steer accurately in the maze and detect the presence of absence of a wall to either side. Both sensors will need to be used when following the IET figure eight maze course. For simple left- or right-wall following one or other side sensor can be omitted.

The emitters are placed above the board and the detectors are below. When mounted, the sensor board will need to be raised above the main board so that there is room for the detectors betwee the sensor board and the main board. Placingthe detectors like this will shield them both from ambient light and direct illumination by the emitters.

A single transistor is available to turn the emitters on and off. There is no provision to bypass this because the wall sensors are much less reliable if used with the emitters continuously illuminated.

Two visible LEDs are available for user feedback.

The emitter and indicator output pin assignments correspond with those on the line sensor board.

The sensor board does not overhang the mainboard outline ad so will not interfere with motion insde the maze. Builders may find that the steering control of the mouse in this configuration will be different to that in the line sensor configuration.


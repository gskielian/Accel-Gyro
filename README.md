Speed-Sensor 4 Martial-Arts + More
====

roadmap:
--------

1. getting speed data in 1-d (this is harder than I thought)
2. attaching bluetooth
3. adjusting for the gyroscope

Tree
----

Where stuff is:

```bash
.
├── lib
│   ├── I2Cdev
│   ├── MPU6050
│   └── Wire
├── MPU6050_raw
│   └── MPU6050_raw.ino
└── README.md
```


Installation:
-------------

1. Add the libraries within the `lib` folder to your `Arduino/Libraries` directory.
2. try out the example program


Specs:
------

## Velocity sensing mode

* light to track the velocity mapping red->low speed, violet->high speed
* sends data via bluetooth or something to a computer/Iphone/Android device

## Impact Sensing Modes

Measures the amount of impact

* How many pounds of force in your punch
* the speed of your punch?
* Sends data to the computer/Iphone/Android device

F &middot; &Delta; t = "weight transferred" (in physics speak it's the momentum transferred)

## Bag Sensing Mode

Tells you how heavy your punch is: the momentum transferred

and the max pressure by proxy with the force.


F/m = a/time_window




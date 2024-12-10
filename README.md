# RPiTank

Raspberry Pi Tank with Camera + Automatic Fire + Turret

A remote-controlled tank built with Raspberry Pi featuring camera streaming, automatic firing mechanism, and turret control capabilities

![image](https://github.com/user-attachments/assets/49d83c51-a807-4aab-a2bc-fa52a46898a5)

Features

    Directional control (forward, backward, left, right)
    Rotating turret with preset angles
    Automated Nerf gun firing system
    Live camera streaming via Flask server
    Object detection using TensorFlow Lite

Hardware Requirements

    Raspberry Pi
    Pi Camera Module
    2x Servo Motors
    Tank chassis with aluminum frame, wheels, and tracks
    2x 9V DC Motors
    Nerf Jolt
    L298N Motor Controller
    6x 9V batteries with clips
    Acrylic plate (for turret)
    Raspberry Pi battery pack
    Jumper cables (Male-to-Female and Male-to-Male)

Software Dependencies

    RPi.GPIO
    Flask
    TensorFlow Lite
    Object Detection Utils

Controls
Movement Commands:

    w: Forward
    s: Backward
    a: Turn Left
    d: Turn Right
    q: Stop

Turret Controls:

    j: 5 degrees
    k: 30 degrees
    l: 50 degrees
    m: 100 degrees
    f: Fire Nerf gun

Special Features

    Simultaneous driving and turret rotation
    Simultaneous driving and firing
    Live camera feed through Flask server
    Object detection capabilities

Demo: https://youtu.be/GivwsJPE8mc

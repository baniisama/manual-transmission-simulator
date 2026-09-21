# manual-transmission-simulator

A mobile friendly manual transmission driving simulator built as a single HTML file. It models clutch, throttle and brake pressure, gear shifting logic, engine RPM behavior including stalling, and simple vehicle physics on flat and uphill roads.

## Made by

banii

## How to use

Open `manual-transmission-simulator.html` in a mobile browser. No installation or server is required, it runs entirely client side.

## Features

Pedal pressure sliders for clutch, brake and gas, controlled with drag gestures rather than fixed steps.

A handbrake slider that holds its position once set.

A draggable gear stick that snaps into the nearest gear position on release, following a standard H pattern with reverse.

Two driving modes: a flat road and an uphill road with gravity based physics for practicing hill starts and hold and go maneuvers.

Realistic engine behavior including idle RPM, a torque curve, a rev limiter, clutch slip, and stalling if the clutch is released too fast without enough throttle.

A synthesized engine sound that changes pitch and volume with RPM and throttle, with a mute toggle.

All controls support simultaneous multitouch, so pedals and the gear stick can be operated with different fingers at the same time.

A warning message appears if the page is opened on a desktop browser, since the controls are designed for touch screens.

## Notes

The physics model is simplified for gameplay and learning purposes rather than an exact simulation of a real vehicle. Constants such as engine torque, gear ratios and hill slope were tuned so that a hill start is achievable with correct technique, that is, moderate revs combined with a gradual clutch release.

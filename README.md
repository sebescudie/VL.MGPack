# VL.MGPack

![patching-hard](doc/img/image.jpg)

This is the MacGyver pack, a collection of utilities I use for my daily patching experience

## Install

`nuget install VL.MGPack`

## What's inside

### VVVV

| Node      | Description                                            |
|-----------|--------------------------------------------------------|
| Framerate | Shows vvvv's framerate. Taken from VL.Skia's perfmeter |
| HasLoaded | Outputs `True` when vvvv has counted 10 frames         |

### System

| Node      | Description                                            |
|-----------|--------------------------------------------------------|
| GetEnvironmentVariable | Simply retrieves an environment variable  |


### Time

| Node        | Description                                                             |
|-------------|-------------------------------------------------------------------------|
| TimeCounter | Returns a `TimeSpan` giving the elapsed time since the node was created |


### Rectangle

|Node    |Description                           |
|--------|--------------------------------------|
| StackX | Stacks Rectangles next to each other |
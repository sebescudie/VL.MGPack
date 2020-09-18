# VL.MGPack

![patching-hard](doc/img/image.jpg)

This is the MacGyver pack, a collection of utilities I use for my daily patching experience

## Install

`nuget install VL.MGPack`

## What's inside

### VVVV

| HasLoaded | Outputs `True` when vvvv has counted 10 frames         |
|-----------|--------------------------------------------------------|
| Framerate | Shows vvvv's framerate. Taken from VL.Skia's perfmeter |

### System

| GetEnvironmentVariable | Simply retrieves an environment variable |
|------------------------|------------------------------------------|

### Time

| TimeCounter | Returns a `TimeSpan` giving the elapsed time since the node was created |
|-------------|-------------------------------------------------------------------------|

### Rectangle

| StackX | Stacks Rectangles next to each other |
|--------|--------------------------------------|
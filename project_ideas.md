# Project Ideas

This is an initial collection of project ideas, mainly to boot-strap your creativity, along with [existing projects](https://github.com/gwu-iot/collaboration/blob/master/inspiration.md).
Please add your own ideas here and contribute to the collective brainstorming!
For each of these projects, ask yourself "what are the sensors" and "what are the actuators", and brainstorm other project ideas from those capabilities.

## Sound source localization + targetted noise canceling

Multiple microphones spread around a room can perform localization and audio processing.
This requires each microphone to be connected to the same system, or for multiple systems to use a time coordination protocol to label when they receive a specific sound.
Central processing on these feeds of data can determine where the sound is coming from (in 2d), and speakers either can be dimmed in that location to enable a conversation to stay quiet, or used to broadcast specific sound waves to cancel the sound.

*Technology*:
- Global time synchronization
- audio processing
- speaker and microphone interfaces

## Environment sensing for efficient autonomous driving

[F1/10](http://f1tenth.org/) vehicles are autonomous and make decisions based on sensors on the vehicle.
What if the environment had an array of sensors that could feed information back to the vehicle?
Perhaps the sensors on the vehicle are unnecessary!
The goal would be to use very cheap sensors such as cameras, and IR/ultrasonic range-finding sensors.

A version of this uses a swarm of [`edumips`](https://www.youtube.com/watch?v=BIMb8D5RdGA) that don't have powerful sensor capabilities.

*Technology*:
- Integrating with an AV technology stack.
- Interfacing with sensors, processing the output, and sending it to the vehicle.
- Building a model about where the vehicle is from distributed sensors.

## Smart X

The grand tradition of IoT is to add "smart" to anything (i.e. to "X").
Smart coffee maker?
Smart doors?
Smart fridges?
What can you make "smart".
Note that there are quite a few definitions of "smart" for us to play with here.
Snark appreciated.

*Technology*:
- embedded system programming
- cloud interactions
- interaction between sensor suites and humans

## Edge cloud MQTT broker

MQTT is one version of a universal communication medium between IoT devices.
It uses a pub/sub model and relies on a broker to perform the pub/sub.
One potential use of edge computing is to place this broker in the edge, and have it mediate communication with low latency.

What IoT system would use this support?
Are there low-latency improvements to MQTT that you can propose?
Are there edge architectures that enable this application?

*Technology*:
- MQTT stacks (see `wolfmq`)
- Edge architectures
- MQTT servers
- IoT systems requiring low-latency communication

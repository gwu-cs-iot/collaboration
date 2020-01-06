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

*Focus*:
- Real-time sound processing and interaction

## Edge-driven time synchronization

[NTP](https://en.wikipedia.org/wiki/Network_Time_Protocol) and related protocols provide relatively fine-grained synchronization in a distributed system.
It is quite powerful for all IoT devices to have a shared notion of time.
Their sensor readings how have a shared global meaning (at this millisecond, we're observing this sound), and their actuation can be synchronized (at time *t*, lights should start a sequence of actions).
To get tighter synchronization, the server code coordinating time synchronization can be placed on the edge.

*Technology*:
- Global time synchronization
- Edge computing
- sensor/actuator interaction with time

*Focus*:
- time synchronization protocols and the edge

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

*Focus*:
- Device programming, sensor interpretation, distributed coordination

## Smart X

The grand tradition of IoT is to add "smart" to anything (i.e. to "X").
Smart coffee maker?
Smart doors?
Smart fridges?
What can you make "smart".
Note that there are quite a few definitions of "smart" for us to play with here.
Snark appreciated.

You should really be creative with this.
What if we wanted to make dancing "smart"?
Walls?
Stairs?
Classrooms?
Performance?
Presentations (that would be a demo at the end!)?
...

*Technology*:
- embedded system programming
- cloud interactions
- interaction between sensor suites and humans
- sensor programming (e.g. video/image processing)

*Focus*:
- Application/interaction focus

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

*Focus*:
- Edge cloud programming

## High-level programming model for IoT

Similar to [samsung's automations](https://smartthings.developer.samsung.com/docs/smartapps/automation.html), build a high-level programming model for connecting

- IoT actuator devices, with
- IoT sensor devices, and 
- Internet information

A [trivial](https://www.youtube.com/watch?v=ycUlqro_QMo&feature=youtu.be) example of this for using internet information into a smart-bulb.

This project could focus on creating a new programming model and API with a strong design around security, or could focus more-so on an interesting interactive demo (art display, informational display, etc...).

*Technology*:
- Cloud programming and implementation of the programming model
- IoT device interaction and programming
- wireless communication
- Internet service intergration

*Focus*:
- Cloud programming

## Secure IoT devices

Traditional embedded software is not designed for security.
Applications and OSes are written in C, typically in the same protection domain.
This complicates system security due to the lack of isolation.
This project investigates system support for isolation and leverages that to provide an application development environment under the assumption that applications can be malicious.
Though this assumption might seem out of place, it forces the system to assume the worst, yet still work well in the normal case.
This functionality should be paired with some system monitoring facilities paired with cloud procesing.
You might think of this via an analogy: anti-virus systems monitor system behavior, and watch for black-listed behaviors.
You'd monitor system behavior (question: which behavior?), and send it as a log to the cloud where it will be processed.

There are three paths that this project could take:

- Use a embedded OS/RTOS that supports isolation,
- Use the Rust support for [embedded systems](https://github.com/rust-embedded/awesome-embedded-rust) for isolation
- Use Linux, but put work into figuring out how to lock down the system and provide an execution sandbox for the application.
    Logging fine-grained application behavior might be challenging here.
    
*Technology*:
- The embedded system software (RTOS/Rust/Linux)
- Some prototype sensor/actuators to demonstrate that you can support them
- Cloud/IoT interaction
- Cloud APIs for storage and processing

*Focus*:
- embedded system programming

## Agile IoT devices via device functionality update and attestation

What do we have to do to security update system software on IoT devices?
What if we only want to update the applications and not the system?
We likely need to attest that the software is coming from a trusted source.
The software that provides the attestation on the IoT device, and provides the signatures in the cloud needs careful design.

*Technology*:
- Crypto
- Device update interactions
- Cloud interactions and portal for updating software

*Focus*:
- crypto and device programming around updates

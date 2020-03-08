C development for embedded systems:
- [General rules and guidelines](https://github.com/gwu-iot/collaboration/blob/master/resources/c.md) for writing C code.
- The [c build process](https://blog.feabhas.com/2012/06/the-c-build-process/)
- [Linker scripts](http://software-dl.ti.com/ccs/esd/documents/sdto_cgt_Linker-Command-File-Primer.html) and how to place programs explicitly in memory.
- [All things](https://github.com/nhivp/Awesome-Embedded) low-level and embedded.
- C development: [visibility and includes](https://www.youtube.com/watch?v=P8g4B9c0i8A&t=490s), [generic data-structures](https://www.youtube.com/watch?v=AUYYN3mqSGU&t=3s), and [polymorphism](https://www.youtube.com/watch?v=bZO0A1tj2MI)
- Makefile [tutorial](https://www.youtube.com/watch?v=DtGrdB8wQ_8)
- Don't imlement your [own spinlock](https://matklad.github.io//2020/01/02/spinlocks-considered-harmful.html) if you can avoid it!

Sensors and actuators:
- [Stepper motors](https://youtu.be/bkqoKWP4Oy4?list=TLPQMDQwMTIwMjCFXJiZsHM4tw) for fine-grained motor control (see also, servo motors).
- [PWM](https://youtu.be/GQLED3gmONg?list=TLPQMDQwMTIwMjCFXJiZsHM4tw) control of actuators.
- Quick survey of [different motors](https://www.electronics-tutorials.ws/io/io_7.html) (brushed/brushless DC, servo, stepper).
- Physical [communication protocols](https://youtu.be/IyGwvGzrqp8?list=TLPQMDQwMTIwMjC3tJDv5Sv15Q&t=93) on embedded systems.
- A little bit tangential, but microscopic devices ([MEMS](https://www.youtube.com/watch?v=iPGpoUN29zk)) are integral in our devices, and are quite impressive.


How to interact with physical systems:
- Understanding control of physical systems using a [PID](https://www.youtube.com/watch?v=wkfEZmsQqiA&list=PLn8PRpmsu08pQBgjxYFXSsODEF3Jqmm-y) controller.
- A great [document](/resources/local_copy/pid.pdf) on understanding PID with great graphs.
- Removing errors in state estimation using [Kalman filters](https://www.youtube.com/watch?v=mwn8xhgNpFY&list=PLn8PRpmsu08pzi6EMiYnR-076Mh-q3tWr).
- Integrating multiple sensor's information to estimate system state using [sensor fusion](https://www.youtube.com/watch?v=6qV3YjFppuc)

`git` and `github` information:
- Some [high-level, guidelines](https://github.com/gwu-iot/collaboration/blob/master/resources/github.md) for their use

On programming as a [craft](https://www2.seas.gwu.edu/~gparmer/posts/2016-03-07-code-craftsmanship.html):

- [debugging](https://github.com/gwu-iot/collaboration/blob/master/resources/debugging.md),
- [testing](https://github.com/gwu-iot/collaboration/blob/master/resources/testing.md), and
- [style](https://github.com/gwu-iot/collaboration/blob/master/resources/style.md)
- Properly using an [editor](https://github.com/gparmer/gwu_os_editors).
    Pull requests to this material are welcome and encouraged directly to that repository.

# Project Criteria and Timeline

The educational objective for the project for this class is to:

- give you experience working in the IoT domain, including embedded device and cloud programming
- learn to work effectively in a team
- experienc taking a project from start to end of a complex project, from planning to design to implementation to integration to testing to demo
- apply the knowledge you've learned about how to make a secure IoT system

What follows are a set of requirements for the project.
There are potential exceptions to these requirements if properly motivated.
Discuss with Gabe if such an exception is warranted.

## Project Requirements

Each project must include

- IoT devices
- a cloud (or edge-cloud) component
- a security analysis of the system, and a design to mitigate the worst impacts of this
- the system must have a testing component, and documentation

Projects might put more emphasis on the embedded system construction, on the coordination between systems, on the interaction with the physical system, or on interesting sensing and actuation, but each project must have a token aspect of each of these.

## Timeline

The major checkpoints for the project follow.
The deadlines for each will be posted on Piazza.

1. *Group selection* - groups should have 3 members by default, though 4 can be argued for.
    Students working on research projects can argue for fewer members.
1. *Project proposal* - your group must provide a proposal for your project.
    These will be submitted via form.
    Your aim is to convince me that your project meets the educational objectives for the class, and the project requirements above.
1. *Project equipment request* - this won't have a deadline, but there is a latency in ordering parts, so please plan for a 2 week delay. 
    Order early!
    I'll set up a form for you to request equipment.
    Generally, if you want to request more than $50 per group member worth of equipment, talk to me about it.
1. *Project work distribution & timeline* - you must provide
    - a breakdown of the different components of the project
    - a timeline on when these will be completed, focusing particularly on what will be done by checkpoint I and checkpoint II
    - an enumeration and description of the interfaces between the components
	- a reference to the principles for [securing the Internet of Things](https://github.com/gwu-iot/collaboration/blob/master/papers/dhs16guidelines.pdf) document spelling out how security will be considered in your project, and an explicit acknowledgment what factors in that document are *not* going to be considered in your project along with the reason why
    - an assignment of components to group members
    All of this should be in a `plan.md` file in your project's repository, and should have a corresponding set of cards in the [github project](https://github.com/features/project-management/) board for your project.

1. *Checkpoint I* - the first "deliverable" for your project.
    This focuses on two aspects:

    1. A brief document, `checkpoint1.md` that describes any *deviations* from the work distribution and timeline plan.
        This should include two main sections: 1. "What changes were necessary in the project", 2. "Where we fell behind", and 3. "What we'll do to catch up".
        If it is no longer feasible to follow the original plan, detail the changes in the first.
        If you feel behind, then detail *who* feel behind in the second, and what you'll do to catch up in the third.
    1. A 5 minute demo, and a plan for concisely (5 minutes) presenting the main technical aspects of the system to your peers.
        In class, we'll do peer feedback in which you'll present your demo and describe the technical aspects of the project to another group.
        When other groups present to you, your job is to provide them high-level feedback on the direction of the project, focusing on potential ideas that could help make their project better.
        These can be technical ideas, or "cool" ideas about how to use the technical parts of the project in novel ways.
    
    Please note that for Checkpoint I, you likely want to plan to get more done on the aspects of your system that don't require the physical system as ordering the devices can take some time.
1. *Checkpoint II* - Same as *Checkpoint I*, but with the output in `checkpoint2.md`.
1. *Demo & Presentation* - Each group will have 12 minutes to present a brief demo and give a technical overview of their project.
1. *Demo day* - Demo your project to a broad audience!
    Invite your friends.
1. *Final commit and report* - Add a `README.md` with two sections:
    1. How your project is organized.
        What each subdirectory holds.
    1. How to build and use your project.
        This will include the necessary hardware and software, and how to use it properly.
        For hardware setup, you should include pictures to illustrate the setup.

    Add a final `report.md` with three sections.
    1. An overview of the design of the system.
        This does *not* need to be very detailed, but should include enough detail for someone to understand what are the main technical aspects of the project, and how they are designed.
    1. The same as your checkpoint documents, include a section that includes a discussion about "What changes were necessary in the project", and "What you were not able to accomplish".
        The former should be well justified.
    1. Who did what.
        This should summarize what each of the members on your team accomplished, and **must** reference the pull requests made by those group members.

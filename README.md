# From Components to Systems

> An interactive educational game that teaches electronics and
> engineering through building, experimentation, and gameplay.

**Project status:** Project initiation / early design\
**Prepared by:** Dhruv Rathore

## Overview

From Components to Systems is a level-based educational game designed to
make electronics and engineering easier to understand through
interactive play. Players explore components, build simple systems, test
what they have made, observe the result, and progress through
increasingly advanced challenges.

The game is intended for beginners across a broad age range. Early
levels should be understandable to younger learners while remaining
useful to older first-time learners.

## Core Learning Loop

**Discover → Interact → Understand → Build → Test → Observe → Progress**

## Project Goals

-   Make introductory electronics and engineering approachable.
-   Teach through interaction, visual feedback, and experimentation.
-   Introduce concepts progressively, from simple components to more
    complex systems.
-   Encourage curiosity instead of punishing mistakes.
-   Provide level progression, hints, tutorials, and rewards.
-   Leave room for future progress tracking, analytics, and additional
    learning content.

## Level 01 --- Welcome to the Workshop

The current first-level concept combines component discovery with an
introduction to electricity and the player's first simple circuit.

### Learning objectives

-   Become familiar with the workshop and its controls.
-   Select, drag, move, rotate, and inspect components.
-   Understand the basic purpose of a battery, wire, and bulb.
-   Learn that a bulb needs a complete electrical path to light.
-   Build and test a first simple circuit.

### Gameplay flow

1.  Enter the workshop and view the green-grid playground.
2.  Browse the **scrollable Components panel**. The full component
    library should be visible, with unlock/availability states for
    components that are not yet usable.
3.  Drag an available component into the workspace and inspect its
    information pop-up.
4.  Learn component functions through short explanations and visual
    feedback.
5.  Use a battery, wires, and a bulb to build a simple circuit.
6.  Select **TEST CIRCUIT** to check the connections.
7.  If the circuit is incomplete, receive helpful guidance and try
    again.
8.  When the circuit is valid, observe the bulb light up and learn about
    the complete electrical path.

**Design decision:** The current Level 01 design does **not** include
the "Meet the Right Components / Toolkit Matching" challenge. Component
discovery is exploratory, and players do not have to inspect every
library item to continue.

### Planned interface areas

-   **Header:** level name, objective/progress, hint, and settings.
-   **Components panel:** full scrollable component library with
    availability/unlock indicators.
-   **Workspace:** interactive green-grid workbench.
-   **Instructions panel:** short guidance that updates with the current
    task.
-   **Learning panel:** concise explanations for key components and
    concepts.
-   **Bottom controls:** Delete, Undo, Redo, Reset, and Test Circuit.
-   **Next Level:** becomes available after completion conditions are
    met.

### Initial component examples

  -----------------------------------------------------------------------
  Component                           Introductory purpose
  ----------------------------------- -----------------------------------
  Battery                             Provides electrical energy for a
                                      circuit.

  Wire                                Provides an electrical
                                      connection/path.

  Bulb                                Produces light when the circuit
                                      works.

  Switch                              Controls a circuit by opening or
                                      closing its path; planned for a
                                      later guided level.

  Resistor                            Limits current; introduced
                                      progressively.

  LED                                 An electronic light source;
                                      introduced progressively.
  -----------------------------------------------------------------------

The component library is expected to grow. The full inventory and unlock
schedule will be defined as level design progresses.

## Gameplay and UI Principles

-   **Learn by doing:** introduce a concept through interaction, then
    explain what happened.
-   **Beginner-friendly language:** keep essential instructions short
    and clear.
-   **Visual feedback:** communicate selection, valid connections,
    errors, and success with more than color alone.
-   **Safe experimentation:** incorrect attempts should help the player
    learn.
-   **Consistent interface:** keep the core playground layout familiar
    across levels.
-   **Optional exploration:** players can inspect components in their
    own order.
-   **Progressive complexity:** teach foundational concepts before
    relying on them in advanced challenges.

## Proposed Technical Direction

The project report identifies the following as potential technologies.
The final engine and implementation stack have **not yet been
confirmed**.

-   Unreal Engine or Unity for a future game implementation
-   A 2D framework for an initial MVP
-   C++ and/or visual scripting such as Unreal Engine Blueprints
-   UI tools for interface and interaction design
-   Git for version control
-   Database and analytics systems for future progress tracking

### Conceptual architecture

``` text
Presentation Layer
        ↓
Game Logic
        ↓
Learning Engine
        ↓
Progress System
        ↓
Data Storage
        ↓
Analytics
```

This is a proposed logical structure, not a claim that all layers are
implemented.

## Planned User Flow

``` text
Launch Game
    ↓
Profile / Login (if included)
    ↓
Select Level
    ↓
Learn and Explore
    ↓
Build
    ↓
Validate
    ↓
Receive Feedback
    ↓
Reward / Progress
    ↓
Unlock Next Level
```

## Planned Systems

The broader project report identifies these as planned or future
capabilities:

-   Level selection and progression
-   Drag-and-drop component interaction
-   Contextual hints and tutorials
-   Component information pop-ups
-   Circuit validation and feedback
-   Achievements and rewards
-   User profiles and authentication
-   Cloud saves and progress tracking
-   Content management
-   Analytics
-   Possible future leaderboard or community features

These features should be implemented incrementally; their inclusion here
does not mean they are already available.

## Testing Approach

-   **Unit testing:** validate individual logic and component behaviors.
-   **Gameplay testing:** check drag-and-drop, placement, rotation,
    connections, and level progression.
-   **UI testing:** verify layout, scrolling, instructions, controls,
    and screen sizes.
-   **Educational validation:** check whether players understand the
    intended concepts.
-   **Performance testing:** monitor responsiveness and stability.
-   **User interaction testing:** observe completion rates, usability,
    learning outcomes, and retention.
-   **Closed beta (later stage):** gather feedback, find bugs, and
    balance difficulty.

## Development Roadmap

High-level proposed roadmap; exact dates and milestones are not yet
defined.

1.  Finalize the first-level UI and gameplay specification.
2.  Select the MVP game engine/framework.
3.  Build a playable workshop prototype.
4.  Implement component selection, dragging, moving, rotating, and
    information pop-ups.
5.  Implement the first battery--wire--bulb circuit and circuit
    validation.
6.  Test with beginners and improve clarity/usability.
7.  Design later levels that build on the first circuit, such as
    controlling it with a switch.
8.  Add progression, persistence, analytics, and other larger systems
    when justified by the MVP.

## Contributing and Feedback

The project is in an early design stage. Feedback from students,
parents, educators, electronics learners, and engineers can help improve
the clarity, usability, and educational value of the game.

Useful feedback includes:

-   Which instructions are unclear?
-   Can a beginner understand what each component does?
-   Are drag-and-drop interactions easy to use?
-   Does the player understand why the bulb lights or stays off?
-   Is the level engaging without becoming confusing or repetitive?

## Current Status

The project is in **project initiation and design**. The concept,
proposed architecture, and first-level direction are being developed.
The final engine, complete component inventory, implementation status,
and release timeline remain to be confirmed.



------------------------------------------------------------------------

*From Components to Systems --- Start with a component. Build a circuit.
Understand the system. Create the technology.*

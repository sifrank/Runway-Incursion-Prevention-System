# Runway Lights: Airport Runway Incursion Prevention System

**Course:** ENGR 408 – Engineering Leadership Principles  
**Competition:** Airport Cooperative Research Program (ACRP) Design Competition  
**Role:** Prototype Lead  
**Technologies:** Python | Turtle Graphics | Object-Oriented Programming | Prototype Design

---

## Project Overview

Runway Lights was a team engineering project developed for the Airport Cooperative Research Program (ACRP) Design Competition as part of ENGR 408: Engineering Leadership Principles.

Our team explored a technology-driven approach to reducing runway incursions, with particular consideration for non-towered airports where pilots may have limited access to real-time air traffic control (ATC) guidance.

The proposed system combined on-field Automatic Dependent Surveillance–Broadcast (ADS-B) aircraft transmissions with optical vehicle detection. A computer would evaluate aircraft and ground-vehicle activity against predefined parameters and send control signals to a runway lighting system to communicate runway status.

As **Prototype Lead**, I guided the team through the prototyping process and helped turn the proposed concept into a tangible demonstration.

## Problem & User Research

Runway incursions can occur when an aircraft, vehicle, or person is incorrectly positioned on a runway or its protected area, creating a potential hazard to airport operations.

To better understand the problem, our team interviewed pilots, engineers, and aviation industry professionals. Interviewees described challenges associated with landing at non-towered airports, navigating runways without ATC guidance, and maintaining awareness of other runway activity.

The interviews helped establish our design objective: develop an accessible way to improve runway-status awareness for pilots and airport ground personnel.

## Proposed Solution

We proposed an automated runway monitoring and lighting concept built around three components.

### 1. Aircraft detection with ADS-B

- Receive aircraft transmissions using on-field ADS-B equipment.
- Evaluate available aircraft information, including altitude and distance.
- Compare aircraft information against predefined parameters.
- Use the results to determine when a runway-related warning may be needed.

### 2. Ground-vehicle detection

- Use optical detectors to identify vehicles entering or occupying the runway.
- Incorporate vehicle activity into runway-status decisions.
- Account for both aircraft activity and ground operations when determining the lighting state.

### 3. Automated lighting control

A central computer processes the detection inputs and applies decision logic. It then sends a control token or signal to change the runway lights.

| Lighting state | Intended indication |
|---|---|
| **Green** | Runway clear |
| **Yellow** | Aircraft approaching or runway use imminent |
| **Red** | Runway occupied or in use |

### Conceptual system workflow

```text
     ADS-B Aircraft Transmissions       Optical Vehicle Detection
                    |                              |
                    v                              v
           Aircraft Information             Vehicle Activity
                    |                              |
                    +--------------+---------------+
                                   |
                                   v
                         Central Processing
                                   |
                                   v
                            Decision Logic
                                   |
                                   v
                         Control Signal / Token
                                   |
                                   v
                         Runway Lighting System
                                   |
                         +---------+---------+
                         |         |         |
                         v         v         v
                       GREEN    YELLOW      RED
                       Clear    Imminent  Occupied
```

*Conceptual architecture of the proposed system. The detection and lighting components shown here represent the overall design concept; they should not be interpreted as a certified, fully integrated airport system.*

## Prototype Development

Our team developed design diagrams, a low-fidelity model, circuit components, and a completed physical runway prototype to explore how the lighting concept could be demonstrated.

The software work also explored the decision logic behind runway alerts and lighting changes, including aircraft proximity thresholds and runway occupancy states.

The prototype work helped translate the system concept into a demonstrable design and gave the team a way to evaluate how runway-status information could be communicated visually.

## Project Screenshots

The following images show the design process, prototype development, physical model, circuit layout, and code.

### System design

**System diagram**

![Runway system diagram](Screenshots/Diagram.png)

**Runway design diagram**

![Runway design diagram](Screenshots/Runway%20-%20diagram.png)

### Prototype development

**Low-fidelity prototype**

![Low-fidelity prototype](Screenshots/Low%20Fidelity%20Prototype.png)

**Completed runway prototype**

![Completed runway prototype](Screenshots/Runway%20-%20Finished%20Prototype.png)

**Rear view of the prototype**

![Rear view of runway prototype](Screenshots/Runway%20-%20back%20of%20prototype.png)

### Circuit and code

**Circuit board**

![Circuit board](Screenshots/CircuitBoad.png)

**Prototype code**

![Prototype code](Screenshots/Sketch%20Code.png)

[View all project screenshots](Screenshots/)

## My Role: Prototype Lead

As Prototype Lead, I guided the team through the prototyping process and helped translate our engineering concept into a working demonstration.

My contributions included:

- Coordinating and guiding the team's prototyping efforts.
- Helping teammates move from the initial concept to prototype development.
- Contributing to the design and refinement of the runway-lighting demonstration.
- Supporting the technical implementation and control logic.
- Helping connect the prototype to the team's overall system concept and design objectives.

## Skills Demonstrated

| Area | Skills |
|---|---|
| Programming | Python, conditional logic, functions |
| Software concepts | Object-oriented programming, state management |
| Prototyping | Low-fidelity modeling, physical prototype development |
| Systems thinking | Sensor inputs, decision logic, lighting controls |
| Research | Stakeholder interviews, problem definition |
| Leadership | Prototype leadership, team coordination, collaboration |

## Potential Next Steps

Further development of the concept could include:

- Connecting to a live ADS-B data feed.
- Integrating optical vehicle-detection hardware.
- Combining aircraft and vehicle inputs into a single control system.
- Adding a real-time monitoring interface.
- Testing the system with simulated runway-conflict scenarios.
- Evaluating reliability, latency, and fail-safe behavior before any real-world application.

## Project Takeaways

This project combined stakeholder research, engineering design, software concepts, and hands-on prototyping to explore an aviation safety challenge. Serving as Prototype Lead strengthened my experience guiding a team through the development process and translating a broad technical idea into a tangible demonstration.

---

**Disclaimer:** This was an academic engineering design project and prototype. The proposed system is not certified or approved for operational aviation use.

**Project Focus:** Aviation Safety | Engineering Design | Python | Systems Prototyping | Technical Leadership

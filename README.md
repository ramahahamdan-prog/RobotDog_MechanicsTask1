# Simple Quadruped Robot - Mechanical Design

## Introduction

This project is a simple mechanical design of a quadruped (four-legged) robot created using **Tinkercad**. The main goal of this project is to understand the basic mechanical concepts behind a walking robot, such as body structure, leg design, joints, and stability.
This project focuses on learning the fundamentals rather than creating a fully functional robot.

---

## Features

- Simple quadruped robot design
- Designed using Tinkercad
- Four identical legs
- Two joints in each leg
- Basic mechanical structure
- Simple walking concept
- Beginner-friendly design

---

## Body Design

The robot body is designed as a rectangular box that acts as the main frame of the robot. It is large enough to hold the main components such as the battery, controller, and motors in a real robot.

The body was kept simple to make the design easier to understand and to provide a stable structure for connecting the four legs.

---

## Leg Design

The robot has four identical legs.

Each leg consists of three main parts:

- Upper leg (Thigh)
- Lower leg (Leg)
- Foot

The same design was repeated for all four legs to keep the robot balanced and symmetric.

---

## Joints

Each leg contains two revolute joints:

1. Hip Joint
   - Connects the leg to the robot body.
   - Allows the leg to move forward and backward.

2. Knee Joint
   - Connects the upper leg to the lower leg.
   - Allows the leg to bend while walking.

Small cylindrical shapes were used in Tinkercad to represent the joint locations.

---

## Degrees of Freedom

Each joint has one rotational degree of freedom.

Since each leg has two joints:

- 2 DOF per leg

The robot has four legs:

- 2 × 4 = **8 Degrees of Freedom (DOF)**

These joints provide enough movement for a basic walking mechanism.

---

## Motors

Servo motors are recommended for this design because they are commonly used in educational robots.

Suggested motor:

- MG996R Servo Motor

Reasons for choosing this motor:

- Easy to control
- Affordable
- Provides suitable torque
- Widely used in robotics projects

---

## Torque Calculation

A simple torque calculation was performed for one joint.

Assumptions:

- Leg mass = 0.5 kg
- Distance from joint = 0.1 m

Weight force:

F = 0.5 × 9.81 = 4.9 N

Torque:

τ = F × r

τ = 4.9 × 0.1

τ = **0.49 N·m**

Therefore, the selected servo motor should provide a torque greater than **0.49 N·m**.

---

## Center of Gravity

The center of gravity is placed near the middle of the robot body.

Keeping the center of gravity in the center improves:

- Balance
- Stability
- Walking performance

A centered weight distribution also reduces the possibility of tipping over.

---

## Walking Gait

The robot is designed to use a simple **Diagonal Walking Gait**.

The walking sequence is:

1. Front Right Leg
2. Rear Left Leg
3. Front Left Leg
4. Rear Right Leg

This gait provides better stability because two legs remain on the ground while the other two move.

---

## Challenges

This project presented several challenges, especially because it was my first mechanical design project.

Some of the challenges included:

- Learning Tinkercad from scratch
- Understanding joints and mechanical movement
- Designing balanced legs
- Understanding torque calculations
- Keeping the robot stable
- Learning basic mechanical engineering concepts

Although these topics were new to me, the project helped me understand the fundamentals of robot mechanics.

---

## Conclusion

This project introduced the basic principles of quadruped robot mechanical design.

Although the robot is a simple conceptual model, it includes the essential mechanical components such as the body, legs, joints, degrees of freedom, motor selection, center of gravity, and walking method.

As a beginner, this project was a valuable opportunity to learn the basics of mechanical design and understand how mechanical and software engineering work together in robotics.

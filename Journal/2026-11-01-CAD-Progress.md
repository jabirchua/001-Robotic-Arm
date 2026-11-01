# Engineering Journal — 1 November 2026

**Project:** Project 001 — Desktop Programmable Robotic Arm  
**Phase:** Mechanical Design and Parametric CAD Development  
**Software:** Autodesk Inventor 2024

## 1. Objective

Develop a parametric mechanical skeleton that establishes the robotic arm's geometry, joint positions, and coordinate system before designing individual mechanical components.

## 2. Work Completed

### Mechanical Design Development

- Refined the robotic arm's dimensions and working envelope.
- Established a 200 mm × 150 mm base footprint.
- Developed a preliminary arm geometry with a nominal extended link reach of 495 mm.
- Maintained the objective of supporting a 500 g payload, prioritizing operation at 250–300 mm reach.

### CAD Development

- Selected Autodesk Inventor 2024 for mechanical modelling.
- Established a coordinate system with X forward, Y vertical, and Z across the robot's width.
- Developed parametric side-view and top-view skeleton sketches.
- Defined named parameters for the base and arm geometry.

## 3. Current CAD Parameters

| Parameter | Value |
|---|---|
| Base_Length | 200 mm |
| Base_Width | 150 mm |
| Shoulder_Height | 130 mm |
| UpperArm_Length | 220 mm |
| ForeArm_Length | 200 mm |
| Wrist_Length | 75 mm |

Nominal extended link reach: 495 mm.

## 4. Engineering Decisions

**Parametric modelling:** Use named dimensions so that changes to arm geometry can be made without manually rebuilding the sketches.

**Coordinate convention:** Maintain a consistent global coordinate system throughout the project.

**Mechanical design approach:** Develop the kinematic skeleton before creating detailed components.

**Payload priority:** Design around a 500 g payload at 250–300 mm, while investigating a longer nominal reach.

## 5. Outstanding Work

- Create named 3D work points for shoulder, elbow, wrist, and tool centre point.
- Establish joint axes.
- Review and validate the arm's reachable workspace.
- Refine shoulder and elbow free-body diagrams.
- Validate motor torque requirements using estimated or CAD-derived component masses.

## 6. Reflection

The project has progressed from conceptual planning into parametric CAD development. My use with ChatGPT Pro as a guide has proved useful, however some 
decisions still needed to be change with the most notable being
- Using correct axis when developing the skeleton as the AI had used the z axis as the height of the robot and the y axis as the width
- Naming conventions which were confusing including Base depth and Base width which i felt was wrong for the length and width of the base

The next challenge is ensuring that the selected geometry is mechanically feasible, particularly regarding joint torque, link mass, stiffness, and positioning accuracy.

## 7. Next Session

Continue in Autodesk Inventor 2024 by creating the named 3D work points and joint axes needed for subsequent component modelling.

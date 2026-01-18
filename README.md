# Baseball Swing Coaching Analysis

## Overview
As a Data Analyst for a professional baseball team, this project analyzes high-resolution swing data from five batters. The dataset includes detailed time-series measurements of joint positions, joint angles, angular velocities, bat metrics, and key swing events such as ball release and contact.

The goal of this analysis is to process raw biomechanical data, identify key swing events, and calculate meaningful metrics that can inform hitting coaches about player performance. By translating complex motion data into intuitive metrics, this project bridges the gap between data science and on-field coaching without requiring a technical biomechanics background.

---

## Project Objectives
- Clean and standardize raw swing-tracking data  
- Identify key events within each batter’s swing  
- Extract coach-relevant performance metrics  
- Present results in a clear, interpretable format  

---

## Key Swing Events

### Ball Release
This event serves as the starting point for analyzing the swing. A well-timed swing begins in response to the pitcher’s release, making this phase critical for understanding swing timing. Metrics captured here help coaches evaluate initial positioning and preparation.

### Maximum Bat Speed
This event captures the moment of peak bat speed during the swing. Maximum bat speed is strongly associated with power generation and overall swing effectiveness.

### End of Swing
The end of the swing is defined as the slowest bat speed following peak velocity. This phase provides insight into follow-through quality and energy transfer efficiency.

---

## Metrics Calculated

### Contact
Indicates whether the batter made contact with the ball. This fundamental metric helps assess swing timing and alignment with the pitch.

### Sweet Spot Hit
Identifies whether contact occurred near the bat’s sweet spot. Not all contact is equal, and this metric helps distinguish optimal contact from less efficient hits.

### Stride Length
Measures the distance between the batter’s left and right ankles. Stride length is linked to balance, stability, and lower-body power generation.

### Torso–Pelvis Ratio
Evaluates the coordination between upper- and lower-body rotation by comparing torso and pelvis angular velocities. Higher ratios near peak bat speed indicate effective kinetic sequencing.

---

## Analysis Output
The final output is a consolidated table summarizing each batter’s metrics at three swing events:
- Ball Release  
- Maximum Bat Speed  
- End of Swing  

This structure enables quick comparison across batters and swing phases while remaining accessible to coaches and performance staff.

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## Conclusion
This project demonstrates how high-resolution swing-tracking data can be transformed into actionable coaching insights. By focusing on key swing events and intuitive metrics, the analysis supports player development, mechanical refinement, and performance optimization, highlighting the value of data analytics in baseball operations.


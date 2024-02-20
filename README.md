# Linear Quarter-Car Suspension Analysis

Welcome to the Quarter Car Suspension Analysis repository! This project focuses on the exploration and analysis of a fundamental quarter-car model representing automotive suspension. While the model itself is basic, its simplicity provides valuable insights into ride characteristics, making it a great starting point for understanding suspension dynamics.

<div style="text-align: center;">
    <img src="https://github.com/MoBehtash/linear_quarter_car_analysis/blob/main/images/schematic.jpg" alt="Time Domain Analysis" width = "200"  />
    <p><em>Figure 1: Schematic of the Quarter-Car Model</em></p>
</div>

## Key Features
- **Model & Analysis:** The repository includes the implementation of a straightforward quarter-car model and associated analysis techniques.
  
- **Insightful Results:** Despite its simplicity, the quarter-car model can yield profound insights into the behavior of automotive suspensions, offering a foundation for further study and experimentation.
  
- **Two Main Analyses:** Explore the suspension dynamics through both time domain and frequency domain analyses.
  
- **Versatile Road Definition:** The flexibility of this analysis allows users to define any type of road profile, enabling visualization of the suspension response under diverse road conditions.
  
- **Parameter Customization:** Easily modify suspension parameters within the model to observe their effects on the system. Experiment with different stiffness, damping, or mass values to understand their impact on ride quality and performance.

## Limitations
- **Linear Elements:** The damper, suspension spring, and tire stiffness in this quarter-car model are assumed linear which can alter the behavior of the model from its real counterpart.
- **Wheel-Ground Contact:** The wheel is assumed to be in contact with the ground at all times

## Results
You can visualize the results of the suspension analysis below:

![Time Domain Analysis](https://github.com/MoBehtash/linear_quarter_car_analysis/blob/main/images/time_res.png)
*Figure 2: Example of Time Domain Analysis*

![Frequency Domain Analysis](https://github.com/MoBehtash/linear_quarter_car_analysis/blob/main/images/freq_res.png)
*Figure 3: Example of Frequency Domain Analysis*

## Disclaimer
Please note that while this vehicle model and analysis framework can provide valuable insights, there is no guarantee of its accuracy in representing real-world vehicle behavior. The model's simplicity and assumptions may not fully capture the complexities of actual automotive vehicle.

**Note:** Feel free to contribute, share your insights, or open issues for discussion. Collaboration is key to expanding our understanding of vehicle dynamics.


## Languages and Utilities Used
- Python 3.12</b>
- Packages: numpy, matplotlib, scipy, math


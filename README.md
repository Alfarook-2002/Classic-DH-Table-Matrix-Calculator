# Classic-DH-Table-Matrix-Calculator
A web-based tool designed for roboticists, engineers, and students to compute individual and global transformation matrices for serial manipulators using the Standard Denavit-Hartenberg (DH) convention.**[🔗 link](https://alfarook-2002.github.io/Classic-DH-Table-Matrix-Calculator/)**


![alt text](https://github.com/Alfarook-2002/Classic-DH-Table-Matrix-Calculator/blob/main/media/Classic%20DH%20Table%20Matrix%20Calculator.png?raw=true)
## Features
Symbolic Computation: Handles variables (e.g., theta1, L1, d2) and preserves them in the final matrix output.
Trigonometric Simplification: Automatically applies identities for phase shifts (e.g., cos($\theta$ - 90) simplifies to S₁).
Standard DH Logic: Uses the standard four-parameter transformation:
$$Rot_{z}(\theta) \cdot Trans_{z}(d) \cdot Trans_{x}(a) \cdot Rot_{x}(\alpha)$$
Dynamic Joints: Add or remove joint rows as needed for your specific kinematic chain.
Dark Mode: Toggle between light and dark themes for better visibility.
Standard Notation: Outputs results using $C_i$ and $S_i$ notation with proper subscripts and superscripts ($T^{i-1}_{i}$).
## Added 3D model Visualization
![alt text](https://github.com/Alfarook-2002/Classic-DH-Table-Matrix-Calculator/blob/main/media/3D%20model.gif?raw=true)
### The matrix
![alt text](https://github.com/Alfarook-2002/Classic-DH-Table-Matrix-Calculator/blob/main/media/The%20Matrix.jpg?raw=true)
## How to Use
- Enter Parameters: Fill in the $\theta$, $d$, $a$, and $\alpha$ values for each joint.
- Use numbers for constants (e.g., 90, 0).
- Use text for variables (e.g., theta1, L1).
- Quick Insert: Use the θ button next to the theta field to quickly insert the joint variable.
- Add/Remove Joints: Use the controls at the top to adjust the number of joints in your robot.
- Calculate: Click "Calculate Transformation Matrix" to generate the symbolic matrices.
- Arabic - English - Turkish Language added.
> [!NOTE]
> The symbolic engine supports basic arithmetic shifts within trigonometric functions. For example:
Entering $\theta1$ - 90 in the $\theta$ field will result in the matrix displaying $S_1$ or $-C_1$ where appropriate based on standard identities.
### 📜Credits
made by Shaker abdullah © 2026

## 🤖 Double Pendulum Simulation Using PINN  
Machine-learning model for predicting the chaotic motion of a double pendulum

## 🚀 Overview  
This project implements a physics-informed neural network (PINN) to predict and simulate the chaotic dynamics of a double pendulum.  
It comprises three main components:  
1. Data generation via a classical physics-based simulation of the double pendulum system.  
2. Training of a neural network (PINN) to learn the underlying dynamics and predict trajectories.  
3. Interactive visualisations of predicted vs. ground-truth trajectories, enabling analysis and validation of the model’s performance.

Through the correct choice of parameters, it is possible to obtain predictions similar to reality.

## 🧠 Key Features  
- **Physics-based data generation**: A full simulation of the double-pendulum system under various initial conditions, generating time-series trajectories and states.  
- **PINN (Physics-Informed Neural Network)**: The ML model incorporates physics constraints (e.g., underlying differential equations of motion) to improve generalisation and physical consistency.  
- **Prediction of chaotic motion**: The trained model aims to accurately predict highly non-linear and chaotic trajectories of the double pendulum beyond mere interpolation.  
- **Visual analytic tools**: Interactive plots and animations comparing model predictions and ground truth trajectories, allowing in-depth qualitative and quantitative evaluation.

## ⚙️ Prerequisites  
- Python 3.x  
- libraries:  `simpy`, `numpy`, `matplotlib`,  `pytorch`  `scipy`  
- Optional: GPU (for faster training)  

## Usage  

1. Clone the repository:  
   ```bash
   git clone https://github.com/zanko-mezdrichki/Double-Pendulum-Simulation-Using-PINN.git
   cd Double-Pendulum-Simulation-Using-PINN
   ```
   
2. Install dependencies:
      ```bash
   pip install simpy numpy matplotlib pytorch scipy 
   ```
      
3. Start the program:
    ```bash
   python main.py
   ```
    
4. Enter the configuration values.



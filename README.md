## 1. Linear quadratic regulator
All of Part 1 can be found in  **Q1.ipynb**
### 1.1 Write class
We write this part in **LQR class**. I'll list the functions corresponding to each question.  
i) **__init__( )**  
ii) **solve_ricatti_ode( )**  
iii) **control_problem_value( )**  
iv) **markov_control_function( )**  
### 1.2 LQR MC checks
I'll describe how I implemented the MC here.   

**simulate_multiple_paths( )** can perform a Monte Carlo simulation after defining the start point t and the end point T, but we have to first define lqr and solve for S using the function in 1.1.  

**compute_J_alpha( )** can derive the J-values of these paths after the simulation is complete.  

**simulate_and_compute_J_for_different_Ns( )** fix steps and do MC to calculate J. Immediately after defining the function, the simulation was performed and the loglog plot was drawn.  

**simulate_and_compute_J_for_different_ns( )** fix sample size n and do MC to calculate J. Immediately after defining the function, the simulation was performed and the loglog plot was drawn.  

## 2. Supervised learning, checking the NNs are good enough

## 3. Deep Galerkin approximation for a linear PDE
## 4. Policy iteration with  DGM 

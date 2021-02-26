# Geothermal
## Introduction
The objective we develop customized predictive analytics tool to enable efficient surveillance, control, and automation of geothermal operations. By integrating state-of-the-art machine learning algorithms with advanced multi-physics monitoring data acquisition systems, this subtask aims to develop into real-time model predictive control algorithms to improve the efficiency of energy production operations in geothermal reservoirs.  

To be more specific, there are three parts in this subtask.  

(i)	Latent space dynamic modeling for power plant data  
(ii)	Numerical process model for the power plant  
(iii)	Model predictive control with the data-driven model in   
The operation of the surface power plant is binary cycle in the principle of the ORC (Organic Rankine cycle). The data-driven model is built based on the historical data from different field such as public dataset and our industrial partner. Our developed model consists of three parts: (i) a sliding-window encoder for capturing data correlations to enable latent-space representation, (ii) fully connected neural network layers tailored for describing the evolution of the latent states, accounting for effects of control changes and making predictions, and (iii) a decoder which maps the prediction results in the low-dimensional latent space back to the original data space. The next achievement is the numerical model with the given information about ORC power plant, which is the physics-based model can be presented to simulate the process for predictive model validation. Finally, we develop advanced model predictive control workflows and combine them with DDNN tools from (i) to enable automation and improved performance efficiency of geothermal operations.

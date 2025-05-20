# Radar
This project uses radar to generate a perception for a self-driving car, covering topics like signal propagation, target response generation, Range Doppler generation, etc.

### Implementation steps for the 2D CFAR process

The 2D CFAR algorithm is deployed on the output of the "RANGE DOPPLER RESPONSE" section's RDM variable (Range-Doppler map) . 
Training and Guard cells are set and looped through - the noise is suppressed and target signal is filtered out based on the threshold setting 



 

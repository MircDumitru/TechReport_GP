# TechReport_GP
Some implementations using non-parametric approaches based on Gaussian processes applied in ECG signals. Generating synthetic signals, denonising, filtering.

## Generating - The goal of this implementation is:
Chalenge the state of the art models used in the literature for ECG signals generation. A comparison between synthetic ECG signals issed from the GP model and from classical models (based on dynamical systems) can be done in order to asses which models produces a more realistic ECG signal.

## Filtering - The goal of this implementation is multiple. 
1. First, a plain implementation with hand-picked parameters serves as proof of concept: the filtering in ECG context can be approached with non-parameteric models.
2. Secondly, an implementation where the parameters are learned (for instance by maximizing the evidence) can be tested against other ECG denoising state-of-the-art methods.
3. Thirdly, there are lots of possible extensions: a non-zero mean GP model, online uptading, theta-domain implementation, hierarchical model for parameters, GP for interval classification.

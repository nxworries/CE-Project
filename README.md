# CE-Project
This is the Cumulative Experience Project I completed for my masters program

## About
This is a project where I created the architecture for a Markov Decision Process for which the purpose was to aid the decision making process for grassland managers in the Midwest United States. The Grassland Monitoring team, a partnership between the Us Fish and Wildlife Service, the National Conservancy, and the Minnesota Department of Natural Resources, started collecting data to make more informed decisions about grassland management since around 2008. Grassland managers can decide to burn or graze their land which has been shown to have ecological benefits for the ecosystem as a whole. The goals of this project were to:

1. Use the collected data on praries to define state-spaces, measuring how desirable the condition of the measured prairie transects are for the managers
1. Create a probability transition matrix out of the data to measure the probability that 1 state turns into another between measurements, given a certain action
1. Create a reward matrix in which to base the decision model, incentivising transitions to more desirable states and disincentivising transitions to less desirable spaces
1. Create the architecture for a Markov Decision Process, which takes in the measured variables of a transect and outputs the action that is most likely to lead to the largest improvement within the state-space

## Files

1. Craig_CE_Paper2.pdf is the file for the final draft of the paper

1. LISA_Project2.rmd contains much of the code (done in R) to complete this project

The data is ommitted since I don't have permission to share it publicly


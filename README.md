# outbreak-demos
Visualizations of behavioral outbreak models

#### social-distancing_1d-2i.mp4
Social distancing (including territorial separation) of 2 groups of indivdiuals in response to local host-generated deterrents (e.g., scent marks, new infections), \psi. \phi refers to the probability distribution of individual group space use. Over time, they segregate from each other; simultaneously, transmission risk surges near the center of the one-dimensional landscape.

#### social-distancing_2d-4i.mp4
Social distancing (including territorial separation) of 4 groups of indivdiuals in response to local host-generated deterrents (e.g., scent marks, new infections). The behavioral responses are identical to the above model except the equations here operate in two-dimensional space. Red lines denote the contour maps of individual group space use. The color density gradient shows the time-varying hotspots.

#### movement-barriers.mp4
Temporally solving a 2-dimensional Fokker-Planck equation of individual movement in response to multiple randomly distributed landscape barriers. Movement is governed by a point attractor located at the top of the landscape. The color density gradient denotes the probability density of the individual's space use.

#### transient-infect-contact.mp4
Transient infective contact rate between a mobile individual (e.g. ungulate) and a sedentary reservoir host inhabiting a waterhole (i.e. bottom rectangular barrier). This model applies the above algorithm. Left panel tracks the probability distribution of the mobile indivdiual's space use. Middle panel shows its joint distribution with the infected host. Right panel updates their infective contact rate over time.

#### outbreak-vax-strategy.mp4
Deployment of healthcare personnel during vaccine-based oubreak management. Vacciation effort starts from the outbreak epicenter and moves across space at a constant diffusion rate. Susceptible individuals are shown in white, infected in red, recovered in black, and vaccinated in yellow. The color density gradient denotes the probability density of collective space use by the healthcare personnel.

#### outbreak-vax-strategy_adaptive.mp4
Adaptive deployment of healthcare personnel during vaccine-based outbreak management. In contrast to the above model, movement behavior of the control agents repond to local epidemic condition over time, withdrawing strategically from highly infected or vaccinated areas. The animation shows four concurrent dynamics: the changes in collective movement and probabilistic space use of healthcare personnel (top left); the outbreak dynamics, where vaccinated individuals are shown in green, susceptibles in grey, and infected in red (top right); the shrinking spatial distribution of susceptibles (bottom left); and the growing spatial distribution of infection (bottom right).



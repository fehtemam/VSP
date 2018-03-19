## Pilot results

Kinematic and EMG data is collected from 5 subjects. EMG signals are high pass filtered (20 Hz) and averaged over gait cycles in each trial and then over all trials for each subject. The mean wave forms are normalised to their RMS values for each subject and then averaged over all subjects.  

The graph below shows muscle activation profiles (normalized mean wave forms) for normal (first row) and perturbed walking (second row) from three muscles, tibialis anterior, lateral gastrocnemius and medial gastrocnemius. 


![Normal and perturbed activation profiles](https://github.com/fehtemam/VSP/blob/master/plot1-page001.png)

<p align="justify">
The folloowing graph compares muscle activation profiles during steady-state conditions to those from transient responses. We observe some qualitative similarities between the two types of responses. At the same regions during the gait cycle we see increase in inhibition (black arrows). Particularly for plantarflexors this happens around the push-off phase. There is also some decrease in inhibition in transient profiles before push-off. However due to limited statistical power (5 subjects) it is not clear how reliable this observation is and if the same decrease in inhibition exists in steady-state condition. 
</p>

![Steady-state condition versus transient responses](https://github.com/fehtemam/VSP/blob/master/plot2-page001.png)

<p align="justify">
To calculate the transient responses, the relationship between the visual perturbations (the input) and the mean wave form of EMG (the measured output) is analyzed in the frequency domain using harmonic transfer functions (HTF). The frequency response functions are then converted back to the time domain which results in impulse response functions (IRFs). This transformation makes the understanding and interpretation of results much easier. The graph below shows IRFs for the three muscles. The impulse response functions show the transient muscle activity as a function of stimulus phase and the phase of the gait cycle. IRFs could be sliced at different phases of stimulus and the results would be the transient responses depicted in the figure above. The slices were transient responses are drawn from are shown with slashed lines
</p>

![Impulse response functions](https://github.com/fehtemam/VSP/blob/master/plot3-page001.png)
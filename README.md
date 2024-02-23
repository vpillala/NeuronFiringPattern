# NeuronFiringPattern
This a Neuron firing model for Izhikevich_Model. You can see the different firing patterns like Fast, LTS, Regular, Intrinsically, chatter 
This line is defining the parameters for a "regular spiking" neuron in the Izhikevich neuron model. The parameters are stored as a tuple and associated with the key 'regular_spiking' in a dictionary. Here's what each parameter represents:
1. `0.02`: This is the `recovery_rate` (a) in the model. It represents the time scale of the recovery variable `u`. Smaller values result in slower recovery.
2. `0.2`: This is the `sensitivity` (b) in the model. It describes the sensitivity of the recovery variable `u` to the subthreshold fluctuations of the membrane potential `v`.
3. `-65`: This is the `reset_voltage` (c) in the model. When the membrane potential `v` reaches the peak (30 mV), it is reset to this value.
4. `8`: This is the `reset_recovery` (d) in the model. When the membrane potential `v` reaches the peak, the recovery variable `u` is increased by this amount.
5. `-65`: This is the initial membrane potential `v_init`.
6. `2`: This is the initial recovery variable `u_init`.
7. `10`: This is the constant input current `I`.
8. `100`: This is the total time `T` for the simulation.
9. `0.1`: This is the time step `dt` for the simulation.
So, in summary, this line of code is setting up the parameters for simulating a "regular spiking" neuron using the Izhikevich model.
Same will implement for different Neuron Firing patterns 

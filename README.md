# EV-Battery-Swapping
Simulation model for EV battery swapping and central charging.

## Front-end Simulation

Implementation based on `simpy`. Currently offering:

1. 3 types of truck arrival: compound poisson, renewal (arrival interval following weibull distribution) and scheduled batch.
2. Adjustable truck load sizes. 

To-do: 

- align unloading and loading buffer with back-end
- asign batteries to different classes of SoC (State of Charge)
- generate numerical results (e.g. How many BSS can one CCS serve? What's the service time for one round of truck arrival?)

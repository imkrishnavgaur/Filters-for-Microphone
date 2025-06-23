# Filters-for-Microphone
- Objective 1:
  - Design and simulate a signal processing system using LTSpice to reduce noise from a voice signal. The system should consist of a signal generator and a filter to remove 50 Hz noise. This setup mimics the operation of microphone circuitry used to capture voice signals. 
- Choice of Design:
  - I tested both active and passive filtering options using the Twin-T Notch Filter Design.
  - I found the active design to be more effective as it gave me a way to control the quality factor of the design. 
- Objective 2:
    - Additional requirements stated that the filter should be able to remove the noises ranging from 50Hz to 60Hz.
    - This was also possible using the Twin-T Notch Method
        - By setting the Fn to 55Hz and the bandwidth to be removed to 10Hz, this gave us a new quality factor which was easy to implement like the first time. 

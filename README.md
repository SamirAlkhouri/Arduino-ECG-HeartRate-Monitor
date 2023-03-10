# Arduino-ECG-HeartRate-Monitor

These programs are meant to help users generate and see an electrocardiogram (ECG) signal using a combination of Arduino hardware and Python scripting. The Arduino program collects heart rate data from a sensor attached to the user through the Sparkfun MAX3010x library, then sends it over to a Python script that uses Numpy to perform calculations. The results are then shown as a visual representation of the ECG signal through the use of Matplotlib. This graph lets users take a closer look at the ECG signal and analyze its different waveform characteristics like amplitudes and durations. Plus, users can also modify some waveform elements by inputting their own specifications, which gives them the opportunity to experiment with different ECG configurations and see how the visualized signal changes. In summary, this software provides a valuable tool for generating and visualizing ECG signals for educational or experimental purposes.

Arduino Schematic:
![Arduino Schematic](https://i.imgur.com/7FHopCs.png)

Final Setup:
![Final Setup](https://i.imgur.com/tqrMKiV.png)

Operation:
![FOperation](https://i.imgur.com/TtDSmpK.jpg)

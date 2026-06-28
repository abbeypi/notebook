## Voltage Controlled Oscillator (VCO Core v1.2)

Discrete component architecture tracking linear to exponential current conversions over standard control voltages.

### Operational Core Math
The fundamental voltage-to-current translation behavior is modeled using the idealized transconductance relationship:

$$I_C = I_S \cdot \exp\left(\frac{V_{BE}}{V_T}\right)$$

Where $V_T \approx 26\text{mV}$ at room temperature constraints.

### Repository & Resources
* **Source Project:** [github.com/AbbeyPi/synth-modules/vco](https://github.com/)
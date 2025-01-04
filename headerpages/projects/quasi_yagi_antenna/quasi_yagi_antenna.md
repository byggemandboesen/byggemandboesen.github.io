---
title: Quasi yagi antenna for DECT communication
---

As one of my first projects designing RF components using electromagnetic simulation, I designed a quasi yagi antenna for DECT communication using CST.

![Antenna](assets/quasi_yagi_antenna.jpg)

I divided the design into two components - the antenna and the balun/impedance matching. The antenna was parametrically modelled in the 3D modeller, and the balun was designed in the schematic editor of CST and imported as a component.

![Balun](assets/cst_balun.jpg)

Once combined in a complete 3D model, I optimized the quater wave impedance transforming section to achieve a desired return loss.

![Measurement in anechoic chamber](assets/in_chamber.jpg)

I had the opportunity to measure the radiation pattern of the antenna in an anechoic chamber, from which the following results were obtained.

![Radiation pattern comparison](assets/radiation_pattern_comparison.jpg)

Finally, a comparison between the simulated and measured return loss can also be found below.

![Return loss comparison](assets/return_loss_comparison.jpg)

This project provided me with very valuable experience in the field of antenna design and -simulation.
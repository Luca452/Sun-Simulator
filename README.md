# Sun-Simulator
Sun Simulator used to test small size solar cells. In our case this is used to test Perovskites solar cells that are going to be mounted on the [6S CubeSat](https://polispace.it/6s-cubesat-project/). The board is mounted on top of an enclosure, acting as the lid.

<img src="https://github.com/Luca452/Sun-Simulator/assets/36864265/39427290-29f9-4814-9904-17e5993ce7b8" width="400" />

<img src="https://github.com/Luca452/Sun-Simulator/assets/36864265/f7d41556-cb27-4870-9165-9492d6fd0bb7" width="390" />

- Arduino nano programmed to: control the LEDs light intensity through voltage controlled current generator, measure pixels temperature through the LM35, measure the light intensity hitting the pixel thanks to a photodiode
- Temperature sensor used is LM35, which provides an analog output.
- Transimpedance amplifier used for conditioning of the photodiode's signal.

<img src="https://github.com/Luca452/Sun-Simulator/assets/36864265/bda7f382-7f1a-4339-9db9-ad5128384f68" width="1000" />



# Sennheiser MM 450-X

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.2dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 5.2; 31 3.9; 34 2.5; 37 1.5; 41 0.5; 45 -0.2; 49 -0.6; 54 -1.1; 60 -1.3; 66 -1.5; 72 -1.9; 79 -2.3; 87 -2.7; 96 -3.2; 106 -3.6; 116 -3.9; 128 -4.1; 141 -4.0; 155 -3.8; 170 -3.5; 187 -3.4; 206 -3.2; 227 -2.9; 249 -2.6; 274 -2.6; 302 -2.3; 332 -1.8; 365 -1.3; 402 -0.9; 442 -0.5; 486 -0.1; 535 0.2; 588 0.3; 647 0.3; 712 0.3; 783 0.0; 861 -0.2; 947 -0.0; 1042 -0.0; 1146 -0.3; 1261 -0.8; 1387 -1.5; 1526 -2.2; 1678 -3.1; 1846 -4.6; 2031 -5.1; 2234 -6.3; 2457 -5.3; 2703 -3.3; 2973 -1.8; 3270 0.5; 3597 4.0; 3957 6.1; 4353 3.5; 4788 3.9; 5267 5.2; 5793 5.1; 6373 3.2; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser MM 450-X GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-62**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser MM 450-X ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 23 Hz   | 1.61 | 6.9 dB  |
| Peaking | 134 Hz  | 0.68 | -4.2 dB |
| Peaking | 2233 Hz | 1.98 | -6.7 dB |
| Peaking | 3856 Hz | 4.42 | 6.4 dB  |
| Peaking | 5557 Hz | 2.83 | 5.5 dB  |
| Peaking | 295 Hz  | 2.78 | -0.8 dB |
| Peaking | 582 Hz  | 1.83 | 0.9 dB  |
| Peaking | 1218 Hz | 1.38 | 0.7 dB  |
| Peaking | 1548 Hz | 2.44 | -0.9 dB |
| Peaking | 8439 Hz | 5.15 | -0.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/rtings/Sennheiser%20MM%20450-X/Sennheiser%20MM%20450-X.png)
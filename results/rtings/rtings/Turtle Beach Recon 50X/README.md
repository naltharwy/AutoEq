# Turtle Beach Recon 50X

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 2.4; 25 2.3; 28 2.0; 31 1.8; 34 1.6; 37 1.6; 41 1.6; 45 1.6; 49 1.7; 54 1.7; 60 1.5; 66 1.0; 72 0.6; 79 0.0; 87 -0.6; 96 -1.0; 106 -1.4; 116 -1.9; 128 -2.6; 141 -3.4; 155 -4.0; 170 -4.4; 187 -4.4; 206 -4.5; 227 -4.7; 249 -5.1; 274 -5.5; 302 -5.4; 332 -5.5; 365 -5.5; 402 -4.7; 442 -4.5; 486 -4.6; 535 -4.5; 588 -4.4; 647 -4.1; 712 -3.3; 783 -2.0; 861 -0.8; 947 -0.1; 1042 0.0; 1146 0.2; 1261 0.4; 1387 1.2; 1526 2.2; 1678 2.6; 1846 2.9; 2031 3.0; 2234 3.4; 2457 4.1; 2703 3.6; 2973 2.2; 3270 1.9; 3597 2.4; 3957 3.0; 4353 4.8; 4788 6.0; 5267 6.0; 5793 6.0; 6373 2.0; 7010 0.1; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Turtle Beach Recon 50X GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Turtle Beach Recon 50X ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 35 Hz   |  0.32 | 2.5 dB  |
| Peaking | 254 Hz  |  0.51 | -5.8 dB |
| Peaking | 600 Hz  |  2.43 | -2.0 dB |
| Peaking | 2085 Hz |  1.01 | 3.7 dB  |
| Peaking | 5115 Hz |  2.84 | 6.3 dB  |
| Peaking | 593 Hz  |  3.9  | 0.8 dB  |
| Peaking | 767 Hz  |  1.51 | -1.4 dB |
| Peaking | 882 Hz  |  2.85 | 1.9 dB  |
| Peaking | 6822 Hz | 12.31 | -1.8 dB |
| Peaking | 8602 Hz |  3.9  | -0.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/rtings/Turtle%20Beach%20Recon%2050X/Turtle%20Beach%20Recon%2050X.png)
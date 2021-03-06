# Polk Audio UltraFocus 8000

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -3.1; 23 -3.0; 25 -2.9; 28 -2.6; 31 -2.3; 34 -1.8; 37 -1.4; 41 -1.0; 45 -0.6; 49 -0.3; 54 0.1; 60 0.6; 66 0.9; 72 1.1; 79 1.2; 87 1.1; 96 1.2; 106 1.3; 116 1.5; 128 1.5; 141 1.6; 155 1.8; 170 2.1; 187 1.9; 206 1.9; 227 2.0; 249 1.9; 274 1.8; 302 1.7; 332 1.6; 365 1.8; 402 1.5; 442 1.5; 486 1.2; 535 1.5; 588 1.9; 647 1.8; 712 1.6; 783 1.7; 861 1.2; 947 0.5; 1042 -0.0; 1146 0.4; 1261 0.9; 1387 1.2; 1526 1.7; 1678 2.2; 1846 3.0; 2031 3.4; 2234 4.1; 2457 5.6; 2703 6.0; 2973 6.0; 3270 6.0; 3597 6.0; 3957 6.0; 4353 5.1; 4788 2.4; 5267 4.6; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Polk Audio UltraFocus 8000 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Polk Audio UltraFocus 8000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 24 Hz   | 1.03 | -3.3 dB |
| Peaking | 177 Hz  | 0.42 | 2.0 dB  |
| Peaking | 642 Hz  | 2.89 | 1.0 dB  |
| Peaking | 3101 Hz | 1.19 | 6.5 dB  |
| Peaking | 5994 Hz | 4.61 | 5.0 dB  |
| Peaking | 67 Hz   | 4.19 | 0.4 dB  |
| Peaking | 1096 Hz | 3.29 | -1.3 dB |
| Peaking | 2446 Hz | 0.33 | 0.4 dB  |
| Peaking | 3067 Hz | 6.35 | -1.2 dB |
| Peaking | 8544 Hz | 2.42 | -1.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Polk%20Audio%20UltraFocus%208000/Polk%20Audio%20UltraFocus%208000.png)
# Sennheiser RS 220

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 5.7; 31 5.1; 34 4.6; 37 4.1; 41 3.6; 45 3.2; 49 2.9; 54 2.4; 60 2.0; 66 2.1; 72 2.2; 79 1.1; 87 0.2; 96 -0.4; 106 -0.8; 116 -1.1; 128 -1.3; 141 -1.4; 155 -1.6; 170 -1.4; 187 -1.5; 206 -1.5; 227 -1.2; 249 -1.0; 274 -0.8; 302 -0.7; 332 -0.7; 365 -0.5; 402 -0.5; 442 -0.2; 486 -0.1; 535 0.2; 588 0.5; 647 0.7; 712 0.5; 783 1.0; 861 0.5; 947 0.2; 1042 0.1; 1146 -0.0; 1261 0.0; 1387 1.4; 1526 4.1; 1678 4.4; 1846 4.9; 2031 1.8; 2234 -2.0; 2457 -4.0; 2703 -2.6; 2973 -0.5; 3270 0.6; 3597 2.1; 3957 4.5; 4353 6.0; 4788 6.0; 5267 4.0; 5793 1.4; 6373 3.9; 7010 -0.2; 7711 -1.0; 8482 -1.0; 9330 -2.0; 10263 -2.4; 11289 -0.2; 12418 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser RS 220 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser RS 220 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 24 Hz   |  1.41 | 6.3 dB  |
| Peaking | 46 Hz   |  2.05 | 2.1 dB  |
| Peaking | 1787 Hz |  2.97 | 6.5 dB  |
| Peaking | 2429 Hz |  3.06 | -6.0 dB |
| Peaking | 4509 Hz |  2.75 | 6.9 dB  |
| Peaking | 70 Hz   |  3.74 | 1.8 dB  |
| Peaking | 151 Hz  |  0.91 | -1.8 dB |
| Peaking | 3928 Hz |  3.64 | 0.3 dB  |
| Peaking | 6373 Hz | 11.65 | 3.5 dB  |
| Peaking | 9186 Hz |  1.92 | -2.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20RS%20220/Sennheiser%20RS%20220.png)
# Polk Audio Buckle

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -1.7; 23 -1.9; 25 -2.1; 28 -2.4; 31 -2.5; 34 -2.5; 37 -2.4; 41 -2.1; 45 -1.9; 49 -1.6; 54 -1.3; 60 -1.0; 66 -0.8; 72 -0.5; 79 -0.4; 87 -0.3; 96 -0.3; 106 -0.3; 116 -0.2; 128 -0.2; 141 0.0; 155 0.2; 170 0.2; 187 0.3; 206 0.2; 227 0.5; 249 0.8; 274 0.4; 302 -0.5; 332 -0.5; 365 0.0; 402 1.1; 442 1.6; 486 1.0; 535 0.5; 588 0.6; 647 0.8; 712 -0.3; 783 -1.2; 861 -1.0; 947 -0.4; 1042 0.3; 1146 1.0; 1261 1.8; 1387 2.4; 1526 3.1; 1678 3.8; 1846 4.2; 2031 4.5; 2234 5.5; 2457 6.0; 2703 6.0; 2973 5.3; 3270 4.8; 3597 5.8; 3957 6.0; 4353 6.0; 4788 6.0; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Polk Audio Buckle GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Polk Audio Buckle ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 32 Hz   | 1    | -2.6 dB |
| Peaking | 443 Hz  | 4.52 | 1.5 dB  |
| Peaking | 858 Hz  | 3.16 | -2.2 dB |
| Peaking | 2538 Hz | 0.88 | 5.5 dB  |
| Peaking | 5264 Hz | 2.05 | 4.9 dB  |
| Peaking | 291 Hz  | 1.76 | 1.7 dB  |
| Peaking | 316 Hz  | 3.2  | -2.4 dB |
| Peaking | 4028 Hz | 4.86 | 1.5 dB  |
| Peaking | 6399 Hz | 4.06 | 4.5 dB  |
| Peaking | 6846 Hz | 1.41 | -3.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/rtings/Polk%20Audio%20Buckle/Polk%20Audio%20Buckle.png)
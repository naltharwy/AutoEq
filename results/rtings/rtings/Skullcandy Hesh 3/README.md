# Skullcandy Hesh 3

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -1.9dB
GraphicEQ: 21 -11.5; 23 -11.1; 25 -10.7; 28 -10.1; 31 -9.4; 34 -8.7; 37 -8.0; 41 -7.2; 45 -6.5; 49 -5.8; 54 -5.1; 60 -4.6; 66 -4.5; 72 -4.8; 79 -5.4; 87 -6.4; 96 -7.3; 106 -7.9; 116 -8.0; 128 -7.9; 141 -7.4; 155 -6.6; 170 -5.8; 187 -4.8; 206 -3.7; 227 -2.4; 249 -1.3; 274 -0.4; 302 0.4; 332 1.0; 365 1.5; 402 1.8; 442 1.8; 486 1.6; 535 1.3; 588 1.1; 647 0.7; 712 0.3; 783 0.1; 861 0.0; 947 0.0; 1042 0.0; 1146 0.2; 1261 0.7; 1387 1.3; 1526 1.6; 1678 1.3; 1846 0.6; 2031 -0.4; 2234 -1.0; 2457 -1.6; 2703 -2.1; 2973 -2.9; 3270 -3.2; 3597 -2.9; 3957 -1.5; 4353 -1.9; 4788 -2.3; 5267 -2.0; 5793 -5.4; 6373 -7.8; 7010 -8.9; 7711 -7.9; 8482 -8.8; 9330 -9.4; 10263 -6.5; 11289 -2.2; 12418 0.1; 13660 -2.4; 15026 -6.0; 16529 -3.1; 18182 0.0; 20000 -5.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Skullcandy Hesh 3 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-19**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Skullcandy Hesh 3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **--0.1dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 13 Hz    | 0.58 | -11.0 dB |
| Peaking | 30 Hz    | 0.77 | -3.9 dB  |
| Peaking | 122 Hz   | 1.39 | -7.8 dB  |
| Peaking | 7882 Hz  | 1.3  | -9.5 dB  |
| Peaking | 15551 Hz | 4.65 | -5.7 dB  |
| Peaking | 419 Hz   | 1.88 | 2.6 dB   |
| Peaking | 1543 Hz  | 3.28 | 2.0 dB   |
| Peaking | 3036 Hz  | 3.45 | -2.4 dB  |
| Peaking | 9651 Hz  | 7.02 | -2.9 dB  |
| Peaking | 12145 Hz | 5.17 | 3.6 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/rtings/Skullcandy%20Hesh%203/Skullcandy%20Hesh%203.png)
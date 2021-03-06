# Grado SR125e

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 5.6; 34 4.9; 37 4.2; 41 3.5; 45 2.8; 49 2.3; 54 1.7; 60 1.2; 66 0.7; 72 0.4; 79 0.1; 87 -0.2; 96 -0.5; 106 -0.7; 116 -0.9; 128 -1.0; 141 -1.1; 155 -1.2; 170 -1.2; 187 -1.1; 206 -0.9; 227 -0.5; 249 -0.3; 274 -0.4; 302 -0.9; 332 -0.9; 365 -0.8; 402 -0.8; 442 -0.8; 486 -0.8; 535 -0.8; 588 -0.6; 647 -0.5; 712 -0.3; 783 -0.2; 861 -0.1; 947 -0.0; 1042 0.0; 1146 -0.1; 1261 -0.4; 1387 -1.0; 1526 -1.8; 1678 -3.1; 1846 -7.1; 2031 -9.5; 2234 -8.5; 2457 -7.0; 2703 -5.6; 2973 -4.3; 3270 -3.8; 3597 -4.5; 3957 -7.1; 4353 -4.3; 4788 -0.6; 5267 -3.9; 5793 -5.0; 6373 -5.5; 7010 -7.6; 7711 -7.0; 8482 -8.2; 9330 -9.5; 10263 -6.9; 11289 -3.2; 12418 -1.7; 13660 -0.6; 15026 -0.0; 16529 -0.0; 18182 -0.5; 20000 -2.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Grado SR125e GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado SR125e ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.3dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 25 Hz    | 0.71 | 6.4 dB  |
| Peaking | 121 Hz   | 0.5  | -1.5 dB |
| Peaking | 2148 Hz  | 2.59 | -9.5 dB |
| Peaking | 3913 Hz  | 5.41 | -5.0 dB |
| Peaking | 8487 Hz  | 1.46 | -9.1 dB |
| Peaking | 1390 Hz  | 0.55 | 2.4 dB  |
| Peaking | 4851 Hz  | 8.3  | 4.2 dB  |
| Peaking | 8049 Hz  | 7.7  | 3.0 dB  |
| Peaking | 9524 Hz  | 0.05 | -2.1 dB |
| Peaking | 14405 Hz | 0.95 | 3.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Grado%20SR125e/Grado%20SR125e.png)
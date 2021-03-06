# Creative Sound BlasterX H5

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.2dB
GraphicEQ: 21 -1.5; 23 -1.2; 25 -1.0; 28 -1.0; 31 -1.0; 34 -1.0; 37 -0.7; 41 -0.2; 45 0.0; 49 -0.0; 54 -0.6; 60 -1.6; 66 -2.6; 72 -3.5; 79 -4.4; 87 -5.2; 96 -6.0; 106 -6.7; 116 -7.3; 128 -7.8; 141 -8.2; 155 -8.6; 170 -8.8; 187 -9.0; 206 -9.2; 227 -9.3; 249 -9.4; 274 -9.4; 302 -8.7; 332 -8.8; 365 -8.5; 402 -8.1; 442 -7.7; 486 -7.3; 535 -6.6; 588 -5.9; 647 -5.0; 712 -3.9; 783 -2.7; 861 -1.5; 947 -0.4; 1042 0.2; 1146 0.6; 1261 0.7; 1387 0.4; 1526 -0.3; 1678 -1.2; 1846 -2.6; 2031 -4.5; 2234 -5.7; 2457 -6.2; 2703 -6.7; 2973 -6.9; 3270 -7.7; 3597 -6.3; 3957 -1.3; 4353 0.8; 4788 2.0; 5267 -2.2; 5793 -4.2; 6373 -4.8; 7010 -6.3; 7711 -6.9; 8482 -7.7; 9330 -9.2; 10263 -7.0; 11289 -0.8; 12418 0.0; 13660 -0.7; 15026 -0.9; 16529 0.0; 18182 0.0; 20000 -4.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Creative Sound BlasterX H5 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-21**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Creative Sound BlasterX H5 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-0.0dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 15 Hz    | 2.68 | -1.1 dB |
| Peaking | 174 Hz   | 0.64 | -8.6 dB |
| Peaking | 419 Hz   | 1.24 | -5.2 dB |
| Peaking | 2818 Hz  | 2.21 | -7.6 dB |
| Peaking | 8703 Hz  | 2.01 | -9.1 dB |
| Peaking | 1214 Hz  | 1.68 | 3.7 dB  |
| Peaking | 2504 Hz  | 0.27 | -1.6 dB |
| Peaking | 4775 Hz  | 3.54 | 7.1 dB  |
| Peaking | 5524 Hz  | 4.35 | -3.7 dB |
| Peaking | 12006 Hz | 4.94 | 3.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/rtings/Creative%20Sound%20BlasterX%20H5/Creative%20Sound%20BlasterX%20H5.png)
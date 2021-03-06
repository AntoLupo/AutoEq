# Mpow H5

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.8dB
GraphicEQ: 21 -0.5; 23 -1.3; 25 -1.9; 28 -2.8; 31 -3.5; 34 -4.1; 37 -4.6; 41 -5.1; 45 -5.6; 49 -6.0; 54 -6.4; 60 -6.9; 66 -7.3; 72 -7.7; 79 -8.1; 87 -8.5; 96 -8.9; 106 -9.3; 116 -9.7; 128 -10.1; 141 -10.3; 155 -10.4; 170 -10.4; 187 -10.4; 206 -10.3; 227 -10.1; 249 -9.9; 274 -9.5; 302 -9.2; 332 -9.2; 365 -9.0; 402 -8.5; 442 -7.3; 486 -5.9; 535 -4.4; 588 -3.3; 647 -2.4; 712 -1.8; 783 -1.4; 861 -0.6; 947 -0.4; 1042 -0.4; 1146 -2.0; 1261 -3.8; 1387 -5.8; 1526 -6.9; 1678 -6.9; 1846 -6.3; 2031 -6.1; 2234 -5.3; 2457 -4.5; 2703 -4.4; 2973 -5.1; 3270 -5.5; 3597 -6.2; 3957 -5.6; 4353 -4.1; 4788 -2.3; 5267 -0.9; 5793 2.5; 6373 1.0; 7010 -2.8; 7711 -5.3; 8482 -9.8; 9330 -13.2; 10263 -10.6; 11289 -3.9; 12418 0.0; 13660 0.0; 15026 -2.4; 16529 -2.7; 18182 -0.7; 20000 -1.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Mpow H5 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-38**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Mpow H5 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-0.0dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 121 Hz   | 0.43 | -9.6 dB  |
| Peaking | 326 Hz   | 1.25 | -5.0 dB  |
| Peaking | 1750 Hz  | 2.01 | -6.7 dB  |
| Peaking | 3486 Hz  | 2.57 | -5.5 dB  |
| Peaking | 9410 Hz  | 3.5  | -14.6 dB |
| Peaking | 925 Hz   | 3.34 | 2.3 dB   |
| Peaking | 6031 Hz  | 5.42 | 7.3 dB   |
| Peaking | 6277 Hz  | 2.74 | -0.5 dB  |
| Peaking | 12569 Hz | 2.76 | 4.7 dB   |
| Peaking | 12833 Hz | 0.39 | -2.3 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/sbaf-serious/Mpow%20H5/Mpow%20H5.png)
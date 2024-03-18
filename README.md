# openMEMSdesign: 
various open source and reverse engineering MEMS layouts

## pressure sensor

| [simple CMOS pressure sensor](http://opencircuitdesign.com/~tim/research/sensor/sensor.html) | [pressure_sensor](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/pressure_sensor.svg) | 
|:------------------:|:------------------:|
| ![simple CMOS pressure sensor](http://opencircuitdesign.com/~tim/research/sensor/giffiles/device.gif) | ![pressure_sensor](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/pressure_sensor.svg) |

## resonators
* claped-clamped beam microresonator in BDRIE, see documentation [here](microresonator_in_BDRIE/readme.md)

| [Tang_resonator](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/Tang_resonator.svg) | [resonator](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/resonator.svg) | 
|:------------------:|:------------------:|
| ![Tang_resonator](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/Tang_resonator.svg) | ![resonator](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/resonator.svg) |

## accelerometers

| [uni_axial_polysilicon_accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/uni_axial_accelerometer.svg) | [bulk micromachined uni_axial accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/accelerometer.svg) | [TPU_accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/TPU_accelerometer.svg) | [uniaxial_BDRIE_accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/uniaxial_BDRIE_accelerometer.svg) |
|:------------------:|:------------------:|:------------------:|:------------------:|
| ![uni_axial_polysilicon_accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/uni_axial_accelerometer.svg) | ![bulk micromachined uni_axial accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/accelerometer.svg) | ![TPU_accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/TPU_accelerometer.svg) | ![uniaxial_BDRIE_accelerometer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/uniaxial_BDRIE_accelerometer.svg) |

## gyros

| [RR-gyro](hhttps://github.com/Kolchuzhin/openMEMSdesign/blob/master/RR-gyro.svg) | LL-gyro | 
|:------------------:|:------------------:|
| ![RR-gyro](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/RR-gyro.svg) |  |

## IMU 
* [Model of an MPU-6050 6 axis accelerometer/gyroscope](https://www.printables.com/de/model/413667-mems-model-six-axis-imu-device/files)

## micromirrors

| [LMGT 2D micromirror](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/LMGT_micromirror.svg) | [micromirror](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/micromirror.svg) | [cascaded micromirror](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/cascaded_micromirror.svg) | 
|:------------------:|:------------------:|:------------------:|
| ![LMGT_micromirror](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/LMGT_micromirror.svg) | ![micromirror](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/micromirror.svg) | ![cascaded_micromirror](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/cascaded_micromirror.svg) |

## compliant mechanisms
* [Sperrklinke](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/Sperrklinke.svg)
* [mechanical_amplifier](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/mechanical_amplifier.svg)
* [indenter](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/indenter.svg)
* [Schrittschaltwerke](https://nbn-resolving.org/urn:nbn:de:bsz:ch1-200800952)

## piezoelectric circuits
<!-- * https://www.systemplus.fr/reverse-costing-reports/qorvo-qm76018-rffem-in-the-apple-iphone-xr/
-->
* https://www.i-micronews.com/products/qorvo-qm76018-rffem-in-the-apple-iphone-xr/
* Baw filter structure with internal electrostatic shielding, US20190103851A1

![BAW filter](https://s3.i-micronews.com/uploads/2019/10/SP19478-Qorvo-QM76018-RF-SiP-Apple-iPhone-Xr_3_logo-2000x0-c-default.jpg)

## test structures
* http://www-tcad.stanford.edu/~chan/mems/canonical/data_files/layout.gds
* [Hall_structures](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/Hall_structures.svg)
* [piezoresistive_structures](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/piezoresistive_structures.svg)

## microfluidic / BioMEMS
* [microfluidic_mixer](https://github.com/Kolchuzhin/openMEMSdesign/blob/master/microfluidic_mixer.svg)

===========================================================================

# commercial MEMS process:
* X-FAB: XMS10 and XMB10
* TUC ZfM: 
  * AIM (Airgap Insulation of Microstructures)
  * SCREAM (Single Crystal Reactive Etching and Metallization)
  * BDRIE (Bonding and Deep Reactive Ion Etching), 40-50um thick device layer
* IMEC: SiGeMEMS
* STMicroelectronics: ThELMA (Thick Epitaxial Layer for Microactuators and Accelerometers)
* Tronics/TDK: HARM
* GE: Polaris (5 mask layers with WLP and TSV, 100um thick device layer, 10x10mm area image)

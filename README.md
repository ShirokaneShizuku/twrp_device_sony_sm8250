# twrp_device_sony_sm8250

For building TWRP for Sony Xperia SM8250 Series (pdx203 & pdx206)

TWRP device tree for Sony Xperia SM8250 Series

NOTICE: This is not universal for ALL XPERIA MARK II SERIES(Xperia 10 II and Xperia Ace II not use Qualcomm sm8250)

The Sony Xperia SM8250 series (codenamed _"pdx203 & pdx204 & pdx206"_) are flagship smartphones from Sony.

Sony Xperia 1 II was announced and released in February 2020.[Supported]

Sony Xperia 5 II was announced and released in September 2020.[Will be merged]

Sony Xperia Pro was announced and released in February 2020.

## Device specifications

|                  Device | Xperia 1 II (pdx203)                    |
| ----------------------: | :-------------------------------------- |
|                     SoC | Qualcomm SM8250 Snapdragon 865          |
|                     CPU | 8x Qualcomm® Kryo™ 585 up to 2.84GHz    |
|                     GPU | Adreno 650                              |
|                  Memory | 8GB / 12GB (LPDDR5)                     |
| Shipped Android version | 10                                      |
|                 Storage | 256GB UFS 3.0 flash storage             |
|                 Battery | Non-removable Li-Po 4000mAh             |
|              Dimensions | 158 x 68 x 8 mm (6.22 x 2.68 x 0.31 in) |
|                 Display | 1644 x 3840 pixels, 21:9 6.5 inches     |

|                  Device | Xperia 5 II (pdx206)                    |
| ----------------------: | :-------------------------------------- |
|                     SoC | Qualcomm SM8250 Snapdragon 865          |
|                     CPU | 8x Qualcomm® Kryo™ 585 up to 2.84GHz    |
|                     GPU | Adreno 650                              |
|                  Memory | 8GB (LPDDR5)                            |
| Shipped Android version | 10                                      |
|                 Storage | 128GB / 256GB UFS 3.0 flash storage     |
|                 Battery | Non-removable Li-Ion 4000mAh            |
|              Dimensions | 158 x 68 x 8 mm (6.22 x 2.68 x 0.31 in) |
|                 Display | 1080 x 2520 pixels, 21:9 6.1 inches     |

|                  Device | Xperia Pro (pdx204)                     |
| ----------------------: | :-------------------------------------- |
|                     SoC | Qualcomm SM8250 Snapdragon 865          |
|                     CPU | 8x Qualcomm® Kryo™ 585 up to 2.84GHz    |
|                     GPU | Adreno 650                              |
|                  Memory | 12GB (LPDDR5)                           |
| Shipped Android version | 10                                      |
|                 Storage | 512GB UFS 3.0 flash storage             |
|                 Battery | Non-removable Li-Po 4000mAh             |
|              Dimensions | 158 x 68 x 8 mm (6.22 x 2.68 x 0.31 in) |
|                 Display | 1644 x 3840 pixels, 21:9 6.5 inches     |

## Features

**Works**

- Booting.

- **Decryption** (Android 10~Android 11, Android 12+ Custom ROMs)

- ADB

- MTP

- OTG

  

**Not Works**

- Vibration
- Fastbootd (Will be fixed)
- **Decryption** (On Xperia Stock Android 12 ROMs)

**Notes**

- Xperia pro **doesn't have proper kernel source yet**
- Xperia sm8250 series using Virtual A/B (vAB) instead super partitions.
- Xperia mark II devices list: Xperia 1/5/10/Ace II, Xperia Pro.

## Thanks

- [FsCrypt fix by mauronofrio](https://github.com/mauronofrio/android_bootable_recovery)

- [Decryption by bigbiff](https://github.com/bigbiff/android_bootable_recovery)

- [Oneplus 8 TWRP by mauronofrio](https://github.com/mauronofrio/android_device_oneplus_instantnoodle_TWRP)

- [Xiaomi sm8250 TWRP device tree by sekaiacg(aka.SKKK)](https://github.com/sekaiacg/android_device_xiaomi_umi_TWRP)

- [Sony SM8250 Kernel Source by hellobbn](https://github.com/hellobbn/android_kernel_sony_sm8250)

- [Xperia 1 II Old TWRP device tree by Cjybyjk](https://github.com/cjybyjk/sony_pdx203_twrp)

- [Xperia 5 II New TWRP device tree by lolipuru](https://github.com/lolipuru/twrp_device_sony_pdx206)

- [Xperia 1 II Old OrangeFox device tree by EggOxygen, although he delete it](https://github.com/ShirokaneShizuku/twrp_device_sony_pdx203)

  [Xperia 1 II lineage 17.1 device tree by sjllls, the origin one](https://github.com/sjllls/android_device_sony_pdx203))

## Credits

- [Sjllls](https://github.com/sjllls)
- [Hellobbn](https://github.com/hellobbn)
- [Lolipuru](https://github.com/lolipuru), who fixed the decryption on Android 12+
- [Cjybyjk](https://github.com/cjybyjk)
- [SekaiACG](https://github.com/sekaiacg)
- [EggOxygen](https://github.com/eggoxygen)
- [mauronofrio](https://github.com/mauronofrio)
- Shion Kagurazaka, the suck one, it's me.

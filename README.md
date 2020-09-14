# Motorola Moto Camera 2 (denali): List 3

<center><img src="https://telegra.ph/file/cf43da1a6481e7c094ff6.jpg"/></center>

Compatible Devices:

- Moto E⁶ (surfna)
- Moto G⁷ Play (channel)
- Moto G⁷ Power (ocean)
- Moto G⁷ Supra (ocean)
- Moto G⁷ Optimo (channel)
- Moto G⁷ Optimo Maxx (ocean)


**How to add it in your tree**

To clone:

`git clone https://gitlab.com/NemesisDevelopers/moto-camera/motorola_camera2_denali-2.git -b ten-arm64 packages/apps/MotCamera2`

Add this in your dependencies:

```
 {
   "repository": "motorola_camera2_denali-2",
   "target_path": "packages/apps/MotCamera2",
   "branch": "ten-arm64",
   "remote": "moto-camera"
 }
```
Add this in your device.mk or common.mk:

```
# Moto Camera 2
PRODUCT_PACKAGES += \
    MotCamera2
```

# [Download & info](https://telegra.ph/Moto-Camera-2-List-N3-05-09)


 Copyright © 2020 Nemesis Team

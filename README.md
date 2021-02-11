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

`git clone https://gitlab.com/NemesisDevelopers/moto-camera/motorola_camera2_denali-2.git -b eleven-arm64 packages/apps/MotCamera2`

`git clone https://gitlab.com/NemesisDevelopers/moto-camera/motorola_camera2_overlay.git -b ten packages/apps/MotCamera2-overlay`

`git clone https://gitlab.com/NemesisDevelopers/motorola/motorola_motosignatureapp.git -b eleven packages/apps/MotoSignatureApp`

Add this in your dependencies:

```
 {
   "repository": "motorola_camera2_denali-2",
   "target_path": "packages/apps/MotCamera2",
   "branch": "eleven-arm64",
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


 Copyright © 2020-2021 Nemesis Team

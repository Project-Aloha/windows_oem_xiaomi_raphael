
# Windows Driver Submodule for Xiaomi Redmi K20 Pro based on [SurfaceDuo-Drivers](https://github.com/WOA-Project/SurfaceDuo-Drivers/)
## [Here](https://github.com/woa-msmnile/msmnile-Drivers) is the Full Driver Pack.
<!-- ## ⚠ Remember to decompress Raphael-Drivers\components\QC8150\Graphics\qcdxwsaum.7z and put the image file into the Raphael-Drivers\components\QC8150\Graphics\GRAPHICS.SOC_QC8150.XXX_XXX_XXX/. -->
> [!NOTE]
> - This repository contains driver binary files for Xiaomi Redmi K20 Pro.
> - All driver binary files form a board support package to be used on Xiaomi Redmi K20 Pro devices to provide hardware support for the Windows operating system.
These driver files are not perfect, typos may exist, feel free to file an issue on GitHub in case you found any.

## Current status

| Feature                | Notes                                               | Status         |
|------------------------|-----------------------------------------------------|----------------|
| 🔊 Audio              |                                                     | ✅            |
| Bluetooth              |                                                     | ✅            |
| Wifi                   |                                                     | ✅            |
| UFS                    |                                                     | ✅            |
| Touch                  |                                                     | ✅            |
| GPU                    | May not work on some devices with unofficial panel. | ✅            |
| Battery                | The battery driver is not installed by default      | ⚠️            |
| Buttons                |                                                     | ✅            |
| Location               |                                                     | ✅            |
| Cellular Data          |                                                     | ✅            |
| Charge                 | Slow charging only.                                 | ⚠️            |
| 🛡️ TPM                | Only supports Windows 11 22H2 and above.            | ⚠️            |
| 🧭 Sensor             |                                                     | ✅            |
| 🧭 Light Sensor       |                                                     | ✅            |
| 🧭 Thermal Sensor     | Same with above                                     | ⚠️            |
| Haptic                 |                                                     | ❌            |

## Resources

## Copyright, License, Disclaimers and end user license agreement

**Below notice must be present in all redistributed portions of this software**

Please see [LICENSE](LICENSE.md)

## Installing manually
Check out guide: [InstallDriver](https://woa-msmnile.github.io/InstallationGuides/InstallDrivers.html)

For preserving charset encoding, please checkout with using:

```
git clone -c core.autocrlf=false https://github.com/woa-msmnile/msmnile-Drivers
```

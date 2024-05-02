
### Poco F5 Pro device trees, vendor and kernel

## Repositories that you may need to clone:
* [Poco F5 Pro Device Tree](https://github.com/Poco-F5-Pro-Mondrian-AOSP/Device-Xiaomi-Mondrian) - device/xiaomi/mondrian - [Fork of following repo](https://github.com/cupid-development/android_device_xiaomi_mondrian)
* [Poco F5 Pro Vendor Tree](https://github.com/Poco-F5-Pro-Mondrian-AOSP/vendor_xiaomi_mondrian) - vendor/xiaomi/mondrian
* [sm8450-common Device Tree](https://github.com/Poco-F5-Pro-Mondrian-AOSP/Device-sm8450-common) - device/xiaomi/sm8450-common
* [sm8450-common Vendor Tree](https://github.com/Poco-F5-Pro-Mondrian-AOSP/vendor_xiaomi_sm8450-common) - vendor/xiaomi/sm8450-common

## Kernel:
* [sm8450 Main Kernel](https://github.com/Poco-F5-Pro-Mondrian-AOSP/kernel_xiaomi_sm8450_mondrian) - kernel/xiaomi/sm8450
* [sm8450 Device Trees](https://github.com/Poco-F5-Pro-Mondrian-AOSP/kernel_xiaomi_sm8450-devicetrees) - kernel/xiaomi/sm8450-devicetrees
* [sm8450 Modules](https://github.com/Poco-F5-Pro-Mondrian-AOSP/kernel_xiaomi_sm8450-modules) - kernel/xiaomi/sm8450-modules

## Device required sepolicy:
[Sepolicy](https://github.com/Poco-F5-Pro-Mondrian-AOSP/device_xiaomi_sepolicy) - device/xiaomi/sepolicy

## Display Hal (recommended)
[Display HAL] (https://github.com/Poco-F5-Pro-Mondrian-AOSP/hardware_qcom-caf_sm8450_display) - hardware/qcom-caf/sm8450/display

## Viper support (Optional)
[ViperFx] (https://github.com/Poco-F5-Pro-Mondrian-AOSP/packages_apps_ViPER4AndroidFX) - packages/apps/ViPER4AndroidFX

## Side Note
* Currently, bringup for trees is done for EvolutionX project, please respectfully adapt for the project that you are planning to use.
* Supported build types: user (userbuild) [ENG is not supported, will crash Zygote]

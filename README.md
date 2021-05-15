# OC_EFI_NVMeFIxDebugging

EFI folder, and logs for [this issue](https://github.com/acidanthera/bugtracker/issues/1642)

- EFI: OpenCore 0.6.9 debug version folder
- panic.txt: file that contains the panic text that the system provided at restart after freeze
- opencore*.txt: log of opencore boot
- Lilu*.txt: log of LILU debug boot

My system specification:

- Laptop: Lenovo Yoga C640
- CPU: Intel i5-10210u
- RAM: 8GB DDR4
- SSD: Samsung Pm991 MZALQ512HALU-000L2
- Disk: 512GB SDD PCIe NVMe SAMSUNG PM991
- Screen: 1920x1080, touchscreen
- iGPU: Intel UHD Graphics 0x9B41

Useful kext information about Opencore EFI kexts:
- Lilu DEBUG 1.5.3
- NVMeFix 1.0.7

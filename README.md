# OpenCore-SurfacePro3
My Personal EFI that is stripped of SMBIOS and UUID. Rest is up to the people that use this. 
It is mostly Optimized for Use on Surface Pro 3 i5 4300U Model

What Works: Battery, Audio, Input/Type Cover(New w/ Spaced Keys), iMessage(AFTER YOU INJECT SMBIOS AND UUID), Graphics.

ACPI: DSDT(Battery Patched), SMBUS(SSDT), Power MGMT(ssdt-rmne),EC(Patched-In), PNLF(SSDT), HPET(SSDT)

The rest is your debugging skills. This has worked cleanly for me but, it may be different for you. Enjoy months of work that resulted in this Repo!

Supports: 10.15.7(Catalina) - 11.0(Big Sur)

Thanks to Opencore team and Rehabman for this amazing learning opportunity!

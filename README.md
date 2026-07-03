Format an SD card as fat32 (you can do the whole thing, but you only need 128mb max) and put this EFI file in the correct order ("EFI" and inside EFI, "BOOT") you should be able to chain load the OS located on the internal SD card.

Please note that this will likely only work if the SD card can already boot by itself if used in a USB reader... I've only tested this chainlauncher with steamOS (hence the steam logo), but it's supposed to look for any OS on the internal SD card reader.

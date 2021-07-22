# nuc-china-m5-mini-pc

This is worked EFI to run Hackintosh Catalina 10.15.7 (19H15) on china NUC i7-10750H version.

Follow dortania laptop guide for comet lake (https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake-plus.html#starting-point) to generate first EFI folder needed to install catalina 10.15.7 version.

After installation put this EFI folder into your EFI partition.

Issues:
For unknown reason HDMI output with IGPU acceleration won't go. To fix it i use HAMA DP to HDMI adapter to get macOS login screen when IGPU acceleration is ON.
If you attach hdmi and dp to two monitor, you can see efi and start logs on hdmi monitor, and macOS login screen on DP to HDMI adapter monitor.

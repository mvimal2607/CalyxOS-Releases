# CaxlyxOS-Releases

## Realme gt master edition [RMX3360/61/63]

## Flashing Instructions

<b>To install CalyxOS on the Realme GT Master Edition (codename: lunaa), follow these steps:</b>

1. Download Recovery
- Download the [CalyxOS Recovery](https://sourceforge.net/projects/calyxos-lunaa/files/Recovery/CalyxOS_Recovery.zip/download) file and extract it to a folder on your computer.

2. Flash the Recovery
- On Linux: Run the <b>flash.sh</b> script.
- On Windows: Run the <b>flash.bat</b> script.
This will flash the recovery and automatically boot your device into the CalyxOS recovery mode.

3. Wipe Data
In the recovery menu, select "Wipe data/factory reset" to clear existing data on the device.

4. Sideload CalyxOS
Use the following command in a terminal or command prompt to sideload the CalyxOS zip file:
``` adb sideload <path-to-filename.zip> ```

5. Wait for Completion
The sideload process will progress to 94% before finishing. This is normal—be patient until it completes.

6. Reboot
Once the sideload is done, select "Reboot system now" from the recovery menu. Congratulations! You’ve successfully flashed CalyxOS!


## Support My Work

If you find my work on this project helpful, please consider supporting me through a donation:

- [GitHub Sponsor](https://github.com/sponsors/mvimal2607)  
- [PayPal](http://paypal.me/Vimal2607)  

### Why Donations Matter for AOSP Projects

Open-source projects like this one, built on the Android Open Source Project (AOSP), thrive on community support. While AOSP provides a free and powerful foundation for custom Android development, maintaining and improving projects like this requires significant time, effort, and resources. Here’s why your donations are crucial:

- **Time Investment**: Developing, testing, and documenting features (like CalyxOS for the Realme GT Master Edition) takes countless hours of unpaid work. Donations help me dedicate more time to enhancing this project instead of balancing it with other commitments.
- **Resource Costs**: Running tests, maintaining my Linux server for building and distributing this project, and ensuring consistent updates incur expenses. Your support offsets these costs.
- **Sustainability**: AOSP projects are often passion-driven, but financial backing ensures they remain active and updated with the latest security patches, features, and Android versions.
- **Community Benefit**: Donations fuel innovation that benefits everyone—whether it’s faster bug fixes, new features, or broader device support. Your contribution keeps this project alive for all users.

Every little bit helps, whether it’s a one-time donation or ongoing sponsorship. Together, we can keep open-source Android development thriving and accessible. Thank you for considering it!

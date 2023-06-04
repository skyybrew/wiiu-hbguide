# Backing Up Your NAND

?> Making a NAND backup is very useful. It can help you fix a brick if you mess up.

!> Restoring a NAND backup requires a JTAG programmer or microsoldering knowledge. Backing up your NAND is optional, but is highly recommended.

1️⃣ Once again, revisit `wiiuexploit.xyz`. and tap `Run Exploit`. \
2️⃣ Hold down B on your gamepad until you see a menu saying `Please choose your payload`. Scroll down and press A on `nanddumper`.\
3️⃣ Use your gamepad's D-Pad to select the following options:
- Dump SLC: **yes**
- Dump SLCCMPT: **yes**
- Dump MLC: **optional**
- Dump OTP: **yes**
- Dump SEEPROM: **yes**

4️⃣ Press A to start the dumping process. This may take a while.\
Once the process has completed, copy all the `.bin` files to your computer and delete them after to save space on your SD card.

- **Continue to [Installing PayloadLoader](/payloadloader)**

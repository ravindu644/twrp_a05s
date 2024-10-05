## - Changelog for Latest TWRP Build v4 -

### Working:
- Touchscreen.
- 90hz Display.
- Fastboot mode.
- Double tap to wake.
- USB OTG and External micro SD card.
- Backup and Restore except for the mapped dynamic partitions.
- Other standard recovery operations..

### Not Working:
- **Decryption**: not planned to implement yet.

### Notes:
- I can't do anything with Samsung's read only dynamic partitions because of the usage of shared blocks or something similar. We should manually disable shared blocks by unpacking and repacking the super image.

### Screenshots:

<p align="center">
  <img src="https://github.com/user-attachments/assets/32e645b6-39cf-4c02-b5b3-e61487c63ca8" alt="TWRP Main Menu" width="400px" style="margin: 10px;">
</p>

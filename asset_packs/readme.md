# Installing Asset Packs on Flipper Zero (Momentum Firmware)

## Overview

Asset Packs customize the appearance of your Flipper Zero by adding or changing interface graphics, icons, animations, and other visual assets.

This guide explains how to install an Asset Pack on a Flipper Zero running **Momentum Firmware**.

## Requirements

- Flipper Zero device
- Momentum Firmware installed
- microSD card inserted into the Flipper Zero
- USB cable
- A compatible Asset Pack downloaded to your computer
- qFlipper or a microSD card reader

## Method 1: Install Using qFlipper

### Step 1: Download an Asset Pack

Download the Asset Pack from its original source, such as the creator's GitHub repository.

If the pack is provided as a ZIP archive, extract it on your computer first.

### Step 2: Connect Your Flipper Zero

1. Connect your Flipper Zero to your computer using a USB cable.
2. Open qFlipper.
3. Wait for the device to connect.
4. Access the SD card storage using a compatible file manager.

### Step 3: Locate the Assets Directory

Navigate to the following directory on the Flipper Zero's SD card:

`/ext/asset_packs`

Asset Packs may use different directory structures depending on their contents and firmware version.

**Important:** Check the Asset Pack's README or installation instructions before copying files. Not every pack uses the same destination directory.

### Step 4: Copy the Asset Pack

1. Locate the extracted Asset Pack files on your computer.
2. Identify the correct destination directory specified by the pack's instructions.
3. Copy the files and folders while preserving their original structure.
4. Avoid overwriting existing files unless you intend to replace them.

### Step 5: Apply the Changes

Safely disconnect your Flipper Zero and restart it if required by the Asset Pack's instructions.

Open the relevant settings or interface menu to check whether the new assets are available.

## Method 2: Install Using a microSD Card Reader

1. Turn off your Flipper Zero.
2. Remove the microSD card.
3. Insert the card into your computer using a compatible card reader.
4. Open the card's filesystem.
5. Navigate to the appropriate directory.
6. Copy the Asset Pack files into the directory specified by the pack's documentation.
7. Safely eject the card.
8. Reinsert the card into your Flipper Zero and turn it on.

## Troubleshooting

### The Asset Pack Does Not Appear

- Verify that the pack is compatible with your Momentum Firmware version.
- Confirm that the files are in the correct directory.
- Extract the archive instead of copying an unsupported ZIP file.
- Check whether the pack requires additional configuration or a restart.

### Graphics or Icons Are Missing

- Check that all required files were copied.
- Preserve the original folder structure.
- Verify that filenames and file extensions have not changed.
- Check the author's documentation for additional requirements.

### The Flipper Zero Does Not Boot Normally

- Remove recently installed files if you suspect they caused the problem.
- Restore any files you backed up before installation.
- Consult the official Momentum Firmware documentation if the problem persists.

## Important Notes

- Back up important files before modifying your SD card.
- Use Asset Packs from trusted sources.
- Do not replace firmware system files unless the pack's instructions explicitly require it.
- Asset Packs are not necessarily interchangeable between firmware versions.
- Installing an Asset Pack does not automatically update or reinstall Momentum Firmware.

## Useful Resources

- **Momentum Firmware:** https://github.com/Next-Flip/Momentum-Firmware
- **qFlipper:** https://flipperzero.one/update
- **Flipper Zero Documentation:** https://docs.flipper.net/

## Credits

Marcopiiit

## Disclaimer

Installation steps and supported directories may vary depending on the Asset Pack and Momentum Firmware version. Always follow the instructions provided by the Asset Pack's author.

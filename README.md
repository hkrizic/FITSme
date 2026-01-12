# FITSme (FITS Mask Editor for macOS)

Offline macOS app (distributed as a `.dmg`) for creating pixel masks on FITS images. Paint mask regions, preview the masked .fits file, and export FITS or DS9 region files. The app can also be used as a .fits image viewer.

## Features
- Load FITS images (.fits, .fit) via local file input.
- Mask IN/OUT modes with brush and eraser, adjustable radius.
- Choose the size of the circular brush and mask the .fits file.
- Display scaling (linear, log, sqrt, asinh, power) and colormaps.
- Pixel magnifier inspector.
- Auto stretch by percentile and ZScale.
- Export mask FITS, masked FITS, and DS9 .reg files.

## Install
1. Download the `.dmg` file. 
2. Open it and drag the app into your `Applications` folder.
3. Launch the app and load a `.fits` or `.fit` file.

## Important Information

If macOS shows the message  
**“Apple could not verify that this app is free of malware”**, this is normal for apps that are not distributed via the App Store.

To open the app anyway:

1. Open **Settings**
2. Go to **Privacy & Security**
3. Scroll down to the **Security** section
4. Click **Open Anyway** next to the app

You only need to do this once. After that, the app will open normally.

## Usage notes
- Mask OUT: painted regions are rejected (mask value 0).
- Mask IN: painted regions are kept.
- "Apply Mask" toggles between overlay view and masked rendering.

## Export formats
- `*.fits` mask (binary mask).
- `*_masked.fits` (fits file with mask applied).
- `*.reg` DS9 region file.


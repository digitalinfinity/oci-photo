# OCI Photo Helper

A privacy-first iPhone PWA for taking and exporting an OCI-format photo.

## Live app

https://digitalinfinity.github.io/oci-photo/

## What it does

- Opens the iPhone camera with a square/head/eye guide.
- Lets you use an existing photo instead.
- Crops to square and exports JPEG.
- Warns if the background looks too white, too dark, or uneven.
- Performs a simple blur/sharpness check.
- Compresses the final image to stay under 200 KB and within the 900×900 OCI upload limit.
- Processes photos locally in the browser; nothing is uploaded by the app.

## Install on iPhone

Open the live app in Safari, tap **Share → Add to Home Screen**, then launch it from the Home Screen and allow camera access.

## Important

The checks are helpers, not a guarantee of OCI acceptance. The app does not retouch Adi's face or replace the background.

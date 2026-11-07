---
title: BibbityLab Support
---

# BibbityLab Support

BibbityLab is a lightweight RAW photo editor for iPad and iPhone. It is a hobby
project developed by one person. Questions, bug reports and ideas are welcome.

[Privacy Policy](privacy.html)

## Contact

- **Bug reports and feature ideas:** [open an issue on GitHub](https://github.com/BibbityDevelops/bibbitylab.github.io/issues/)
  (a free GitHub account is needed)
- **Email:** contact.bibbity@pm.me

When reporting a problem, please include:

- your device and iOS/iPadOS version (Settings › General › About)
- the BibbityLab version (Settings › About BibbityLab in the app)
- for a photo that won't open: the camera model and file type (e.g. Sony ARW)
- what you did, what you expected, and what happened instead

Please don't attach photos you'd rather keep private. If a specific file is needed
to reproduce a problem, I'll ask.

## Frequently asked questions

### Which files can BibbityLab open?

RAW photos: Adobe DNG (including Apple ProRAW), Canon CR2/CR3, Fujifilm RAF,
Hasselblad 3FR, Nikon NEF, Olympus/OM System ORF, Panasonic RW2, Pentax PEF,
Samsung SRW and Sony ARW. JPEG and HEIC photos are not supported.

Support for individual cameras depends partly on the RAW engine built into iOS and
iPadOS. Very new camera models may only work after an iOS update.

### How do I add photos?

- **From a folder:** in the sidebar, tap **+ › Add Folder…** and choose a folder in
  Files, on an external drive or on an SD card.
- **From the Photos app:** tap **+ › Import from Photos…** and select the photos.
  BibbityLab only sees the photos you select. RAW versions are copied into the
  folder "Imported from Photos"; photos without a RAW version are skipped.

### Are my original photos changed?

No. Edits are stored separately and only applied when you view or export a photo.
The original file is never modified.

### Where are my edits stored?

In the app on your device. Optionally (Settings › Backups), BibbityLab also keeps a
small backup of each photo's edits in a hidden folder named `.bibbitylab` next to
the photo, so edits can be restored after reinstalling the app or when opening the
same folder on another device.

### Are imported photos included in my iCloud backup?

No. Copies imported from the Photos app are excluded from device backups because the
originals are still in Photos. Your edits and labels are backed up as part of the
app's data.

### What is the difference between "Hide" and "Delete"?

- **Hide** only removes the photo from BibbityLab's library. The file stays on your
  device. Bring it back with **Sort › Show Hidden Photos**.
- **Delete from Device** permanently deletes the RAW file and its edits. For photos
  imported from the Photos app, only BibbityLab's copy is deleted; the original in
  Photos is not affected.

### A folder can no longer be opened

Remove the folder from the sidebar (long-press › Remove from Library) and add it
again. This renews the permission to access it. Your edits are kept.

### A photo shows an error instead of opening

The file's format or camera model may not be supported yet. Please report it with
the camera model and file type (see Contact above).

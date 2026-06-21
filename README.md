# DICOM Pocket

DICOM Pocket is a local-first DICOM viewer for opening medical imaging files directly on your device. It helps you view DICOM image series, export images as PNG, and prepare ZIP packages for sharing.

Files are handled on your device. No account, cloud upload, or server is required for the core viewing and export workflow.

> Not for diagnosis. DICOM Pocket is not a medical device and must not be used for diagnosis, treatment decisions, triage, or emergency care.

## Store Links

- Apple App Store: [DICOM Pocket](https://apps.apple.com/us/app/dicompocket/id6764627571)
- Android: Google Play release in progress.

## What It Does

- Open local `.dcm`, `.dicom`, and ZIP files.
- View imported DICOM image series.
- Navigate image stacks by slice.
- Adjust image viewing with window/level, zoom, and pan controls.
- Use measurement tools for non-diagnostic reference.
- Export the current image as PNG.
- Package selected series as ZIP files for sharing.
- Use the app in multiple languages.
- Work across phone, tablet, desktop, iPad, and macOS layouts.
- On supported macOS builds, optional Segmentator overlays may run locally with TotalSegmentator.

## Segmentator And Open Source Notices

The optional Segmentator feature may use [TotalSegmentator](https://github.com/wasserth/TotalSegmentator), an open-source tool for anatomical segmentation of CT and MR images.

DICOM Pocket uses TotalSegmentator only for local, non-diagnostic visualization. It is not affiliated with or endorsed by TotalSegmentator, University Hospital Basel, or the TotalSegmentator authors.

DICOM Pocket is intended to expose only TotalSegmentator tasks that are available for any usage under Apache-2.0, such as `total` for CT and `total_mr` for MR. TotalSegmentator tasks that require a separate commercial license or are marked non-commercial-only are not included unless a separate license review and notice update is completed first.

See [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md) for license, attribution, citation, and restricted-task notes.

## Privacy

DICOM Pocket is built around local file handling:

- Imported DICOM files remain on the user's device.
- Files are shared only when the user explicitly exports or uses the operating system share sheet.
- The app does not require an account for local viewing.
- The app does not include advertising features.
- The app does not collect, sell, or upload personal data.
- Segmentator processing, when enabled, runs locally. DICOM Pocket does not upload selected DICOM studies to a cloud segmentation service.

See [PRIVACY.md](./PRIVACY.md) for the privacy policy draft.

## Intended Use

DICOM Pocket is intended for personal file viewing, organization, export, and sharing preparation. It can be useful when you need to review imaging files you already have on your device or prepare copies to share through your device's normal sharing tools.

It is not intended to replace clinical workstations, PACS systems, radiology review software, or professional medical advice.

## Search Keywords

DICOM viewer, DICOM file opener, medical imaging viewer, local DICOM viewer, DICOM PNG export, DICOM ZIP viewer, offline DICOM viewer, iOS DICOM viewer, Android DICOM viewer, macOS DICOM viewer.

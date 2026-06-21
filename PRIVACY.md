# DICOMPocket

DICOM Pocket processes selected DICOM, ZIP, and image files locally on the user’s device.

The app does not require an account, does not upload medical files to a server, and does not sell user data.

Exported PNG or ZIP files are created locally. Sharing or emailing only happens after the user chooses to share the exported file.

## Segmentator Processing

On supported macOS builds, the optional Segmentator feature may run local anatomical segmentation with TotalSegmentator.

Segmentator processing is designed to run on the user's device. DICOM Pocket does not upload selected DICOM studies, medical images, or generated segmentation outputs to a cloud segmentation service.

Installing or updating Segmentator dependencies or model weights may contact third-party package or model hosts, but DICOM Pocket does not send selected patient image data to those hosts for segmentation.

## Data Retention and Deletion

DICOM Pocket processes DICOM files locally on your device. We do not upload, store, or retain your DICOM files, medical images, studies, series, or related metadata on any servers



The app is not intended for medical diagnosis.

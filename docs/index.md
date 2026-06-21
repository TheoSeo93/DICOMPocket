# DICOMpocket Support

Thank you for using DICOMpocket.

DICOMpocket is an application for viewing DICOM medical imaging files on supported Apple platforms.

> Not for diagnosis. DICOMpocket is not a medical device and must not be used for diagnosis, treatment decisions, triage, or emergency care.

## Contact

For support, questions, bug reports, or feature requests, please contact:

**Email:** [dev.theo.cs@gmail.com](mailto:dev.theo.cs@gmail.com)

You can also report issues on GitHub:

**GitHub Issues:** https://github.com/TheoSeo93/DICOMPocket/issues

## Frequently Asked Questions

### What is DICOMpocket?

DICOMpocket is an app for viewing DICOM medical imaging files, including CT series and MPR views where supported.

### What file types are supported?

DICOMpocket supports DICOM files and common import methods such as files, folders, and ZIP archives, depending on the platform and file source.

### Why does a series not open or show MPR?

Some DICOM series may not support MPR if the dataset is incomplete, unsupported, or contains localizer images instead of a full CT volume.

### What is Segmentator?

On supported macOS builds, DICOMpocket may include an optional Segmentator feature for local anatomical segmentation overlays. Segmentator may use the open-source [TotalSegmentator](https://github.com/wasserth/TotalSegmentator) project.

Segmentator is for non-diagnostic visualization and reference only. It is not a medical device feature and must not be used for diagnosis, treatment decisions, triage, or emergency care.

### Does Segmentator upload my files?

No. Segmentator processing is designed to run locally on your device. DICOMpocket does not upload selected DICOM studies to a cloud segmentation service.

Installing or updating Segmentator dependencies or model weights may contact third-party package or model hosts, but DICOMpocket does not send selected patient image data to those hosts for segmentation.

### What third-party licenses apply to Segmentator?

Segmentator may use TotalSegmentator. DICOMpocket is intended to expose only TotalSegmentator tasks that the TotalSegmentator project identifies as openly available for any usage under Apache-2.0, such as `total` for CT and `total_mr` for MR.

TotalSegmentator tasks that require a separate commercial license or are marked non-commercial-only are not included unless a separate license review and notice update is completed first.

See [Third-Party Notices](./third-party-notices.html) for TotalSegmentator attribution, license, restricted-task, and citation notes.

### How do I report a bug?

Please email us or open a GitHub issue with the following information:

* Device model
* OS version
* App version
* Steps to reproduce the issue
* A short description of what happened

Please do not share personal health information or identifiable patient data when reporting issues.

### Does DICOMpocket upload my files?

DICOMpocket is designed to open files selected by the user. Please refer to the privacy policy for details.

## Privacy Policy

Privacy Policy: https://github.com/TheoSeo93/DICOMPocket/blob/main/PRIVACY.md

## Third-Party Notices

Third-Party Notices: https://github.com/TheoSeo93/DICOMPocket/blob/main/THIRD_PARTY_NOTICES.md

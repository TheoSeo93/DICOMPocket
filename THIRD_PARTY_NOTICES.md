# Third-Party Notices

This document lists third-party software and model components that may be used by DICOM Pocket features.

## TotalSegmentator

DICOM Pocket's optional Segmentator feature may use TotalSegmentator for local anatomical segmentation overlays on supported macOS builds.

- Project: TotalSegmentator
- Source: https://github.com/wasserth/TotalSegmentator
- License: Apache License 2.0 for the openly available tasks identified by the TotalSegmentator project
- Apache License text: [docs/licenses/apache-2.0.txt](./docs/licenses/apache-2.0.txt)
- Official Apache License URL: https://www.apache.org/licenses/LICENSE-2.0
- Created by: Department of Research and Analysis, University Hospital Basel

TotalSegmentator is a third-party project. DICOM Pocket is not affiliated with, sponsored by, or endorsed by TotalSegmentator, University Hospital Basel, or the TotalSegmentator authors.

### Tasks Used By DICOM Pocket

DICOM Pocket is intended to expose only TotalSegmentator tasks that the TotalSegmentator project identifies as openly available for any usage under Apache-2.0, including:

- `total` for CT images
- `total_mr` for MR images

These tasks are used for local visualization and reference overlays only. DICOM Pocket is not a medical device and must not be used for diagnosis, treatment decisions, triage, or emergency care.

### Restricted Or Separately Licensed Tasks

As of June 21, 2026, TotalSegmentator lists some tasks as requiring a separate license, available free for non-commercial usage only, or otherwise restricted. DICOM Pocket does not include or enable those tasks for commercial distribution unless a separate commercial license review and notice update is completed first.

Examples include:

- `heartchambers_highres`
- `appendicular_bones`
- `appendicular_bones_mr`
- `tissue_types`
- `tissue_types_mr`
- `tissue_4_types`
- `brain_structures`
- `vertebrae_body`
- `face`
- `face_mr`
- `thigh_shoulder_muscles`
- `thigh_shoulder_muscles_mr`
- `coronary_arteries`
- `coronary_arteries_LEGACY`
- `aortic_sinuses`
- `brain_aneurysm`, which TotalSegmentator identifies as CC BY-NC 4.0 with no commercial license available

Check the upstream TotalSegmentator README and license information before enabling any additional task.

### Citation

If Segmentator results are used in academic or research contexts, please cite the publications requested by the TotalSegmentator project, including the TotalSegmentator paper and nnU-Net paper. For MR usage, also cite the TotalSegmentator MRI paper requested by the upstream project.

Upstream citation guidance:

- https://github.com/wasserth/TotalSegmentator
- https://pubs.rsna.org/doi/10.1148/ryai.230024
- https://pubs.rsna.org/doi/10.1148/radiol.241613
- https://github.com/MIC-DKFZ/nnUNet

### Local Processing

Segmentator processing is designed to run locally on the user's device. DICOM Pocket does not upload selected DICOM studies to a cloud segmentation service. Installing or updating TotalSegmentator dependencies or model weights may contact third-party package or model hosts, but DICOM Pocket does not send selected patient image data to those hosts for segmentation.

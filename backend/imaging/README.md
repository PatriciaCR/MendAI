# Medical Imaging Service

This service handles medical image processing using MONAI for segmentation, detection, and classification of medical scans.

## Setup

REQUIRES GPU SUPPORT

1. Install dependencies:
   ```bash
   poetry install
   ```

2. Run the service:
   ```bash
   poetry run uvicorn main:app --reload --host 0.0.0.0 --port 8002
   ```

## Features
- Medical image segmentation
- Disease detection and classification
- DICOM file processing
- MONAI model integration 
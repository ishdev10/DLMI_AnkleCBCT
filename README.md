# Distal tibiofibular joint segmentation in CT
**Authors**: Isha Dev, Liora Dsilva

This is the repository containing the code for the Deep Learning for Medical Imaging Spring 2025 course project: Distal tibiofibular joint segmentation in CT

This project implements a 2D deep learning pipeline to segment the fibula, tibia, and talus bones from axial slices of ankle CBCT scans. It explores U-Net variants (baseline, Attention U-Net), stacked slice inputs (2.5D), class-weighted and focal losses, and data augmentation. The dataset is preprocessed from .npz volumes and evaluated using Dice and pixel accuracy metrics.

The dataset consists of 40 high-resolution 3D cone-beam CT (CBCT) scans of the ankle joint, each with corresponding ground truth segmentations for the fibula, tibia, and talus. Each volume contains approximately 384 × 384 × 576 voxels at an isotropic resolution of 0.5 mm³, acquired using a Carestream OnSight 3D CBCT system.

# D2-Seg: breast ultrasound segmentation examples

Three paired ultrasound examinations from the 76-case test split. Each row shows B-mode ultrasound (BUS), shear-wave velocity (SWV), shear-wave time (SWT), and the final segmentation on BUS (green contour). Display panels are cropped and resized; Dice is evaluated on the original BUS grid.

**Test performance:** D2-Seg achieved a mean Dice of **72.10%** and a mean IoU of **58.11%** on the 76-case test split using the U-Net student (seed 128) and MedGemma-27B-it review.

The examples below come from a separate run with a three-branch U-Net++ student (seed 124) and nine-candidate MedGemma review. They were selected near the 25th, 50th and 75th percentiles of case-level Dice for that run.

### Example 1 — Dice 63.17%

![Example 1: BUS, SWV, SWT and BUS prediction](examples/example-01.png)

### Example 2 — Dice 74.74%

![Example 2: BUS, SWV, SWT and BUS prediction](examples/example-02.png)

### Example 3 — Dice 83.66%

![Example 3: BUS, SWV, SWT and BUS prediction](examples/example-03.png)

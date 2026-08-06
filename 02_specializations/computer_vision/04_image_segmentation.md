# Image Segmentation & Generative Vision

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study U-Net architecture paper for Biomedical Image Segmentation
**Resource:** [https://arxiv.org/abs/1505.04597](https://arxiv.org/abs/1505.04597)

**Acceptance Criteria:**
- [ ] Read the U-Net paper completely
- [ ] Understand encoder-decoder with skip connections
- [ ] Understand why U-Net works well for biomedical images

**Deliverable:** Paper summary with architecture diagram

---

### Understand Semantic vs Instance Segmentation vs Panoptic Segmentation
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Define semantic segmentation (pixel-level class labels)
- [ ] Define instance segmentation (separate objects)
- [ ] Define panoptic segmentation (combines both)
- [ ] Give use-case examples for each type

**Deliverable:** Comparison document with examples

---

### Practice Mask R-CNN & Segment Anything Model (SAM) APIs
**Resource:** [https://segment-anything.com/](https://segment-anything.com/)

**Acceptance Criteria:**
- [ ] Run Mask R-CNN inference on sample images
- [ ] Run SAM inference with point and box prompts
- [ ] Compare output quality and speed

**Deliverable:** Notebook with Mask R-CNN + SAM examples

---

### Mini-Project: Build a U-Net model in PyTorch for background removal
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement U-Net architecture in PyTorch (encoder + decoder + skip connections)
- [ ] Train on image segmentation dataset
- [ ] Implement dice loss or IoU loss
- [ ] Evaluate with pixel accuracy and mean IoU
- [ ] Visualize predicted masks vs ground truth

**Deliverable:** PyTorch U-Net implementation with training script

---


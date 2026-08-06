# Object Detection (YOLO, Faster R-CNN)

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Study YOLO architecture & Faster R-CNN papers
**Resource:** [https://arxiv.org/abs/1506.02640](https://arxiv.org/abs/1506.02640)

**Acceptance Criteria:**
- [ ] Read YOLO v1 paper and understand grid-based detection
- [ ] Read Faster R-CNN paper and understand region proposals
- [ ] Compare one-stage vs two-stage detectors

**Deliverable:** Paper comparison notes

---

### Understand Bounding Box Regression, IoU, and Non-Maximum Suppression
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Implement IoU calculation from scratch
- [ ] Explain how bounding box regression works
- [ ] Implement Non-Maximum Suppression algorithm
- [ ] Understand anchor boxes concept

**Deliverable:** Python implementations of IoU and NMS

---

### Practice Ultralytics YOLOv8 Python API
**Resource:** [https://docs.ultralytics.com/](https://docs.ultralytics.com/)

**Acceptance Criteria:**
- [ ] Install and run YOLOv8 on sample images
- [ ] Use different model sizes (n, s, m, l, x)
- [ ] Run inference with confidence threshold tuning

**Deliverable:** Notebook with YOLOv8 inference examples

---

### Mini-Project: Train a custom YOLOv8 object detector on custom dataset
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Label custom dataset with 3+ classes (use LabelImg or Roboflow)
- [ ] Format dataset in YOLO format
- [ ] Train YOLOv8 on custom dataset
- [ ] Evaluate with mAP@50 and mAP@50:95
- [ ] Run inference on test images and visualize results

**Deliverable:** Custom trained YOLOv8 model with evaluation

---


# Vizcontext

---

## Abstract

---

In real world applications, object detection systems often function on image streams, where subsequent frames have small time deltas. However, they do not make use of contextual information in previous frames to guide their understanding of the current frame.

Current object detection and recognition systems function purely on singular frames. Video systems function the same way, in that they break a video down into subsequent frames which then pass through the system independently. 

Introducing a contextual layer based on a typical transformer architecture, that builds context as it processes subsequent frames,  improves both performance and accuracy of object detection and recognition systems.

## Main goals

---

- Drop in solution for existing models (yolo, detectron, etc).
- Minimal change to existing model training code.

> This is an open research project. As such, ideas and code will be gradually contributed to the repo until the solution sufficiently achieves the main goals.
# Plant-Classification-AI-ML-

# Plant Species Classifier (Curry vs Mint) — Built with Edge Impulse

This project uses a machine learning model trained via Edge Impulse to classify images of two common plant species: **curry** and **mint**. 

---

## Classification Setup

- **Platform**: Edge Impulse Studio
- **Classes**: `curry`, `mint`
- **Dataset**: 256 total images (128 per class), captured manually
- **Image Size**: 96 X 96
- **Learing model**: Image Processing


## Observations

- Image quality (resolution, lighting) and size had a significant impact on training and testing.
- Balanced datasets with varied angles improved generalization.

> YOLOv5 was my original choice for this project, but due to system limits, I moved forward with Edge Impulse. I plan to try YOLOv5 again later and update this project.

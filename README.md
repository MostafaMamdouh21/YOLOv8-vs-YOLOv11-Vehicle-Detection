# YOLOv8 vs YOLOv11: Vehicle Detection Before and After Fine-Tuning

## 🌟 Overview

This project compares the performance of YOLOv8 and YOLOv11 for vehicle detection, evaluating their accuracy, speed, and effectiveness before and after fine-tuning on a custom dataset. The goal is to analyze how fine-tuning impacts detection performance and which model performs better in real-world scenarios.

## 📂 Project Structure

- **data/** - Contains the dataset used for training and evaluation.
- **models/** - Pre-trained and fine-tuned weight files for YOLOv8 and YOLOv11.
- **results/** - Performance metrics and comparison reports.
- **visuals/** - Detection outputs for visual comparison.

## 🚀 Features

- **Pre-trained vs Fine-tuned Analysis** - Compare the models before and after fine-tuning.
- **Performance Metrics** - mAP, precision, recall, FPS, and fitness.
- **Reproducibility** - Step-by-step instructions to replicate the results.

## 📊 Results

### YOLOv8 Metrics

| Metric | Value |
|--------|-------|
| Precision (B) | 0.910 |
| Recall (B) | 0.905 |
| mAP50 (B) | 0.965 |
| mAP50-95 (B) | 0.706 |
| Fitness | 0.732 |

### YOLOv11 Metrics

| Metric | Value |
|--------|-------|
| Precision (B) | 0.907 |
| Recall (B) | 0.906 |
| mAP50 (B) | 0.966 |
| mAP50-95 (B) | 0.711 |
| Fitness | 0.736 |

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/YOLOv8-vs-YOLOv11-Vehicle-Detection.git
   cd YOLOv8-vs-YOLOv11-Vehicle-Detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🖼️ Visualizations
Detection results are available in the `visuals/` folder, showcasing:
- Pre-trained model detections.
- Fine-tuned model detections.
- Side-by-side comparisons of YOLOv8 and YOLOv11.

## 📚 License
This project is licensed under the [MIT License](LICENSE).

## 👥 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📧 Contact
For any questions or feedback, feel free to reach out at mostafamamdouh340@gmail.com

---

Let me know if you'd like any modifications! 🚀


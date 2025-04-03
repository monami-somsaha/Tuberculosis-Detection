# Tuberculosis Detection from Chest X-Rays

Tuberculosis (TB) remains a critical global health challenge, requiring efficient and accurate diagnostic methods. This project focuses on leveraging machine learning techniques to classify chest X-ray images as either normal or tuberculosis-infected.

## Dataset
The dataset used consists of:
- **Training Set:** 2,940 chest X-ray images
- **Testing Set:** 1,260 chest X-ray images

This makes it a **binary classification problem**, where the goal is to correctly differentiate between normal and TB-positive chest X-rays.

## Evaluation Metrics
The performance of models is assessed using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score** (used as the final benchmark metric)

## Approach
The classification model is built using deep learning techniques, ensuring robustness and generalization across unseen test data. The final model submission is evaluated against a predefined benchmark using the F1-score metric.

## Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/tb-detection.git
   cd tb-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model training:
   ```bash
   python train.py
   ```
4. Evaluate the model:
   ```bash
   python evaluate.py
   ```

## License
This project is licensed under the MIT License.

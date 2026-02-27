# Dog Cardiomegaly Detection

This project focuses on detecting **Dog Cardiomegaly** (enlarged heart) from X-ray images using Deep Learning techniques. 

### Highlight: 85.75% Accuracy! 🎉
Our **EfficientNet-B7** model achieved an impressive **85.75%** accuracy on the validation app, standing out as one of the best results.

![Validation Accuracy](Screenshot\ 2025-04-13\ at\ 5.20.34 PM.png)

## Approach & Model Training

I initially experimented with **ResNet**, extracting features and evaluating different architectures. To push performance further, I switched to the **EfficientNet-B7** architecture. 

1. **Data Preparation**: Loading, preprocessing, and exploratory data analysis of the X-ray images.
2. **Model Training (EfficientNet-B7)**: The model was trained to accurately classify the images, overcoming the limitations of simpler architectures.
3. **Evaluation**: We evaluated the models, saving predictions and comparing performance, ultimately reaching the 85.75% accuracy mark.

The full workflow is available in the included Jupyter Notebooks.

## Files Included

- `Project_one_prashant_Soni.ipynb` & `Week9_Prashant_Soni.ipynb`: Notebooks containing data processing, model training, feature extraction, and evaluation code.
- Prediction CSVs and evaluation screenshots (e.g., loss curves and accuracy metrics).

## 📄 Read the Full Research
For more details on the methodology and findings, check out the full publication on ResearchGate:
[Deep Learning Approach for Canine Cardiomegaly Detection Using EfficientNet Architecture](https://www.researchgate.net/publication/390748739_Deep_Learning_Approach_for_Canine_Cardiomegaly_Detection_Using_EfficientNet_Architecture?_sg%5B0%5D=eTatRuVExTT4iMjt6lDkyVaBmJs8Z8QehOdgNolrd5Q-5WSQLc09OZL_MsKi1pJO1y2fv1j_D5MApCcz293PNxkguxpG5Ftdw8UhT7Zu.COJGnOvPfC1G4RL8miNpKdFPsW7SOPasDUYe6gZDrZbs6G7tXfvBIP8mPN7AHBH77-jQ_J05iHVdpTkDCRUF7g&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InByb2ZpbGUiLCJwYWdlIjoicHJvZmlsZSIsInBvc2l0aW9uIjoicGFnZUNvbnRlbnQifX0)

## Author

**Prashant Soni**

Feel free to reach out with any questions about this project!

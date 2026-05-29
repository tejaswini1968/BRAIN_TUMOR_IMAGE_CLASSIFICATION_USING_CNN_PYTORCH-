Developed an end-to-end deep learning pipeline to automate medical image classification, distinguishing between "Healthy" and "Brain Tumor" scan types from a heterogeneous dataset.

Technical Core Competencies
•	Deep Learning Frameworks: PyTorch, Torchvision, Torchinfo
•	Hyperparameter Optimization: Optuna (Automated search for layers, filters, dropout, and learning rates)
•	Data Engineering & Preprocessing: Pathlib, DataLoaders, PIL Image Mode Conversions (RGBA/L/P to RGB)
•	Data Augmentation: Geometric transformations (Random Rotation, Horizontal Flip, Resizing to 256x256)
•	Performance Evaluation: Matplotlib, Scikit-learn (Classification Report, Confusion Matrix, Loss/Accuracy Curves)

Key Achievements & Workflow
•	Data Pipeline Engineering: Successfully ingested 4,600 multi-format (JPEG, PNG, TIFF, etc.) medical images of varying resolutions and color profiles. Standardised data into uniform 256x256 RGB formats using PyTorch transforms.
•	Automated Architecture Tuning: Utilized Optuna to dynamically determine optimal network parameters, including convolution layer depth, filter counts, kernel sizes, dropout rates, and dense layer configurations.
•	Robust Model Evaluation: Implemented rigorous 80/20 train/validation splits. Monitored model convergence over 28 epochs using loss and accuracy curves to prevent overfitting.
•	Clinical Diagnostic Metrics: Secured a 98.48% validation accuracy. Validated clinical reliability using a confusion matrix and a detailed classification report to guarantee minimal false-negative rates.


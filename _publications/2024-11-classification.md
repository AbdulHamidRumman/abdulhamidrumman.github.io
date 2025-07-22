---
title: "Classification of CoCr-based magnetic thin films via GLCM texture features extracted from EFTEM images and machine learning"
collection: publications
category: manuscripts
permalink: /publication/2024-11-classification
excerpt: "<ul>
                <li>GLCM (Gray-level Co-occurrence Matrix) based texture features effectively classify CoCr-based magnetic thin films using EFTEM images.</li>
                <li>LightGBM and ANN models achieved classification accuracies exceeding 85%, with ANN reaching 100% accuracy</li>
                <li>Image segmentation strategy significantly impacts model performance, with 18 segments proving optimal for the ANN model.</li>
                <li>SHAP analysis revealed feature importance, highlighting the ANN's ability to utilize a broader range of features for pattern identification.</li>
          </ul>"
date: 2024-11
venue: 'AIP Advances'
paperurl: 'https://doi.org/10.1063/5.0232442'
---
### Abstract
Gray-level co-occurrence matrix (GLCM) texture features offer a powerful technique for image analysis in various fields, including medical diagnostics and material classification. This research investigates their efficacy in classifying CoCr-based magnetic thin films—Co<sub>84</sub>Cr<sub>16</sub>, Co<sub>80</sub>Cr<sub>16</sub>Pt<sub>4</sub>, Co<sub>80</sub>Cr<sub>16</sub>Ta<sub>4</sub>, and Co<sub>76</sub>Cr<sub>16</sub>Ta<sub>4</sub>Pt<sub>4</sub>—using energy-filtered transmission electron microscopy (EFTEM) images. The raw EFTEM images were preprocessed to divide into variable quantities of equal segments (9, 18, or 36), leading to three distinct training and testing sets. Light Gradient Boosting Machine (LightGBM) and Artificial Neural Network (ANN) were employed, achieving accuracies exceeding 85%. Besides the accuracy metric, the ML models underwent a comprehensive evaluation using precision, recall, F1-score for each class, and 10-fold cross-validation. Furthermore, a comparative study between the LightGBM and ANN models was performed by conducting feature importance analysis using SHapley Additive exPlanations (SHAP). Notably, both ML models exhibit an accuracy of over 85%. Furthermore, the strategic segmentation of images into 18 equal pieces yielded 100% accuracy using the ANN model. The research delves into the nuanced dynamics surrounding the impact of training and testing set size on the model’s performance. Finally, the feature importance analysis via SHAP identifies pivotal contributors, accentuating the ANN model’s adeptness in leveraging a broader spectrum of features for pattern identification and underscoring the effectiveness of neural network-based models in navigating the intricate landscape of image classification tasks.
<img src="/images/graphical-abstracts/classification-2024-11.jpg" width="600px" height="400px">

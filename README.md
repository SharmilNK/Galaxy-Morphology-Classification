# Galaxy Morphology Classification: Multi-Model Comparison

A comprehensive galaxy morphology classification system that compares three approaches on the Galaxy Zoo Challenge dataset: naive baseline, classical machine learning with hand-crafted CAS features, and deep learning CNNs for automated feature extraction.

##  Project Overview

This project implements and evaluates three classification approaches to distinguish between elliptical and spiral galaxies:
- **Naive Baseline**: Majority class predictor
- **Classical ML**: Random Forest with CAS (Concentration, Asymmetry, Smoothness) features
- **Deep Learning**: CNN (ResNet/EfficientNet) with end-to-end learning

##  Scientific Significance

Galaxy morphology classification enables:

1. **Galaxy Evolution Studies:** Understanding how galaxies form and evolve over cosmic time
2. **Dark Matter Mapping:** Morphology correlates with dark matter distribution
3. **Star Formation Analysis:** Spiral galaxies show active star formation; ellipticals do not
4. **Large-Scale Structure:** Mapping universe structure through galaxy clustering
5. **Supernova Host Analysis:** Predicting supernova types based on host galaxy morphology

##  Key Features

- Automated CAS feature extraction from galaxy images
- Balanced dataset handling (500 elliptical + 500 spiral galaxies)
- Comparative analysis across three modeling paradigms
- Interactive web application for real-time galaxy classification
- Comprehensive evaluation metrics and visualizations


### Launch Web App
```bash
cd app
python app.py
```

Navigate to `http://localhost:5000` to classify galaxies interactively.





##  References

- Lintott et al. (2008) - Galaxy Zoo: morphologies derived from visual inspection
- Willett et al. (2013) - Galaxy Zoo 2: detailed morphological classifications
- Dieleman et al. (2015) - Rotation-invariant CNNs for galaxy morphology
- Walmsley et al. (2022) - Galaxy Zoo DECaLS: Detailed visual morphology


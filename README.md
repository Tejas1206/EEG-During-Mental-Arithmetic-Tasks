# EEG-During-Mental-Arithmetic-Tasks

**Dataset Link** - https://physionet.org/content/eegmat/1.0.0/

### Summary:
1. **Data Loading and Preprocessing:**
   - Loaded EEG data using MNE library, concatenated multiple files for both rest and task states.
   - Preprocessed data by applying re-referencing and epoching.

2. **Power Spectral Density (PSD) Analysis:**
   - Computed PSD using Welch's method for both rest and task states.
   - Visualized PSD comparison between rest and task states.

3. **Feature Extraction:**
   - Defined functions to extract various statistical features from EEG epochs.
   - Extracted features from epochs and prepared them for model training.

4. **Model Training:**
   - Implemented EEGNet and TSception model using TensorFlow/Keras for classification.
   - Trained the models, evaluated its performance on test data, and generated a classification report.


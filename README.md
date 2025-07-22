# GAN-on-dengue-time-series-data

In my undergraduate thesis, I implemented a Generative Adversarial Network (GAN) using PyTorch to impute missing values in dengue time series data. The missing rate patterns were based on missing rate–gap length distributions extracted from a global dengue dataset. For simulation, I used dengue data from Davao City, sourced from the Thinking Machines Project CCHAIN. 

## 📁 Repository Files

- `Data/`:  
  Contains the dengue time series dataset and the missing rate - gaplength data obtained from OpenDengueData with artificially induced missing values.

- 'OpenDengueData/':
  Public dataset obtained from Clarke et al., consisting of global dengue case reports. Used as a reference or external validation set for dengue trends.

- 'GAN_torch_code.ipynb':
  Contains the core PyTorch implementation of the GAN model used for imputing missing time series data.

- 'GAN_validations.ipynb':
  To evaluate imputation performance of the GAN model using:  
    RMSE (Root Mean Squared Error)
    SMAPE (Symmetric Mean Absolute Percentage Error)
    MAE (Mean Absolute Error)
    Cosine Distance
    Linfoot’s Criteria (Fidelity, Structural Content, Correlation)
  This includes visualization to compare original and imputed time series data.


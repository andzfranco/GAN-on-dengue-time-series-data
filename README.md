# GAN-on-dengue-time-series-data
In this project, I implemented a Generative Adversarial Network (GAN) using PyTorch to impute missing values in dengue time series data. I obtained missing rate - gaplength data from a publicly available dengue dataset as basis in performing simulations. I used the dengue data in Davao City from Thinking Machines Project CCHAIN as my data for simulations.

📁 Repository Files

Data/
Contains the dengue time series dataset and the missing rate - gaplength data obtained from OpenDengueData with artificially induced missing values.

OpenDengueData/
Public dataset obtained from Clarke et al., consisting of global dengue case reports. Used as a reference or external validation set for dengue trends.

GAN_torch_code.ipynb
Contains the core PyTorch implementation of the GAN model used for imputing missing time series data.

GAN_validations.ipynb
To evaluate imputation performance of the GAN model using:

RMSE (Root Mean Squared Error)

SMAPE (Symmetric Mean Absolute Percentage Error)

MAE (Mean Absolute Error)

Cosine Distance

Linfoot’s Criteria (Fidelity, Structural Content, Correlation Measure)

This includes visualization to compare original and imputed time series data.


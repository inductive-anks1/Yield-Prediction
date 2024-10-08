# Yield Prediction

This repository contains the code for yield prediction. Follow the instructions below to set up the project on your local machine.

## Getting Started

### 1. Clone the Repository

First, clone the repository into a folder on your local machine:

```
git clone https://github.com/inductive-anks1/Yield-Prediction.git
```


### 2. Change Directory

Navigate into the project directory:

```
cd Yield-Prediction
```


### 3. Install Dependencies

Install the required Python packages using the requirements.txt file:

```
pip install -r requirements.txt
```


### 4. Download Data

To get the necessary datasets, click on the link below to download the "data" folder:

[Link](https://isbhydmoh.sharepoint.com/:f:/s/PlakshaSummerInternship/Eu2_WcPQZQRAi7vaTs5KCXwBSZ_GdIpnkv9lFdRsFMGp-g?e=i9udTn)

### 5. Move the Data Folder

After downloading, move the "data" folder into the cloned repository:

```
mv /path/to/downloaded/data-folder ./Yield-Prediction/data
```
Now you are good to go!

### 6. Short Description on Code Files

The repository contains several Python scripts, each serving a specific purpose in the yield prediction pipeline. Below is a brief description of each:

- **Centroid-SOI Mapping**: This script handles the mapping of centroids to SOI (Survey of India) villages. It aligns the geographical centroids of areas with their corresponding SOI village polygons.

- **Common-Village-and-Tehsil** :  This script identifies and analyzes villages and tehsils that repeat across different year blocks.

- **Cost-of-Cultivation** : This script preprocesses the raw Cost of Cultivation (COC) data, preparing it for analysis.

- **Tehsil-Village Mapping**: A set of scripts in this folder deals with various aspects of mapping tehsils to villages:
  - **One-to-One Mapping**: Maps villages to tehsils in a one-to-one relationship.
  - **Raw COC Data Mapping**: Maps one to one mapped villages to tehsils based on the raw COC dataset.
  - **DTA File Mapping**: Maps one to one mapped villages using the DTA file, aligning them with tehsils for further analysis.

- **Toy-Model-DTA** : This script contains a basic implementation of a Random Forest Regressor model trained on the DTA file. It serves as an initial step in predicting crop yield using the provided data.


### 7. Short Description on Datasets present in the data folder

This is how the data folder looks like!

![Data folder](image.png)

- **All-India-Subdistrict-Shape-File**: This data folder contains the Subdistrict level shape files.
  
- **All-Inida-SOI**: This data folder contains the village shapes downloaded from Survey of India website.

- **Centroid_File**: This data folder contains the centroids of the villages.

- **Clean-Centroid-File** - This data folder contains the clean version of Centroids (non-repeating centroids).

- **CoC-Raw-Data** - This data folder contains the DTA file, COC DTA clean and COC_raw_concat_clean.

- **Final Data** - It contains all the Final Preprocessed data

- **Tehsil Data** - This data folder conatins the One to One mapped Tehsils data and the One to Many mapped Tehsils

- **Village-Localisation-Raw-Data** - This data folder contains the raw Village localisation data downloaded from the COC website.

- **Village-Mapping** - This contains the merged data of One to One mapped villages with the Concatened COC data.

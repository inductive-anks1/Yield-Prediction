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

Centroid-SOI : Centroid to SOI village mapping

Common-Village-and-Tehsil : Repeating Villages and Tehsils over the Year Blocks

Cost-of-Cultivation : Contains preprocessing code of the RAW COC data.

Tehsil-Village-Mapping : Contains different Tehsil to Village mapping codes (One to One mapped Villages, Village mapping on Raw COC dataset, Village mapping on DTA file)

Toy-Model-DTA : Contains code on training a Random Forest Regressor for predicting Yield on the DTA file.


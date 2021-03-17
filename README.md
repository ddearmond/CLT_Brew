# CLT_Brew
A project to cluster Charlotte, NC craft breweries using the k-means clustering algorithm. 

<img src="https://github.com/ddearmond/CLT_Brew/blob/main/images/clusters_map.png">

<img src = "https://github.com/ddearmond/CLT_Brew/blob/main/images/cluster_1.png" >

# Prerequisites
Before you begin, ensure you have met the following requirements:
* You have a Mac machine, platform: osx-64
* You have installed the latest version of miniconda https://docs.conda.io/en/latest/miniconda.html 
* Download or clone this respository to your working directory
* Create a FourSquare Developer account to obtain a Client Id and Client Secret for their Places API https://developer.foursquare.com/docs/places-api/getting-started/ It's Free!
* Create a Mapbox Account to obtain an access token https://account.mapbox.com/auth/signup/ It's Free!

## Create Conda environment
Open a new terminal and navigate to your working directory where the repository is located. 

To replicate the development environment, run the following command in your terminal:
```
conda create --name brewery_cluster --file requirements.txt --yes
```

## Activate Conda environment
```
conda activate brewery_cluster
```

## Launch Jupyter Lab
```
jupyter lab
```

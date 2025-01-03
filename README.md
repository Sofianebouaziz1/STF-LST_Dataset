# STF-LST Dataset : Spatio Temporal Fusion Dataset for Land Surface Temperature Estimation

The <strong>STF-LST Dataset</strong> is a robust foundation for developing and evaluating innovative spatio-temporal fusion techniques, specifically designed to address the challenges of land surface temperature estimation. This dataset includes 51 paired <em>MODIS/Landsat</em> images, each with a resolution of <em>950 x 950</em> pixels. They were collected between March 18, 2013, and October 15, 2024, and they cover the Orleans Métropole in the Centre-Val de Loire region of France.

Below is a video showcasing diverse samples from the STF-LST Dataset (click on the picture and download the video) : 

[![Watch the video](example_sample.png)](STF-LST_video.mp4)

[**Features**](#Features)
| [**Tutorial**](https://github.com/Sofianebouaziz1/FLASH-RL/blob/main/tutorial.ipynb)
| [**Guide of use**](#Guide-of-use)
| [**Paper**]()
| [**ArXiv**](https://arxiv.org/pdf/2412.16631)
| [**How to cite us ?**](#How-to-cite)

## Features

The STF-LST Dataset offers the following features:

* 51 paired MODIS-Landsat images covering a wide range of time periods.
* Various preprocessing techniques were applied, including linear, spatial, and bicubic interpolation methods.
* A fully reproducible codebase that can be adapted for different regions and time periods by simply adjusting the parameters.

## Guide of use
To generate the STF-LST dataset, run the following command in your terminal:  

```bash
python3 run.py
```
The code utilizes the Google Earth Engine platform, so you will need a valid account for authentication before downloading the data.

Please note that this process may take some time.


## Requirements
STF-LST dataset has been generated using the following versions: 
- Python (v3.9.19).
- Torch (v2.4.1+cu121).
- Scipy (v1.13.1).
- Earth Engine (v1.1.2).
- Geemap (v0.34.5).
- Rasterio (v1.3.10).
- NumPy (v1.26.4).
- Pandas (V2.2.2).

## Authors 

STF-LST dataset has been developed by Sofiane Bouaziz, Adel Hafiane, Raphaël Canals and Rachid Nedjai.

## How to cite?
In case you are using STF-LST dataset for your research, please consider citing our work:

```BibTex
@article{bouaziz2024deep,
  title={Deep Learning for Spatio-Temporal Fusion in Land Surface Temperature Estimation: A Comprehensive Survey, Experimental Analysis, and Future Trends},
  author={Bouaziz, Sofiane and Hafiane, Adel and Canals, Raphael and Nedjai, Rachid},
  journal={arXiv preprint arXiv:2412.16631},
  year={2024}
}
```

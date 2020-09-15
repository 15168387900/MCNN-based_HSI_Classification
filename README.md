# MCNN-based_HSI_Classification
## Papers
MCNN-CP: Hyperspectral Image Classification Using Mixed Convolutions and Covariance Pooling (TGARS 2020)[paper](https://ieeexplore.ieee.org/document/9103280/)  
MCNN-PS & Oct-MCNN-PS: Hyperspectral Image Classification Using Hybrid Octave and Sub-Pixel Convolutional Neural Network (TGARS Submitted)

## 1. Environment setup
This code has been tested on on a personal laptop with Intel i7-9750H 2.6-GHz processor, 16-GB RAM, and an NVIDIA GTX1650 graphic card, Python 3.6, tensorflow_gpu-1.14.0, Keras-2.2.4, CUDA 10.0, cuDNN 7.6. Please install related libraries before running this code:

    pip install -r requirements.txt

## 2. Test
Download the datesets:

    [Indian Pines]() code:
    [Kennedy Space Center]() code:
    [University of Pavia]() code:
    [Salinas Scene]() code:
and put them into data directory.

Download the models (loading models):

    [Indian Pines]() code:
    [Kennedy Space Center]() code:
    [University of Pavia]() code:
    [Salinas Scene]() code:
and put them into models directory.

Download the pretrained_models (loading model parameters):

    [Indian Pines]() code:
    [Kennedy Space Center]() code:
    [University of Pavia]() code:
    [Salinas Scene]() code:
and put them into pretrained_models directory.


## 3. Cite
If you use MCNN-CP in your work please cite our paper:

    @ARTICLE{9103280,
      author={J. {Zheng} and Y. {Feng} and C. {Bai} and J. {Zhang}},
      journal={IEEE Transactions on Geoscience and Remote Sensing}, 
      title={Hyperspectral Image Classification Using Mixed Convolutions and Covariance Pooling}, 
      year={2020},
      volume={},
      number={},
      pages={1-13},
    }

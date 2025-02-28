## PDRNet-Net

This is the official repository  of the paper: *Nighttime Image Dehazing via A Physics-Aware Dynamic Neural Model with Progressive Contrastive Regularization*, 2025.



## Usage

The code will be released soon. Please feel free to contact  [Xinjie Xiao:Email](caelum@stu.scau.edu.cn).

We recommend using the [**Anaconda**](https://www.anaconda.com/) package manager to avoid dependency/reproducibility problems. 

#### Installation

1. Clone the repository

```
git clone https://github.com/xxx
```

2. Install Python dependencies

```
conda create -n PDRNet -y python=3.9
conda activate PDRNet 
cd PDRNet 
chmod +x install_requirements.sh
./install_requirements.sh
```

#### Single Image Inference

To get the quality score of a single image, run the following command:

```
python dehaze.py --img_path assets/01.png (To be refined)
```



```
--img_path                  Path to the image to be evaluated
```



 ## Citation

To be done.

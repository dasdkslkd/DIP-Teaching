# Assignment 3 - Play with GANs

### This is 肖健楠's impletation of DIP assignment3

### Resources:
- [DragGAN](https://vcai.mpi-inf.mpg.de/projects/DragGAN/): [Implementaion 1](https://github.com/XingangPan/DragGAN) & [Implementaion 2](https://github.com/OpenGVLab/DragGAN)
- [Facial Landmarks Detection](https://github.com/1adrianb/face-alignment)

---
## Requirements

### GAN for facades

In 1 directory

```setup
python -m pip install -r requirements.txt
```

download facades dataset

```dataset
sh 1.sh
```

To run training

```train
python train.py
```

### DragGAN + face alignment
In 2 directory

To prepare DragGAN

```DragGAN
git clone https://github.com/XingangPan/DragGAN.git
```

Then copy the files and directory under 2 to DragGAN root dir and replace all files

To setup environment

```env
conda env create -f environment.yml
conda activate stylegan3
```

To download pretrained model

```
python scripts/download_model.py
```

To run DragGAN+face_alignment

```run
scripts/gui.sh
```
or
```
scripts/gui.bat
```

## Results

### GAN for facades
#### train results
![image](1/train.png)  

#### val results
![image](1/val.png)

### DragGAN + face alignment


https://github.com/user-attachments/assets/9e5f6030-dde7-4c5b-a97a-b77349880afc




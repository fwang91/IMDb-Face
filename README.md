# The Devil of Face Recognition is in the Noise(ECCV'18)
By Fei Wang, Liren Chen, Cheng Li, Shiyao Huang, Yanjie Chen, Chen Qian, Chen Change Loy

![imdbface](https://github.com/fwang91/IMDb-Face/blob/master/imdb-face.png)

**IMDb-Face** is a new large-scale noise-controlled dataset for face recognition research. The dataset contains about 1.7 million faces, 59k identities, which is manually cleaned from 2.0 million raw images. All images are obtained from the IMDb website. A detailed introduction of IMDb-Face can be found in the paper(https://arxiv.org/abs/1807.11649).

We hope that the **IMDb-Face** dataset could shed lights on the influences of data noise to the face recognition task, and point to potential labelling strategies to mitigate some of the problems. It could serve as a relatively clean data to facilitate future studies of noises in large-scale face recognition.

### Citation
If you find **IMDb-Face** useful in your research, please cite:

	@article{wang2018devil,
  		title={The Devil of Face Recognition is in the Noise},
  		author={Wang, Fei and Chen, Liren and Li, Cheng and Huang, Shiyao and Chen, Yanjie and Qian, Chen and Loy, Chen Change},
  		journal={arXiv preprint arXiv:1807.11649},
  		year={2018}
    }

### Contents
0. [Data Download](#data-download)
0. [Data Statistics](#data-statistics)
0. [Overlap with Face Recognition Benchmarks](#Overlap-with-Face-Recognition-Benchmarks)
0. [Notation](#Notation)
0. [Contact](#Contact)

### Data Download
IMDb-Face.csv

GoogleDrive Download: https://drive.google.com/open?id=134kOnRcJgHZ2eREu8QRi99qj996Ap_ML

BaiduDrive Download: https://pan.baidu.com/s/1eRylM-jMgjYL6cyU6qQd8g

Note: We found that the resolution of some images has changed, so we provide the shape information of each image. If the resolution of the newly downloaded image is not the same as the one we provide, you can rescale the rectangle and get the final rectangle information.

### Data Statistics
Overall

Total number of images: **1.7M**

Total number of identities: **59k**

IMDb-Face dataset statistics 
![dataset](https://github.com/fwang91/IMDb-Face/blob/master/dataset_statistics/dataset_statistics.png)

### Overlap with Face Recognition Benchmarks
We have removed celebrity images of which the identification appear in the LFW dataset, Facescrub (MegaFace evaluation images) and YTF based on names. You can evaluate a face recognition model trained on IMDb-Face on these public benchmarks directly. 

### Notation
(1) IMDb-Face does not own the copyright of the images. IMDb-Face only provides URLs of images. The images in their original resolutions may be subject to copyright, so we cannot make them publicly available on our server. The dataset is released for non-commercial research and/or educational purposes. 

(2) If you are the celebrity included in the IMDb-Face and you do not want to be included in the dataset, please contact us and we will remove the data based on your request.

### Contact
[Fei Wang](cloud9166@gmail.com)

Questions can also be left as issues in the repository. 

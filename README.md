# Fire Video Segmentation Dataset
This Fire Video Segmentation Dataset was used on "Real-Time Fire Detection Based on Color-Motion Feature for Video Surveillance System" by Wahyono, Faisal Dharma Adhinata, Gamma Kosala, Agus Harjoko, Andi Dharmawan, and Kang Hyun Jo, (In Review) 2021. 

This work was supported by the Ministry of Education Culture, Research and Technology, Republic of Indonesia under World Class Research (WCR) Grant 111/E4.1/AK.04.PT/2021 and 4506/UN1/DITLIT/DIT-LIT/PT/2021.  

## Overview
This dataset provides fire segmentation data on 12 common fire classification video. This dataset was obtained by per-frame, manual hand annotation with total of 2,684 annotated frames.

The original raw video data was obtained from A. E. Çetin. “Computer Vision Based Fire Detection Dataset.” 2014. We provide seamless integration of the original data (which not included in this repository) to ours with download_extract_dataset.py script, that download, then extract the original dataset, and modified it to fit our environment settings. For tools, we use VGG Image Annotator version 2.0.11. with *.csv as export.

## Video Annotation Info Table

| Fire   Segmentation Video | Visifire Dataset          | FPS | Total Frame |
|---------------------------|---------------------------|-----|-------------|
| Video01                   | controlled1.avi           | 15  | 260         |
| Video02                   | controlled2.avi           | 15  | 246         |
| Video03                   | controlled3.avi           | 15  | 208         |
| Video04                   | forest1.avi               | 15  | 200         |
| Video05                   | forest2.avi               | 15  | 245         |
| Video06                   | forest3.avi               | 15  | 255         |
| Video07                   | forest4.avi               | 15  | 219         |
| Video08                   | forest5.avi               | 15  | 216         |
| Video09                   | fBackYardFire.avi (@2fps) | 2   | 241         |
| Video10                   | forestfire.avi            | 15  | 218         |
| Video11                   | fire1.avi (@5fps)         | 5   | 236         |
| Video12                   | 40m_PanFire_20060824.avi  | 29.97  | 140         |


## Usage Example
| VisiFire Video (A. E. Çetin, 2014) | Fire Segmentation Video Ground Truth      | Example Implementation (Wahyono et al., 2021) |
| ----------- | ----------- | ----------- |
| ![Alt Text](./GitExample/Video01.gif)      | ![Alt Text](./GitExample/Video01_GT.gif)       | ![Alt Text](./GitExample/Video01_ML.gif)       |
| ![Alt Text](./GitExample/Video02.gif)      | ![Alt Text](./GitExample/Video02_GT.gif)       | ![Alt Text](./GitExample/Video02_ML.gif)       |
| ![Alt Text](./GitExample/Video04.gif)      | ![Alt Text](./GitExample/Video04_GT.gif)       | ![Alt Text](./GitExample/Video04_ML.gif)       |
| ![Alt Text](./GitExample/Video05.gif)      | ![Alt Text](./GitExample/Video05_GT.gif)       | ![Alt Text](./GitExample/Video05_ML.gif)       |

Feel free to contact us, if any problems occur.
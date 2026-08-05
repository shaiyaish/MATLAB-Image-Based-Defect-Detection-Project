<table>
<td><img src="https://gist.githubusercontent.com/robertogl/e0115dc303472a9cfd52bbbc8edb7665/raw/defectDetection.png"  width=500 /></td>
<td><p><h1>Image-Based Defect Detection for Manufacturing Inspection</h1></p>
<p>Build a MATLAB inspection pipeline to detect manufacturing defects  image processing.</p>
</table>

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=shaiyaish/MATLAB-Image-Based-Defect-Detection-Project&file=ImageBasedDefectSystem.mlx)

## Motivation
Modern manufacturing inspection needs two things at once: traceable evidence (why a part failed) and robust decisions under normal variation (lighting, texture, small pose changes). A common industry approach is a hybrid workflow: use classical vision to standardize inputs and capture measurable “evidence,” then use a lightweight AI model to improve classification. This project gives students a practical, deployable pattern: preprocess → evidence → AI decision → test → report.

## Project Objective
The objective behind the project would be to create a simple, AI-integrated MATLAB program that can categorize manufactured metal plates in either "Pass" or "Fail". The intended use of the program would be to make it easy and accessible for workers in the manufacturing industry to be able to use algorithm-based programs that can analyze patterns of defects in products in seconds. A program that can easily classify and recognize patterns would save time and money for many manufacturing companies.
## Steps to Run Code/Models
- Click the "Open MatLab Online" button to launch in MATLAB online.
<p>OR</p>

- Clone repository and run ImageBasedDefectSystem.mlx after installing dependencies.
<p>OR</p>

- Open ImageBasedDefectSystem.pdf to look at a pre-run result of the program.

## Toolboxes and Dependencies
- Deep Learning Toolbox
- Deep Learning Toolbox Model for ResNet-18 Network
- Image Processing Toolbox

## Contributors
| Team Member    | Role                                        |
| :------------- | :------------------------------------------ |
| Shai Yaish     | Modeling and Quality Assurance Lead         |
| Thao Mai       | Documentation/Visualization Lead            |
| Brayan Camacho | Analysis/Validation Lead and Project Manager|

## Credits
[MPDD Dataset:](https://github.com/stepanje/MPDD)
```
@INPROCEEDINGS{9631567,
  author={Jezek, Stepan and Jonak, Martin and Burget, Radim and Dvorak, Pavel and Skotak, Milos},
  booktitle={2021 13th International Congress on Ultra Modern Telecommunications and Control Systems and Workshops (ICUMT)}, 
  title={Deep learning-based defect detection of metal parts: evaluating current methods in complex conditions}, 
  year={2021},
  volume={},
  number={},
  pages={66-71},
  doi={10.1109/ICUMT54235.2021.9631567}
}
```
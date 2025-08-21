# AI-Powered-3D-Trace-Detector-aiPTD

## Semi-Automatic Joint Trace Detection from Textured 3D Rock Mass Models

<img width="1908" height="895" alt="Picture1" src="https://github.com/user-attachments/assets/fa2a0601-fc69-42e7-85cf-e3f93c4910e5" />

A MATLAB-based software tool that combines artificial intelligence with 3D geological modeling to automatically detect and map joint traces in rock masses. This innovative approach addresses the limitations of traditional manual surveying methods by utilizing virtual digital image rendering and deep learning techniques.
<img width="1008" height="540" alt="image" src="https://github.com/user-attachments/assets/a1f3e6bd-9bdf-4b2a-b68e-51f86e6d9b41" />

### 🔬 Key Features

- **Pixel-wise Dense Point Cloud Generation**: Maps high-resolution textures onto 3D mesh models with precise resolution preservation
- **Virtual Digital Image Rendering**: Captures optimal viewpoint images to overcome field limitations (lighting, access, topography)
- **AI-Powered Trace Detection**: Employs DeepLabV3+ neural network for accurate joint trace identification
- **3D Data Structuring**: Comprehensive pipeline including 2D thinning, 3D reprojection, clustering, and segmentation
- **Interactive User Interface**: Semi-automatic workflow allowing manual refinement and validation of detected traces
- **3D Polyline Export**: Generates complete 3D trace networks for further geological analysis

### 🎯 Applications

- **Rock Mass Characterization**: Automated analysis of geological discontinuities
- **Geotechnical Engineering**: Efficient joint mapping for stability assessments
- **Mining Engineering**: Large-scale rock structure analysis
- **Digital Outcrop Modeling**: Enhanced geological surveying and documentation

### 📊 Performance

- **Speed**: ~20x faster than manual trace detection methods
- **Accuracy**: High similarity with manual surveys (validated through rosette diagram analysis)
- **Coverage**: Capable of analyzing inaccessible areas and complex rock formations
- **Scalability**: Handles large, high-resolution 3D models efficiently

### 🛠️ Technical Approach

1. **Texture-to-Point Cloud Mapping**: Novel algorithm for aligning texture pixels with 3D mesh vertices
2. **Virtual Camera System**: Configurable camera parameters for optimal image capture
3. **Machine Learning Integration**: Pre-trained DeepLabV3+ network for semantic segmentation
4. **3D Clustering & Segmentation**: DBSCAN clustering combined with 3D Hough transform
5. **Adaptive Segment Linking**: Intelligent connection of trace segments into continuous polylines

### 📋 Requirements

#### MATLAB Toolboxes
1. MATLAB (Core)
2. Image Processing Toolbox
3. Statistics and Machine Learning Toolbox
4. Fuzzy Logic Toolbox
5. Parallel Computing Toolbox
6. Computer Vision Toolbox

#### System Requirements
- MATLAB R2020b or later recommended
- Minimum 8GB RAM (16GB+ recommended for large models)
- GPU support recommended for AI processing acceleration


### 🔬 Research Background

This software implements the methodology described in:

**"Artificial intelligence-aided semi-automatic joint trace detection from textured three-dimensional models of rock mass"** - *Journal of Rock Mechanics and Geotechnical Engineering* (2025)

The research addresses critical challenges in geological surveying by combining:
- High-resolution 3D modeling techniques
- Advanced image processing algorithms
- State-of-the-art deep learning networks
- Robust 3D spatial analysis methods

https://www.sciencedirect.com/science/article/pii/S1674775524004633?via%3Dihub

### 📧 Contact

For questions, support, or collaboration opportunities:
- **Lead Developer**: Seyedahmad Mehrishal (ahmad@snu.ac.kr) (ahmad.mehri@yahoo.com)
- **Institution**: Seoul National University, Department of Energy Systems Engineering
https://www.linkedin.com/in/seyedahmad-mehrishal/

https://www.youtube.com/@rockbench
### 🙏 Acknowledgments

This work was supported by grants from:
- Human Resources Development program (Grant No. 20204010600250)
- Training Program of CCUS for the Green Growth (Grant No. 20214000000500)
- Korea Institute of Energy Technology Evaluation and Planning (KETEP)
- Ministry of Trade, Industry, and Energy of the Korean Government (MOTIE)

### 📊 Citation

If you use this software in your research, please cite:

```bibtex
@article{mehrishal2025ai,
  title={Artificial intelligence-aided semi-automatic joint trace detection from textured three-dimensional models of rock mass},
  author={Mehrishal, Seyedahmad and Kim, Jineon and Shao, Yulong and Song, Jae Joon},
  journal={Journal of Rock Mechanics and Geotechnical Engineering},
  volume={17},
  pages={1973--1985},
  year={2025},
  publisher={Elsevier}
}
```

---

**Keywords**: Rock Mechanics, Joint Mapping, AI/ML, 3D Modeling, Image Processing, Geological Engineering, Photogrammetry, Digital Outcrop Analysis

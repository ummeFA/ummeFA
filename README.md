![banner](banner-gh.png)

### Hi there 👋, I'm Umme Fatema

I'm a Computer Science & Engineering graduate working with 3D LiDAR and geospatial data in Japan, and independently building a research track in medical imaging and computer vision. Both center on the same underlying problem: extracting meaningful signal from noisy, paired data, whether disease patterns in brain MRI or displacement patterns in disaster-affected terrain. Published in Alzheimer's disease classification (IEEE ICIEV/icIVPR 2020), and continuing to build independent projects in medical imaging deep learning, SAR sea ice classification, and geospatial/LiDAR change detection.

### Technical Skills

**Programming & Development**
- Python, Java, JavaScript
- HTML, CSS

**Machine Learning & AI**
- Machine Learning, Deep Learning
- TensorFlow, Keras
- scikit-learn, XGBoost
- CNN, Transfer Learning, U-Net
- Model Evaluation (ROC-AUC, Precision, Recall)

**Data & Domain Skills**
- Data Preprocessing, Feature Engineering
- Image Classification, Segmentation
- LiDAR and Point Cloud Processing (laspy, PDAL, rasterio)
- SAR Imagery
- QGIS, Geospatial Data Analysis

---

### Current Focus
- Longitudinal and 3D change detection in imaging data
- Deep learning for medical image analysis
- Bringing ML methods to geospatial, LiDAR, and SAR data

## Featured Projects

- **Sea Ice Type Classification from SAR**  
  Six-class sea ice type classification from Sentinel-1 C-band SAR (347 scenes, Canadian Ice Service charts, scene-level train/validation split to avoid leakage). Compared an SVM on HH/HV backscatter + GLCM texture against a U-Net: texture raised SVM accuracy from 0.48 to 0.69, and the U-Net reached 0.78 accuracy, the best on common classes, while the SVM did better on rare thin and young ice (both at macro F1 0.42). `Python` · `scikit-learn` · `TensorFlow` · `Keras`  
  🔗 [Repository](https://github.com/ummeFA/sar-ice-tracking)

- **Brain Tumor MRI Classification**  
  Two-stage transfer learning (EfficientNetB0) for 4-class brain tumor classification (glioma / meningioma / pituitary / no tumor). Compared frozen-base vs. fine-tuned performance; fine-tuning improved glioma recall (68.5% → 70.0%) at the cost of meningioma recall, revealing a class-specific trade-off consistent with known glioma–meningioma imaging overlap in the radiology literature. `Python` · `TensorFlow` · `Keras` · `EfficientNetB0`  
  🔗 [Repository](https://github.com/ummeFA/brain-tumor-mri-efficientnet)

- **Kumamoto Earthquake Surface Change**  
  Bitemporal airborne LiDAR analysis of the Futagawa fault rupture. Compared pre- and post-earthquake scans on a shared 20 m grid to compute a DEM of difference, recovering coherent fault-trending displacement. Diagnosed and fixed a spurious offset by switching from interpolation to binning (σ ~3.0 m → ~1.48 m). `Python` · `laspy` · `rasterio` · `QGIS` · OpenTopography data  
  🔗 [Repository](https://github.com/ummeFA/kumamoto-earthquake-surface-change)

- **Mt. Fuji Summit LiDAR Terrain Analysis**  
  0.5 m DTM analysis of the Mt. Fuji summit area from VIRTUAL SHIZUOKA ground LiDAR: hillshade, sky-view factor, slope statistics, and K-means landform clustering. `Python` · `QGIS` · `scikit-learn`  
  🔗 [Repository](https://github.com/ummeFA/mt-fuji-lidar-dtm-analysis)

- **Alzheimer's Disease MRI Classification**  
  CNN-based classification across the Alzheimer's continuum (AD / MCI / CN) from ADNI structural MRI. Compared three transfer learning architectures (VGG19, InceptionV3, ResNet50); VGG19 performed best at ~90% accuracy. `Python` · `TensorFlow` · `Keras`  
  🔗 [Published at ICIEV/icIVPR 2020, IEEE Xplore](https://ieeexplore.ieee.org/document/9306649)

- **Satellite Image Classification**  
  4-class land-cover classification (cloudy / desert / green area / water). Compared a custom CNN baseline (94.49%) against MobileNetV2 transfer learning, which reached 99.64% validation accuracy. `Python` · `TensorFlow` · `Keras`  
  🔗 [Repository](https://github.com/ummeFA/satellite-image-identifier)

**Links:**

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/ummeFA)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/umme-fatema-052876198)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/kaggle.svg' alt='kaggle' height='40'>](https://www.kaggle.com/ummefatema1)

⚡ Fun fact: I love solving puzzles, especially the Rubik's Cube, enjoy traveling and exploring new places (currently discovering Japan region by region), and love watching movies in my free time.

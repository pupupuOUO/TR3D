# TR3D

<h1 align="center">
    <strong>3D Digital Modeling of Power Transformers Based on Morphology-aware Registration Network</strong>
</h1>
<p align="center">
    <a href="https://github.com/pupupuOUO">Qiubing Shen</a>, <a >Yige Zhao</a>, <a >Chen Yang</a>, <a >Yuhao Zhang</a>, <a >Hui Chen</a>
</p>
<p align="center">
    <img src="assets/teaser.png" alt="teaser" width="100%">
</p>

---

# Usage

## Download the dataset
You can download the dataset from <a href="https://pan.baidu.com/s/1oBqaLTGQITdzhm7D0z-Gkw?pwd=wd98" style="text-decoration:underline;">here</a>.

### Dataset Description
- **Brief introduction to the TR3D dataset**  
  TR3D is a PT 3D dataset comprising 420 models of approximately 50 types of PT used in power systems. It is designed to provide comprehensive morphological
  knowledge for deep learning models or serve as a test benchmark for power equipment. TR3D includes both point cloud data and mesh data, with the point cloud
  data obtained using the SPS sampling method mentioned in the paper.

- **Directory structure explanation**  
```
TR3D_Data_Root
├── H5File
│ ├── ply_data_test0.h5 - Point cloud data
├── Mesh
│ ├── <PT_*>- Mesh data

---

# TODO

- More task annotations

---

# License

The TR3D dataset is made available under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

---

# Reference

If you find our dataset useful in your research, please cite:
```bibtex
@article{TR3D,
    author = {Qiubing Shen, Yige Zhao, Chen Yang, Yuhao Zhang, Hui Chen},
    title = {3D Digital Modeling of Power Transformers Based on Morphology-aware Registration Network},
    booktitle = {},
    year = {2025}
}


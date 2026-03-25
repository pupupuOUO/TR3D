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

# Updates
- [03/2026] 🎉 **TR3D is officially published!** See the paper [here](https://ieeexplore.ieee.org/abstract/document/11442696/keywords#keywords)
- [12/2025] TR3D dataset released!

---

# Usage

## Download the dataset
You can download the dataset from [here](https://drive.google.com/drive/folders/1JVc1nNX4xGQvYu3LEnberPirgwEemyOs?usp=drive_link).

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
```

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
  author={Shen, Qiubing and Zhao, Yige and Yang, Chen and Zhang, Yuhao and Chen, Hui},
  journal={IEEE Transactions on Industry Applications}, 
  title={3D Digital Modeling of Power Transformers Based on Morphology-Aware Registration Network}, 
  year={2026},
  volume={},
  number={},
  pages={1-13},
  doi={10.1109/TIA.2026.3675169}
}


## Setup
We provide the code as IPython notebooks. For ease of use, we recommend using [Google Colab](https://colab.research.google.com) to run all of the notebooks except 3d_shape_occupancy.ipynb. The notebooks are designed to install libraries that the Colab environment is missing. To run in Colab, click the badge at the top of the notebook or upload the file to colab.research.google.com and enable the GPU in the runtime settings.

Install the following libraries if you would prefer to use your own local environment:
```
JAX (GPU)
jaxlib
neural-tangents
tqdm
Livelossplot
imageio
PIL
cv2
numpy
matplotlib
phantominator
gdown
```

To run 3d_shape_occupancy.ipynb the additional libraries are necessary:
```
Embree
pyembree
trimesh
```

## Included Files


| File                        | Figures   | Tables |
| --------------------------- | --------- | ------ |
| `1d_regression.ipynb`       | 2,3,12    |        |
| `1d_scatter_plots.ipynb`    | 4,13      |        |
| `1d_ntk_opt.ipynb`          | 5         |        |
| `2d_image_regression.ipynb` | 1,6,10,15 | 1,3    |
| `2d_CT.ipynb`               | 17        | 1,5    |
| `2d_MRI.ipynb`              | 1,18      | 1,6    |
| `3d_shape_occupancy.ipynb`  | 1,16      | 1,4    |
| `3d_simple_nerf.ipynb`      | 1,19      | 1,7    |
| `Kernel_spreading.ipynb`    | 7         |        |
| `toy_stationary_ex.ipynb`   | 14        |        |
| `axis_aligned_ex.ipynb`     | 11        |        |

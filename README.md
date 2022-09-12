# Felzenszwalb-supervoxel-segmentation
Extension of the [Felzenszwalb scikit-image superpixel algorithm](https://scikit-image.org/docs/stable/api/skimage.segmentation.html#skimage.segmentation.felzenszwalb) to 3D supervoxels.


Compile `felzenszwalb_3d_cy.pyx` with Cython by running: `python setup.py build_ext --inplace` 



This implementation was developed as part of the [ADNet project](https://github.com/sha168/ADNet):
```
@article{hansen2022anomaly,
  title={Anomaly Detection-Inspired Few-Shot Medical Image Segmentation Through Self-Supervision With Supervoxels},
  author={Hansen, Stine and Gautam, Srishti and Jenssen, Robert and Kampffmeyer, Michael},
  journal={Medical Image Analysis},
  pages={102385},
  year={2022},
  publisher={Elsevier}
}
```
Please consider citing it if you find our implementation useful.

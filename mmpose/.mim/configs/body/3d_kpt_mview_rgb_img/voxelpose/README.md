# VoxelPose: Towards Multi-Camera 3D Human Pose Estimation in Wild Environment

<!-- [ALGORITHM] -->

<details>
<summary align="right"><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460188.pdf">VoxelPose (ECCV'2020)</a></summary>

```bibtex
@inproceedings{tumultipose,
  title={VoxelPose: Towards Multi-Camera 3D Human Pose Estimation in Wild Environment},
  author={Tu, Hanyue and Wang, Chunyu and Zeng, Wenjun},
  booktitle={ECCV},
  year={2020}
}
```

</details>

VoxelPose proposes to break down the task of 3d human pose estimation into 2 stages: (1) Human center detection by Cuboid Proposal Network
(2) Human pose regression by Pose Regression Network.

The networks in the two stages are all based on 3D convolution. And the input feature volumes are generated by projecting each voxel to
multi-view images and sampling at the projected location on the 2D heatmaps.

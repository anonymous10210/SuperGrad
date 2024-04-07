# A Super-pixel-based Approach to the Stable Interpretation of Neural Networks
<p align="center">
<img src="assets/ssim_region_cifar.png" width="800">
</p>
<p align="center">
 <em width="800"> Figure 1. The SSIM of saliency map between two models trained with
disjoint training datasets from CIFAR10 (with error bar). Super-pixel-based methods are started with "S-" for short.</em>
</p>

<p align="center">
<img src="assets/mege.png" width="400">
</p>
<p align="center">
 <em> Table 1.  Comparison of MeGe between pixel-based and super-pixel-based methods. L2-norm is used as the distance measure.</em>
</p>

<p align="center">
<img src="assets/vis_cub.jpg" width="1000">
</p>
<p align="center">
 <em width="800"> Figure 2.  Qualitative comparison on CUB dataset between pixel-based and super-pixel-based interpretation maps for
different methods.  Birds segmentations are used to mask out the background during the training and inference to manually remove the noise in saliency maps. Super-pixel-based methods can be more focused on specific body parts of the birds.</em>
</p>

<p align="center">
<img src="assets/vis_architecture.jpg" width="1000">
</p>
<p align="center">
 <em width="800"> Figure 3. Qualitative comparison on ImageNet dataset between pixel-based and super-pixel-based interpretation maps for
different network architectures with simple gradient. Super-pixel-based methods can achieve better visual quality and inter-architrcture consistency.</em>
</p>

<p align="center">
<img src="assets/superpixel.png" width="400">
</p>
<p align="center">
 <em width="800"> Figure 4. Illustration of super-pixel-based partitions using different algorithms.</em>
</p>


<p align="center">
<img src="assets/cyclegan.png" width="1000">
</p>
<p align="center">
 <em> Figure 5. Visualization of saliency maps for explaning the discriminator in CycleGAN. We conducted apple2orange and horse2zebra image translation tasks.</em>
</p>


<p align="center">
<img src="assets/algo.png" width="1000">
</p>
<p align="center">
 <em> Table 2. Comparison of stability and fidelity tradeoff among different super-pixel generation algorithms.</em>
</p>


<p align="center">
<img src="assets/cost.png" width="400">
</p>
<p align="center">
 <em> Table 3. Computation time of different methods for processing one 224x224 images.</em>
</p>



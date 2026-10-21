# Radiance Cascades vs. Unity's Standard Global Illumination Methods

Experimental materials for the DIGRA conference paper:

**"Comparative Evaluation of Real-Time Global Illumination Methods in Unity URP"**

This repository holds the raw performance data, generated figures, and test project used to compare Radiance Cascades against Unity's built-in real-time GI approaches in the Universal Render Pipeline (URP).

## Contents

| Item | Description |
|------|-------------|
| Raw datasets | FPS and frame time measurements for each GI method and scene |
| Figures | Charts and plots used in the paper |
| Render videos | Recorded captures for visual comparison ([YouTube playlist](https://www.youtube.com/watch?v=daDjPJyB86o&list=PLaHv1eGKS6CyZF2IG05RV7KAHvvU5-xIQ)) |

> Update the paths in the table above to match the actual folder names in this repo.

## Methods Compared

- **Radiance Cascades**: the screen-space/probe-based real-time GI technique under evaluation
- **Unity standard GI methods** in URP (list the exact ones tested, e.g. baked lightmaps, Adaptive Probe Volumes, light probes, screen-space GI)

## Experimental Setup

**Software**

- Unity 6000.2.12f1
- Render pipeline: Universal Render Pipeline (URP)

**Hardware**

- GPU: NVIDIA RTX 4060 Laptop GPU
- CPU: Intel Core i7-13620H

**Measurement protocol** *(fill in)*

- Resolution and quality settings:
- Scenes tested:
- Capture duration / number of runs per method:
- Metrics: average FPS, frame time (ms), and any percentile or 1% low values

## Reproducing the Results

1. Install Unity 6000.2.12f1 via Unity Hub.
2. Clone this repository and check out the relevant branch:
   ```bash
   git clone https://github.com/gwynplainee/Radiance-Cascades-Compared-to-Unity-s-Standard-Global-Illumination-Methods.git
   git checkout practice_6
   ```
3. Open the project in Unity and load the test scene.
4. Select the GI method to test, run the scene, and record FPS and frame time.
5. Compare your output against the datasets in this repo.

Results will vary with hardware, drivers, and power settings. The reported numbers were collected on a laptop GPU, so thermal and power limits may affect them.

## Citation

If you use this material, please cite the paper:

```bibtex
@inproceedings{TODO,
  title     = {Comparative Evaluation of Real-Time Global Illumination Methods in Unity URP},
  author    = {TODO},
  booktitle = {DiGRA},
  year      = {TODO}
}
```

## License

Released under the [MIT License](LICENSE).

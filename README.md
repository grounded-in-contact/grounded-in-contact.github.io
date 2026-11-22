# Grounded in Contact

Project page for **Grounded in Contact: Reducing Floating and Interpenetration Artifacts with Multimodal Skill-Effect Models**.

**Website:** https://grounded-in-contact.github.io

Siyeon Kim<sup>1</sup>, Mohanraj Devendran Shanthi<sup>1,†</sup>, Joseph C. Liechty<sup>1,†</sup>, Tucker Hermans<sup>1,2</sup>

<sup>1</sup>University of Utah, <sup>2</sup>NVIDIA Research, <sup>†</sup>Equal contribution

## Contents

| Path | Description |
|---|---|
| `index.html` | The project page (single file, no build step) |
| `fig-net-final.png` | Network overview figure |
| `media/pred_*.mp4` | Simulation pose prediction examples (push, push height, pick, pick no-op, place) |
| `media/quality_crop.png` | Prediction quality charts (Brier score, physical plausibility) |
| `media/multistep_crop.png` | Multi-step planning results in simulation |
| `media/real_multistep.mp4` | Real-robot push, pick, and place run |

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Citation

The arXiv link and BibTeX will be added once the preprint is announced.

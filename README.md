# Domain-specific_finetunning

## Data and Model Access

The images, ground-truth annotations, and trained models are available **upon request for research purposes**.

For access, please contact:

**Victor Augusto Benedicto dos Santos**
[victorbenedicto@ufpr.br](mailto:victorbenedicto@ufpr.br)

or 

**Thiago Zilli**
[thiagozilli@ufpr.br](mailto:thiagozilli@ufpr.br)

## Repository Contents

### `Phase_1_Training_Hyperparameter_Exploration.ipynb`

Training hyperparameter exploration, including epochs, learning rate, weight decay, and their refined combination.

### `Phase2_Generalization_data_augmentation.ipynb`

5-fold cross-validation comparing models trained with and without data augmentation.

### `Phase3_inference_hyperparameter_optimization.ipynb`

Inference-parameter optimization and evaluation of the trained models on their respective test folds.

### `Phase4_morphology_measurements.ipynb`

Comparison of ground-truth and predicted segmentations based on neuron count, area, and equivalent diameter.

### `results_analysis_best_models.ipynb`

Analysis and visualization of the main segmentation results and figures presented in the manuscript.

## Workflow

```text
Phase 1 → Phase 2 → Phase 3 → Phase 4 → Results Analysis
```

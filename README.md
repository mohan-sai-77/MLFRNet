# MLFRNet: Multi-scale Local Feature Refinement Network

Official implementation and experimental resources for:

**MLFRNet: Multi-scale Local Feature Refinement Network using Multi-scale
Depthwise Convolution for HER2 Score Classification**

## Repository Status

This repository is provided to support reproducibility of the reported
experiments.

The complete training and evaluation implementation, experimental
configurations, checkpoint-selection procedures, and supporting scripts
will be made publicly available upon publication of the paper.

## Experimental Configuration

The reported experiments use the following configurations:

| Experiment | Input Resolution | Seed | Epochs | Purpose |
|---|---:|---:|---:|---|
| Primary experiment | 224 × 224 | 42 | 15 | Main evaluation |
| Resolution sensitivity | 384 × 384 | 42 | 15 | Resolution sensitivity |
| Resolution sensitivity | 512 × 512 | 42 | 15 | Resolution sensitivity |

The checkpoints used for the different experiments are documented
separately and should not be assumed to correspond to the same training
epoch.

## Reproducibility

The complete release will include:

- Training code
- Evaluation code
- Configuration files
- Dataset split/partition information
- Random-seed settings
- Checkpoint-selection logic
- Metric calculation scripts
- Scripts for reproducing reported tables and figures
- Prediction outputs required for verification
- Computational profiling scripts
- Package and environment information

## Training and Evaluation

The released implementation will document:

- Data preprocessing
- Training/validation partitioning
- Input resolution
- Batch size
- Number of epochs
- Optimizer and learning-rate schedule
- Loss formulation
- Validation-based checkpoint selection
- Test-set evaluation procedure

## Checkpoints

The repository will document the checkpoints associated with each reported
experiment, including:

- input resolution
- random seed
- training epoch
- validation performance
- checkpoint-selection criterion

The 224 × 224, 384 × 384, and 512 × 512 experiments should therefore be
reproduced using their respective documented checkpoints.

## Availability

The complete reproducible code and associated experimental materials will
be released publicly after publication of the paper.

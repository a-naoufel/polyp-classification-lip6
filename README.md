# Polyp Classification — LIP6 Internship

Machine learning and deep learning for the classification of colorectal
polyps from coloscopy images, in the context of colorectal cancer
diagnosis.

**Internship — Master 1** · LIP6, Sorbonne Université
Supervisor: [name]
Period: June–August 2026

## Objective

Study and develop approaches to improve the characterization and
classification of colorectal polyps from endoscopic images, focusing on:
- Convolutional Neural Networks (CNNs)
- Transformer-based architectures
- Comparison of performance, interpretability, and robustness

## Project structure

\`\`\`
src/         Reusable source code (data, models, training, utils)
notebooks/   Exploratory analysis
configs/     Experiment configuration files
scripts/     CLI entry points
results/     Final figures and tables
docs/        Notes and report drafts
\`\`\`

## Setup

\`\`\`bash
# Clone the repo
git clone <repo-url>
cd polyp-classification-lip6

# Create a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
\`\`\`

## Usage

\`\`\`bash
# Run a training experiment from a config file
python scripts/run_training.py --config configs/resnet50_baseline.yaml
\`\`\`

## Data

See \`data/README.md\`. Datasets are **not** included in this repository
for size and privacy reasons. [Describe how to obtain them.]

## Experiment tracking

Experiments are logged with [Weights & Biases / TensorBoard].
Each experiment corresponds to one config file in \`configs/\`.

## Status

🚧 Work in progress.

## Author

[Your name] — [your email]

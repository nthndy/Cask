
# CASK: Cellular Analysis of Spatiotemporal K-functions

**CASK** (*Cellular Analysis of Spatiotemporal K-functions*) is a repository accompanying the publication **"Spatial and temporal signatures of cell competition revealed by K-function analysis"**. This repository provides Jupyter notebooks for spatiotemporal K-function clustering analysis and single-cell labeling, offering distilled quantitative methods to study the spatiotemporal dynamics of cellular competition.

![Uploading pasted-movie.png…]()

## Key Features

- **K-function Analysis**: Quantitatively evaluates the spatial and temporal clustering of wild-type cell mitoses relative to mutant cell elimination events.
- **Single-Cell Labeling**: Includes notebooks for labeling and tracking individual cells to analyze heterogeneity in cellular behaviors.
- **Publication-focused**: Reproduces key findings from the study.
- **Simple Setup**: No installation required; explore the included Jupyter notebooks directly.

## Included Notebooks

1. **Space-time_K-Function_analysis.ipynb**: Implements the spatiotemporal K-function clustering analysis.
2. **Single-Cell Labeling Notebooks**:
   - `align.ipynb`: Aligns imaging data for accurate cell tracking.
   - `btrack_tracking.ipynb`: Utilizes Bayesian tracking for single-cell movement analysis.
   - `cellx_classify.ipynb`: Classifies cell types based on imaging data.
   - `napari_viewer.ipynb`: Visualizes cell data using the Napari viewer.
   - `stardist_segmentation.ipynb`: Segments cell images using the StarDist algorithm.

*Note:* This repository **does not** include segmentation or tracking tools. Those were performed using bespoke pipelines described in the publication.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/nthndy/Cask.git
   cd Cask
3. Navigate to the provided notebooks and explore the analysis.

## Citation
If you use this repository, please cite the publication:  
**Spatial and temporal signatures of cell competition revealed by K-function analysis**  
Nathan J. Day, Jasmine Michalowska, et al. (2024).

## License
This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
This work was conducted at **University College London (UCL)**. Special thanks to the Lowe and Charras labs for their contributions and support.

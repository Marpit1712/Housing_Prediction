# Housing Price Prediction

An end-to-end machine learning workflow built with Scikit-Learn for predicting house prices. The project walks through the full pipeline of a regression task — exploring the data, creating a proper test set, handling categorical attributes, scaling features, and assembling everything into reusable Scikit-Learn pipelines.

Each stage lives in its own Jupyter notebook so the process is easy to follow step by step.

## Project Structure

| File | Description |
|------|-------------|
| `Visualizing the data.ipynb` | Exploratory data analysis and visualizations of the housing dataset |
| `creating a Test Set.ipynb` | Splitting the data into training and test sets (including stratified sampling) |
| `Handling Categorical Attributes.ipynb` | Encoding categorical features for use in ML models |
| `Feature_Scalling .ipynb` | Scaling and normalizing numerical features |
| `Sklearn_pipelines.ipynb` | Building Scikit-Learn pipelines to chain preprocessing and modeling steps |
| `Further Processing.ipynb` | Additional preprocessing and refinement of the pipeline/model |
| `housing.csv` | The housing dataset used throughout the notebooks |

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Marpit1712/Housing_Prediction.git
   cd Housing_Prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   ```

3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

### Usage

Run the notebooks in order to follow the full workflow from raw data to a trained model:

1. `Visualizing the data.ipynb`
2. `creating a Test Set.ipynb`
3. `Handling Categorical Attributes.ipynb`
4. `Feature_Scalling .ipynb`
5. `Sklearn_pipelines.ipynb`
6. `Further Processing.ipynb`

Each notebook builds on the concepts and outputs of the previous one, so it's best to run them sequentially rather than in isolation.

## Dataset

The project uses `housing.csv`, a dataset of housing-related features (such as location, rooms, and population statistics) used to predict median house values.

## Tech Stack

- **Python** — core language
- **Pandas / NumPy** — data manipulation
- **Matplotlib** — data visualization
- **Scikit-Learn** — preprocessing, pipelines, and modeling

## License

No license has been specified for this repository. Consider adding one (e.g., MIT) if you plan to share or accept contributions.

## Contributing

This is currently a personal learning project. Feel free to fork it and adapt it for your own experimentation.

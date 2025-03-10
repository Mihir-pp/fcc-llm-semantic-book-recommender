# Semantic Book Recommender
The project includes multiple components, such as text data cleaning, vector search, text classification, sentiment analysis, and a Gradio-based web application.


## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution)
- Git (optional, for cloning the repository)

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-repo/semantic-book-recommender.git
cd semantic-book-recommender
```

### Step 2: Create and Activate the Conda Environment

This project provides an `environment.yml` file to set up dependencies.

```bash
conda env create -f environment.yml
conda activate semantic-book-recommender
```

### Step 3: Download Necessary Data
Some components may require additional datasets or models to be downloaded. Follow the instructions within each Jupyter notebook to ensure you have all necessary files.

### Step 4: Running Jupyter Notebooks
Launch Jupyter Notebook to explore and run each notebook:
```bash
jupyter notebook
```
Open the desired `.ipynb` file in your browser and execute the cells step by step.

This will start a local server, and a URL will be provided in the terminal to access the application.

## Usage
- **Enter a book-related query** (e.g., "a book about a detective solving a mystery").
- **Filter results by fiction/non-fiction** using the classification model.
- **Sort results by sentiment/tone** (e.g., suspenseful, joyful, sad).
- **Explore similar books** based on vector search.

## Contributing
Made with Free code camp 

## License
This project is open-source and available under the MIT License.



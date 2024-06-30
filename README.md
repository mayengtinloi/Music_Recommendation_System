# Music Recommendation System 

## Description
The Music Recommendation System predicts whether a user would enjoy a song. It builds a list of suggested tracks after reviewing the user's previous song history and the music's attributes. The system is based on the Spotify dataset, which includes variables such as acousticness, danceability, energy, instrumentalness, key, liveness, loudness, and more.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Contributing](#contributing)

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/mayengtinloi/Music_Recommendation_System.git
    cd Music_Recommendation_System 
    ```

2. **Navigate to the `SourceCode` folder:**
    ```bash
    cd SourceCode
    ```

3. **Install Jupyter Notebook (if not installed):**
    ```bash
    pip install jupyter
    ```

4. **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

5. **Open the notebook:**
    - Navigate to the `TestingAnalysis.ipynb` file in the `SourceCode` folder and open it in the Jupyter interface.

## Usage

Here’s a brief guide on how to use this project:

1. **Data Analysis:**
    - The project is based on the `SpotifyAudioFeaturesNov2018.csv` file, which contains audio features data for Spotify tracks.
    - Open the `SourceCode/TestingAnalysis.ipynb` notebook in Jupyter.

2. **Running the Notebook:**
    - Ensure the CSV file is in the same directory as the notebook or update the path in the notebook to point to the correct file location.
    - Execute the cells step by step to analyze the data. The notebook includes data loading, processing, and visualization steps.

3. **Exploring the Data:**
    - The notebook will guide you through various analyses such as summary statistics, visualizations, and possibly some machine learning models.
    - Modify the notebook to suit your analysis needs or explore additional data insights.

4. **Running the Python Script:**
    - If your project includes a Python script, ensure it's executable by setting the correct permissions:
    ```bash
    chmod +x SourceCode/script_name.py
    ```
    - Run the script with:
    ```bash
    python SourceCode/script_name.py
    ```
    - This will perform tasks such as data preprocessing, model training, and recommendations based on your code.

5. **Customizing the Recommendations:**
    - Update parameters or configurations in the Python script or notebook to customize recommendations for specific users or datasets.
    - Modify functions or classes as needed to extend the system's capabilities.

## Contributing

We welcome contributions! Here’s how you can contribute:

1. **Fork the repository:**
    - Click the "Fork" button at the top right of the repository page.

2. **Clone your fork:**
    ```bash
    git clone https://github.com/yourusername/Music_Recommendation_System.git
    cd Music_Recommendation_System 
    ```

3. **Create a new branch:**
    ```bash
    git checkout -b feature-branch-name
    ```

4. **Make your changes:**
    - Add new features or fix bugs in your branch.

5. **Commit and push your changes:**
    ```bash
    git add .
    git commit -m "Description of changes"
    git push origin feature-branch-name
    ```

6. **Create a pull request:**
    - Go to the original repository on GitHub and click on the "Pull request" button.
    - Provide a detailed description of your changes and submit the pull request.

### Guidelines

- Follow the coding style used in the project.
- Write clear and concise commit messages.
- Ensure your changes don't break existing functionality.
- Update the documentation as necessary.

Thank you for your interest in contributing!

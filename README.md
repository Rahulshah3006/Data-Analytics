# Data-Analytics

- There are two projects in this particular file of data analytics and a small description is given below 

   - Project-1
     - Given an ".txt" format data of links betweeen the nodes in which the links covers scientific collaborations between authors papers submitted to General Relativity and Quantum Cosmology category.
     - Lets say, if an author i co-authored a paper with author j, the graph contains an undirected edge from i to j. If the paper is co-authored by k authors this generates a completely connected (sub)graph on k nodes.

   - project-2
      - Given and json file and csv which describes the instruments and its properties in json file and ratings of particular instruments by the user rspectively.
      - So, hereby under this project I have created collabrative as well as content based recommendation model which recommends based on its ratings  by user by creatig User-User matrix and by using categories of Instruments .

### NOTES:

- The dataset for first project is given in respective folder
- The dataset for second project is given in Kaggle so to download you can run it either in google colab or any env you using bwlow code 

## Downloading Dataset from Kaggle

To download the `orchestra-data-analytics` dataset from Kaggle and extract it, follow these steps:

1. **Ensure you have the Kaggle API installed**:
    ```bash
    pip install kaggle
    ```

2. **Download and Extract the Dataset**:
    - Use the following commands to download and unzip the dataset:
    ```bash
    !kaggle datasets download -d romeo62/orchestra-data-analytics
    !unzip orchestra-data-analytics.zip -d /content/
    ```

### NOTE:
- Replace `/content/` with the desired directory path where you want to extract the dataset files.

By following these steps, you'll be able to download and extract the `orchestra-data-analytics` dataset for use in your project.






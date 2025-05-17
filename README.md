# Restaurant Rating Prediction Using Zomato Dataset

# Research Question:
The central question of our research is,  
**"Can we predict restaurant ratings accurately based on structured metadata such as location, cost, cuisines, and service features?"**

This inquiry is significant because understanding the factors influencing restaurant ratings can help restaurant owners optimize their services and allow customers to make informed dining choices.  
Unlike traditional review analysis relying on textual reviews, this project focuses solely on structured data fields, making it a faster and scalable solution for platforms like Zomato.

# Dataset Description:
The dataset used is from Kaggle, titled "**Zomato Bengaluru Dataset**."  
It contains information about over **50,000** restaurants located in Bengaluru, India, including attributes like:
- Restaurant name
- Location
- Cost for two
- Online ordering availability
- Table booking option
- Cuisines
- Ratings

After cleaning and preprocessing, around 21,000 usable rows were retained.  
This dataset is suitable because it combines various structured features directly impacting customer satisfaction and restaurant quality.

Dataset Link: [Zomato Bengaluru Dataset on Kaggle](https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset/data)

# Steps to run code

1. **Download the dataset** from the above link and place it inside the cloned repository where the `.ipynb` notebook is located.

2. **Create a new Conda environment**:
   ```bash
   conda env create -f environment.yml
   ```
3. **Activate the environment**
```bash
  conda activate zomato_env
   ```
  4. **Run Jupyter Notebook**
```bash
 jupyter notebook
   ```

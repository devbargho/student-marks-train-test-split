# Student Marks: Train/Test Split
 
A small notebook showing how to split a dataset into training and testing sets, first manually with NumPy and then with scikit-learn's `train_test_split`.
 
## Dataset
 
10 samples with 3 columns:
 
| Column | Role | Description |
|---|---|---|
| Study hours | Feature | Hours studied per day |
| Play time | Feature | Hours spent playing per day |
| Marks | Target | Marks obtained |
 
## What it covers
 
- Shuffling the data with `np.random.choice`
- Separating features (`X`) and target (`y`)
- Manual 80/20 split using slicing
- The same split using `train_test_split`
With 10 samples and `test_size=0.2`, you get 8 training rows and 2 testing rows.
 
## Requirements
 
```bash
pip install numpy scikit-learn
```
 
Open `Splitting_of_Train_Test_Data_From_Dataset.ipynb` in Jupyter or Google Colab to run it.

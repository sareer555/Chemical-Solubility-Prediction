# Chemical-Solubility-Prediction
Build a machine learning model to predict the solubility of chemical compounds (logS) based on molecular properties like molecular weight, logP (lipophilicity), and structural descriptors.
2. Tools & Libraries
Python: Pandas, NumPy, Scikit-learn, RDKit, Matplotlib/Seaborn

SQL: For querying additional compound data (optional)

Dataset: Delaney Solubility Dataset (1,143 compounds with measured solubility).


## Adding more features to our solubility prediction project using RDKit and Python.
## Step 1: Calculate Additional Molecular Descriptors
RDKit provides a wide range of molecular descriptors. Here are some key ones to add:

Polar Surface Area (TPSA): Measures polarity, which affects solubility.

Number of Hydrogen Bond Donors/Acceptors: Influences water solubility.

Rotatable Bonds: Indicates molecular flexibility.

Aromatic Rings: Affects molecular stability and solubility.

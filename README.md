# Species identification from DNA sequences using Random Forest

### Description :gear:
+ Certain fragments of DNA (for example, mitochondrial, nuclear, and plastid sequences) have been
defined as barcodes used as markers to identify and classify
species. :bee:
+ These markers can be understood as sequences of four letters:
1.   Adenine (A)
2.    Cytosine (C)
3.    Guanine (G)
4.    Thymine (T)

they vary between individuals of the same species and between species. 
+ These sequences in some cases they may be encoded and therefore automatically translatable into
amino acid sequence (alphabetic sequences of approximately 21 letters)
that store structural information or physicochemical properties. :dna:

[**This project tries to identify the species based on its DNA sequences.**](Species_identification_from_DNA_sequences_using_Random_Forest.ipynb)


---

### Dataset 📖

You can use [Drosophila_test](Drosophila_test.xlsx) and [Drosophila_train](Drosophila_train.xlsx) for custom training. 
It contains data on many types of fruit flies.

For Google Colab, these files must be on your drive in the google sheets format, not the XLSX one.

---

### Requirements 🛠️
+ Python 3.10.12
+ pandas 1.5.3
+ numpy 1.22.4
+ scikit-learn 1.2.2
  
(only necessary if running on Google Colab):
+ gspread 3.4.2
+ gspread_dataframe 3.0.8
+ google-auth 2.17.3
+ google.colab 1.0.0

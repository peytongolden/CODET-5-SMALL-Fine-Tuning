# CODET-5-SMALL-Fine-Tuning
This file is best run in Google Colab but can be run on any other editor that can run .inpy files.  If you would wish to use a different training, test, or validation set, simply upload those files and find these lines of code and replace the file paths in quotes with the path to the desired files. 
df_train = pd.read_csv('ft_train.csv')
df_valid = pd.read_csv('ft_valid.csv')
df_test = pd.read_csv('ft_test.csv')

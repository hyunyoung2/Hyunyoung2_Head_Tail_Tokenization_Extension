## Head-Tail Tokenizatio Extension 


If you want to make dictionary, type in 

```
python3  make_dict.py
```

** If you want to run n-gram extension, you have to make n-gram dictionaries. 

for example, If running left-bigram extension of Head-Tail tokenization, 

first of all, make uni dictionary and left bigram dictionary and then run the command below with left-bigram option

If you want to experiment test data, type in 

```
python3 head_tail_tokenizer.py
```

When you prompt the line above, you have to make dictiionary 


Check your result with test data

```
python3 check_precision_and_recall.py
```


Finally, If you want to count the number of data 


```
python3 data_set_check.py
```

on make_dataset.py under data_processing directory 


If you want to set up location of dictionary and train & test file. 

change the variable, which is dict_types and child_dict_type, in head_tail_tokenizer.py and make_dict.py 

If you want the original full dataset for tran and test for Head-Tail w or w/o pos, access the following URL:

Head_Tail Without POS 
  
  for 00_kcc_q28_only_Train_and_Test,[KCC_Q28_Head_Tail_Train_and_Test_corpus](https://drive.google.com/file/d/1EazZ1Ucn0y7Mg4ZKA6-4rtfgBVtXgjPw/view?usp=sharing)

  for 01_kcc_150_only_Train_and_Test,[KCC_150_Head_Tail_Train_and_Test_corpus](https://drive.google.com/file/d/1DHY-FXWKffquE6NsvzIGmi2VWEASoPPs/view?usp=sharing)
  
  for 02_kcc_q28_n_150_only_Train_and_Test,[KCC_Q28_AND_KCC150_Head_Tail_Train_and_Test_corpus](https://drive.google.com/file/d/1JVee3VOg7P7sXpvQDMma_G_D1xfLi-5v/view?usp=sharing)


Head_Tail With POS 
  
  for 00_kcc_q28_only_Train_and_Test,[KCC_Q28_Head_Tail_Train_and_Test_corpus](https://drive.google.com/file/d/1unJox73bQB72hfoiZi5nbvQ3LX4VpZub/view?usp=sharing)

  for 01_kcc_150_only_Train_and_Test,[KCC_150_Head_Tail_Train_and_Test_corpus](https://drive.google.com/file/d/1Arf2-jgTnhHC0JPaU7mz-FODsjP4CdgA/view?usp=sharing)
  
  for 02_kcc_q28_n_150_only_Train_and_Test,[KCC_Q28_AND_KCC150_Head_Tail_Train_and_Test_corpus](https://drive.google.com/file/d/12DTGoqQWsosRXeWjicQgn9t-wnWdg6t4/view?usp=sharing)

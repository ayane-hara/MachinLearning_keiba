# MachinLearning_keiba

1. keiba_LTR_1_get race data.ipynb  
  It gets the race information.  
  Input file : No file  
  Output files : race_url.txt, race_data.csv
2. keiba_LTR_2_get horse_data, jockey_data.ipynb  
  It gets the horse and jockey information that is tied to the race information.  
  Input files : race_data.csv  
  Output files : horse_data.csv, jockey_data.csv
3. keiba_LTR_3 merge_data.ipynb  
  It merges race, horse and jockey information and adds sume features.  
  Input files : race_data.csv, horse_data.csv, jockey_data.csv  
  Output files : all_data.csv
4. keiba_LTR_4 train and predict.ipynb  
  It performs a ranking study and displays the predicted results.  
  Input file : all_data.csv  
  Model : LightGBM
5. keiba_4 3着に入るか判定.ipynb  
  It performs classification learnings and displays the predicted results.  
  Input file : all_data.csv  
  Model : CNN, LightGBM

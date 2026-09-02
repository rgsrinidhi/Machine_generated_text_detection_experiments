# Machine_generated_text_detection_experiments
This repository hosts experiements and notebooks on detection of machine generated text using multiple detectors.

Project Structure

Datasets : Hosts the base dataset for all three classes 
  -> Human writings 
  -> AI mimicking human
  -> AI generic

Feature files : Final training and testing dataset with feature values
 -> Training dataset
 -> Testing dataset

Model files: Model files for loading the model whenever required
  -> RoBERTa LoRA adapter pretrained files 
  -> Random forest classifier pickled file

Mutation Files: Generational results for each mutation in the genetic algorithm 

Python notebook : The ghost of machine hosts the whole experiment

Comments: 
The roberta model was trained separately in kaggle for compute resources and the downloaded model was further used for other processes in colab

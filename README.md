Custom NER Model Using Spacy

In this repository I have added a label to the entity list by annotating data and then tested it on an unseen data.

SUMMARY OF ALL THE STEPS:
1. Loaded a spaCy model and checked if it has ner pipeline.
2. Since no entities were found in the Doc object, we customized the NER model for detecting the job_role from the job posts.
3. Annotated the data to train the model.
4. Converted the annotated data into the spaCy bin object.
5. Generated the config file from the spaCy website.
6. Trained the model in the command line.
7. Loaded and test the saved model.

Applications of NER:
1. Enables Recommendation Systems.
2. Simplify Customer Support.
3. Classify the data of News Sources.
4. Optimizing the Search Engine Algorithms.

Conclusion:
We have taken just 10 records to train the model. For better accuracy and precision, we need to have a huge amount of annotated data to train a model.

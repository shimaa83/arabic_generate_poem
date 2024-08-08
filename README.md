# Generate Arabic Poem using fine tuning GPT model
idea is to use transformer and try to fine tune it and train model in your data set
# dataset
- Arabic Poetry Dataset (6th - 21st century) 
- https://www.kaggle.com/datasets/fahd09/arabic-poetry-dataset-478-2017
# steps:
    1. read dataset
    2. clean dataset
    3. choose specific poem type to make it easy for the model
    4. make your toknizer by split words and gave each word id
    5. split your data to train validation
    6. build your model
    7. train model
    8. finally use the pretrained model to generate poem

# Named_entity_Recognition

Here I performed Named Entity Recognition using Keras with TF. The dataset consists of some category,     
+ geo = Geographical Entity
+ org = Organization
+ per = Person
+ gpe = Geopolitical Entity
+ tim = Time indicator
+ art = Artifact
+ eve = Event
+ nat = Natural Phenomenon     

 After the preprocessing of the data I used a Bidirectional LSTM model to train it. The model has more than 1M parameter. Then using `adam` optimizer  trained the model, which has an acc of 98.5% on val set.    

All source code is available in the notebook. The dataset is also added in `.zip` format.    

#### Dataset
Dataset can also found *[here](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)*

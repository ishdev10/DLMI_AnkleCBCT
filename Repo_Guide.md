See `Model_Guide.md` for information on each model. 

### **Models**
Each jupyter notebook contains the complete pipeline, from start to finish, to:  
* Load and process the data
* Create data loaders (Train, Val and Test)
* Define model architecture and metric functions
* Train the model
* Save and plot training metrics
* Evaluate the model and view metrics
* Plot sample predictions

### **Results**
Each model folder contains the following results:
* `best_model.pth`: best saved model weights (for each configuration)
* `training_log.csv`: epoch-wise training and validation metrics
* `training_metrics.png`: epoch-wise plots of training metrics

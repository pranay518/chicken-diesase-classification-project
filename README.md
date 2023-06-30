# chicken-diesase-classification-project

## Workflows

1. Update config.yaml  :            Updating this file allows you to experiment with different configurations without changing the code itself.
2. Update secrets.yaml [Optional] : If your project involves sensitive information, such as API keys or authentication credentials.
3. Update params.yaml :             modifying  hyperparameters , include settings such as the number of layers, hidden units, dropout rates, or any other model-specific parameters.
4. Update the entity :              update the entity class or module that defines the objects or data structures relevant
5. Update the configuration manager in src config : ensures that any changes made to the configuration files are properly reflected and accessible within your project.
6. Update the components  :         data_ingestion, data_transformation, model_trainer files..
7. Update the pipeline   :          updating the pipeline module or script that orchestrates the sequence of steps 
8. Update the main.py   :           entry point or main script
9. Update the dvc.yaml  :          file helps track data, model versions, and dependencies
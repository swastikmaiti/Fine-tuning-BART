# Finetuing BART for Text2Text Generation

In this work we will be fine tuning `BART-LARGE`

Fine Tuning a Model is simple process that needs few steps and a perticular sequence.

The Steps in Fine Tuning are as follow:
  -  Load the Pre-Trained Model
  -  Data Pre-Processing
  -  Prepare Data Loader
  -  Define Optimizer and Scheduler
  -  Define Post Processing if any.
  -  Create the Training Loop

These steps/subtasks are the work that need to pe performed in sequence. The subtasks will vary according to the task, model or dataset.
In this work we show how to fine-tune [facebook/bart-large-cnn](https://huggingface.co/facebook/bart-large-cnn) on [gretelai/synthetic_text_to_sql](https://huggingface.co/datasets/gretelai/synthetic_text_to_sql) dataset.

# File Structure
- ***data_preparation.ipynb:*** This notebook contains code for data pre-processing and some rudimentary analysis to find context length of model input and output.
- ***bart-nl2sql.ipynb:*** This notebook contains the full code for fine-tuning.

# Architecture
- **Task:** text2text generation
- **Model:** BART Large
- **Fine-Tuning Framework:** Hugging Face

# Hugging Face

The details of Model Training and Implementation are present on the Model Card on Hugging Face Repository. Please refer to the model card for detailed model description and how to use.
You can also checkout the Inference Endpoint.

Model Card: [SwastikM/bart-large-nl2sql](https://huggingface.co/SwastikM/bart-large-nl2sql)

### If you find the repo helpful, please drop a ⭐

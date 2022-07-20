# neuromatch-compneuro-2022-project
Files for the NMA 2022 behavior project

## Structure 
* There is a `main` and a `development branch` (see dropdown menu on the top left)
* The idea is that `main` is always stable, `development` is where recent code additions get tested before they are pulled into `main`
* Therefore: Please direct pull requests towards `development`
* Workflow for getting your code into `main`
    * fork the repository 
    * change code in your local development branch
    * create a pull request asking to merge you  

## Notebook overview

### Preprocessing Notebook
* [Preprocessing Notebook **Main Branch** (open in Colab)](https://colab.research.google.com/github/ffvoigt/neuromatch-compneuro-2022-project/blob/main/playground/CalTech_Preprocessing_NMA2022_Sfenj1) 

* [Preprocessing Notebook **Development Branch** (open in Colab)](https://colab.research.google.com/github/ffvoigt/neuromatch-compneuro-2022-project/blob/development/playground/CalTech_Preprocessing_NMA2022_Sfenj1)

**Preprocessing Notebook (tbd)** - downloads Caltech data and converts it into a Pandas DataFrame for upstream analysis

### Feature Extraction Notebook
Takes the preprocessed tracking data and adds handcrafted features to it.
* [Feature Extraction Notebook **Main Branch** (open in Colab)](https://colab.research.google.com/github/ffvoigt/neuromatch-compneuro-2022-project/blob/main/playground/Feature_Extraction_NM2022_Sfenj1.ipynb) 

* [Feature Extraction Notebook **Development Branch** (open in Colab)](https://colab.research.google.com/github/ffvoigt/neuromatch-compneuro-2022-project/blob/development/playground/Feature_Extraction_NM2022_Sfenj1.ipynb)

### Classification Notebook
* **Classification Notebook (tbd)** - performs classification
 
## Useful links
* [Dataset overview](https://sites.google.com/view/computational-behavior/our-datasets/calms21-dataset)
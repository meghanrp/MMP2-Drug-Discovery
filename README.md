# MMP2 Computational Drug Discovery

## Background
The MMP2 (Matrix Metallopeptidase 2) is an enzyme produced by the MMP2 gene that is responsible for various activites, including assisting in the formation and growth of new blood vessels, cleaving the type IV collagen protein, repairing damaged tissues, bone remodeling, and more [(MedlinePlus [Internet], n.d.)](https://medlineplus.gov/genetics/gene/mmp2/). In addition, MMP2 is a necessary component of the extracellular matrix (ECM) [(MedlinePlus [Internet], n.d.)](https://medlineplus.gov/genetics/gene/mmp2/). Collectively, these functions allow for MMP2 to be prevalent throughout the body.

While MMP2 is involved in multiple critical cellular functions, the enzyme that can potentially be harmful when overexpressed. Specifically, MMP2 is commonly overexpressed in certain cancers, such as breast cancer [(Jiang & Li, 2021)](https://pubmed.ncbi.nlm.nih.gov/33568081/). This overexpression of MMP2 is ultimately dangerous for the cancer prognosis. When overexpression does occur, the MMP2 enzyme can degrade certain components of the ECM; furthermore, this can lead to cell migration/metastasis and tumor growth [(Webb et al., 2017)](https://bmccancer.biomedcentral.com/articles/10.1186/s12885-017-3418-y).

Previous studies have found that low levels of MMP2 are positively associated with smaller tumor sizes and a less likelihood of metastasis [(Webb et al., 2017)](https://bmccancer.biomedcentral.com/articles/10.1186/s12885-017-3418-y). With that, it has been suspected that inhibiting the overexpression of MMP2 in cancer patients can lead to these more favorable outcomes and prognoses [(Jezierska & Motyl, 2009)](https://pubmed.ncbi.nlm.nih.gov/19182722/).

## Purpose of this Project
As noted, the overexpression of MMP2 can lead to potentially dire complications in cancer (breast cancer) patients; however, by inhibiting MMP2, these complications can potentially be avoided. Although research continues to be conducted on MMP2 and cancer, there are currently no inhibitory drugs available that can readily decrease MMP2 levels in the body. The purpose of this project is to promote the discovery of such novel drug inhibitors by utilizing machine learning methods to predict the bioactivity levels of active compounds associated with the MMP2 protein.

## Data Sources
All molecular/chemical data for this project was acquired from the [ChEMBL database](https://www.ebi.ac.uk/chembl/g/#search_results/targets/query=MMP-2). The fingerprint files utilized in this project were acquired from the [Data Professor](https://github.com/dataprofessor/padel).

## Future Directions
Future directions of this project will be focused on using classification methods to determine the accuracy of predicting only the active chemical compounds. In addition, TensorFlow and other neural network packages may be utilized to improve the accuracy/sensitivity/specificity of the model.

## Repository Structure
The structure of this repository is as follows:

- data_analysis_results: Folder containing the results from the exploratory data analysis procedures.
- mmp2_datasets: Folder containing the MMP2 datasets utilized in the project.
- mmp2_model: Folder containing the final and primary MMP2 model utilized in the experiment in two different formats.
- model_results: Folder containing the model performance results for the various machine learning models utilized.
- PubChem.csv: File containing the PubChem fingerprint output.
- comp_drug_discovery_project.ipynb: The Jupyter notebook file for the project.
- fingerprints.zip: The file containing the fingerprint types that can be utilized in PaDEL.
- molecule.smi: The SMILES file that is utilized for PaDEL.

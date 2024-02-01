# CASEWorkshopTimeLineExtraction
Repository containing the code and data for the 'Timeline Extraction from Decision Letters Using ChatGPT' to appear in the 2024 CASE Workshop.

## Directory structure
Below is a short description of the structure of the repository.

- `InterAnnotatorAgreement/`: Contains the annotations and notebook for the calculation of the IAA scores.
    - `InterAnnotatorAgreement.ipynb`: Notebook containing the IAA calculation for the dates, events and relations. 
- `data/`: Contains the dataset and precalculated dataframes with the spacy part of the algoritm already run.
   - `txt_files` Original text extracted from PDF documents, with all sentences present
   - `ground_truth_data`:  dataset with all triples, with the dates manually corrected and converted to ISO format.
   - `annotated_triples` : dataset with the triples and the output of the date correction algorithm.
   - `uncorrected_spacy_output`: The output of the spacy algorithm for date extraction pre-run on the train and test sets.
- `scripts/`
- `TimeLineExperiments.ipynb/`: Notebook with the code integrated to run the complete pipeline and to evaluate the various components.


## Running the experiments
- To run the experiments you can run the 'TimeLineExperiments.ipynb' notebook, which will guide you through the various parts of the algorithm.

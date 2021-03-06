# task_potency

## GENERAL_SCRITPS
plug-in scripts to apply the task potency pipeline on any data. 
- roscha_task_potency.py requires path to preprocessed nifti files in the same registration space. It uses Mixture Modelling functions developped by Alberto Llera.
- roscha_MM_thresholding.py can be used for network estimation 

## DATA_NeuroIMAGE_fc
- subject and acquisition parameters (age, aroma, gender, TR, rms jenkinson)
- task performance
Z partial correlation matrices of the data used for both papers and permutation testing of age effect will be available after publication.

## SCRIPT_Potency_method_paper
Scripts of analysis and lists of subject corresponding to the preprint:
And the best task is ...? Using Task potency to infer task specificity
https://www.biorxiv.org/content/early/2017/11/29/111187
(under revision - updated script will be released soon)

## SCRIPT_Potency_age_paper
Scripts of analysis corresponding to the article:
Assessing age-dependent multi-task functional co-activation changes using measures of task-potency
www.sciencedirect.com/science/article/pii/S1878929317300592 
lists of subjects are the same as the one in script_potency_method_paper

## Pipeline related to both articles
To build matrices, the following pipeline is applyed:
NOTE : all raw data are not provided to rerun initial steps leading to the Z partial correlation. 
However Z partial correlation matrices are provided and scripts leading to these matrices are provided for transparency.
- reg_subjects_GENERIC (data not available to run this step): time series extraction 
- matrice_subjects_GENERIC (data not available to run this step): from time series to Z partial correlation matrices
- MMnormalizeALLmat: mixture modelling normalization of the Z partial correlation matrices

- taskpotency_submission (for method paper analysis - will be updated according to the review)
- taskpotency_age_submission (for age paper analysis)





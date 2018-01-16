# task_potency

## SCRIPT_Potency_method
Scripts of analysis and lists of subject corresponding to the preprint:
And the best task is ...? Using Task potency to infer task specificity
https://www.biorxiv.org/content/early/2017/11/29/111187

## SCRIPT_Potency_age
Scripts of analysis corresponding to the article:
Assessing age-dependent multi-task functional co-activation changes using measures of task-potency
www.sciencedirect.com/science/article/pii/S1878929317300592 
lists of subject are the same as the one in script_potency_method

## Pipeline
To build matrices, the following pipeline is done :
NOTE : all raw data are not provided to rerun initial steps leading to the Z partial correlation. 
However Z partial correlation matrices are provided and scripts leading to these matrices are provided for transparency.
- reg_subjects_GENERIC (data not available to run this step)
- matrice_subjects_GENERIC (data not available to run this step)
- MMnormalizeALLmat
- taskpotency_submission (for analysis)

## DATA_NeuroIMAGE_fc
- subject and acquisition parameters (age, aroma, gender, TR, rms jenkinson)
- task performance

Z partial correlation matrices of the data used for both papers and permutation testing of age effect will be available after publication.



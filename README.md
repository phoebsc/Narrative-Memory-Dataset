# Narrative Free Recall Dataset

This repository contains code used to produce the paper "The Narrative Free Recall Dataset: four stories, hundreds of participants, and high-fidelity transcriptions" by Omri Raccah, Phoebe Chen, David Poeppel, and Vy A. Vo.
The data in the project is at https://osf.io/h2pkv/. To reproduce the results, place the recall transcripts in respective folders such as /recall_transcript/recall_transcript_eyespy.
The code borrows heavily from the processing steps in the paper ["Geometric models reveal behavioural and neural signatures of transforming naturalistic experiences into episodic memories"](https://www.nature.com/articles/s41562-021-01051-6.epdf?sharing_token=zBNF7ExvsNAn6dwRV2wbatRgN0jAjWel9jnR3ZoTv0Os85t-vR-u-Efaty0-uoqOJVLSCaVoppMqs8h0fibLcqGN8-6I_NPhCJMoHMR5VvrNcBfBoco7C6Yp3vJJfeQhUOvYBnwv3BSjY0N1-ytdd_S-DhUyYmokmB3dfE-NX_Q%3D), with certain modifications outlined in our paper.

The repository is organized as follows:

### code
- A_topic_model.py : Python script for topic modeling (output saved in "result_models")
- B_HMM.py : Python script for event detection using Hidden Markov Models (output saved in "result_models")
- C_scoring.py : Python script for scoring the recalls (output saved in "result_models")
- D_listLearning.py : Python script for list learning analysis (figure 3)
- E_precisionPlot.py : Python script for generating precision plots (figure 2)
- F_check_text.py : Python script for text checking (output saved in "result_text")
  
### folders
- sherlock_helpers : Python package with support code for 'Sherlock' analyses
- result_models : Folder containing model results
- result_text : Folder containing text results
- story_transcript : Original transcripts of stories used in analyses

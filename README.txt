Code: 
Data_processing.ipynb: pick 25 sequences from the raw data
Sequence_Alignment_and_Split_Data.ipynb: MSA sequences and form training/testing sets
Viterbi Processing.ipynb: process the Viterbi score from phmm2.jar
Phylogenetic_Tree_Helper.ipynb: Edit sequence description for phylogenetic tree construction
Phmm2.jar: Hidden Markov Model program


File list:
main.fasta: 50 sequences collected from OXTR_primate_edited.fasta and OXTR_bonyFish_edited.fasta
main_edited.fasta: input sequences to construct phylogenetic tree

Folder src_primate
All files for basic set data (Primates)
File list: 
OXTR_primate.fasta: raw data of 95 primate oxytocin receptor genes from NCBI
OXTR_primate_edit.fasta: 25 picked unique sequences from OXTR_primate.fasta
OXTR_primate_aligned.fasta: MSA aligned sequences from OXTR_primate_edit.fasta
OXTR_primate_train.fasta: Training sets
OXTR_primate_test.fasta: testing sets
OXTR_viterbi_training: Viterbi scores for training set
OXTR_viterbi_testing: Viterbi scores for testing set
random_viterbi: Viterbi scores for random sequences
primate_log_viterbi_testing_out.fasta: results of viterbi processing

Folder src_bonyFish
All files for related set data (bonyFish)
File list: 
OXTR_bonyFish.fasta: raw data of 95 bonyFish oxytocin receptor genes from NCBI
OXTR_bonyFish_edit.fasta: 25 picked unique sequences from OXTR_bonyFish.fasta
OXTR_bonyFish_aligned.fasta: MSA aligned sequences from OXTR_bonyFish_edit.fasta
OXTR_bonyFish_training.fasta: Training sets
OXTR_bonyFish_testing.fasta: testing sets
bonyFish_viterbi_training: Viterbi scores for training set
bonyFish_viterbi_testing: Viterbi scores for testing set
random_viterbi: Viterbi scores for random sequences
bonyFish_log_viterbi_testing_out.fasta: results of viterbi processing
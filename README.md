# Some_Tranformers_NLP_tasks
This repository presents the use of transformers in different tasks :

1.Classification of incidents with 2 models:
 * Bert Based uncased and Electra models
We did the finetuning of these 2 models and analysed the differences in performance between them.

2.Questions Answering with tranformer Extractive Model:
We focused mainly on 3 formulations for  extracting each type of information("WHEN", "WHERE","EVENT") .We also tried different approaches like sliding window and also taking the concatenation of parts for the model bert-base-uncased-whole-masking-finetuned-squad.

3.Proverb Correction with Transformers:
We used 2 transformer models the first qanastek/pos-french-camembert for Postagging in order to identify the possible verbs  in the text and the second a Masked Language Model (MLM) in order to replace the verb in the proverb with the right one.
We compared its performance with Regular expressions based via spacy approach.

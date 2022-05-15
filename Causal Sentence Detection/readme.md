---
---
*<h1 align='center'> Causal Sentence Detection </h1>*
---

## *Models Used:*
- Bert encoding + (Machine Learning models / Bidirectional GRU with Attention / Neural Network)
- Bi-GRU-Att
- RNN, LSTM, Bi-LSTM
<br>

--> **Name**: Logesh.V <br>
--> **Email**: vlogesh2001@gmail.com <br>
--> **DATASETS**: 
- Causaly_small: https://archive.org/details/CausalySmall <br>
About Dataset: The dataset contains 2000 manually annotated sentences derived from
pubmed articles. 1113 out of 2000 sentences are annotated as Causal (Annotated_Causal = 1) and the rest (887) are annotated as non-Causal (Annotated_Causal = 0).

## Causal Sentence Detection
- The automatic detection and extraction of Semantic Relations is a crucial step to improve the performance of several Natural Language Processing applications.
- It is the task of detecting sentences that express causality,This work is focused on the detection and extraction of Causal Relations from open domain text

### Definition of causal:
- expressing or indicating cause : CAUSATIVE
- of, relating to, or constituting a cause
- involving causation or a cause : marked by cause and effect
- arising from a cause

### Causal Relations
A causal relationship exists when one variable in a data set has a direct influence on another variable. 

### Further work:
We have also tried implementing these below model, which didn’t end up training properly, so will need to figure out the problems caused in those…
- Bert+BiGRUAtt(full model training)
- Bert+Dense(full model training)

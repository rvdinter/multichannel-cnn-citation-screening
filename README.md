# Multichannel CNN Model to support Citation Screening in the Systematic Literature Review Process

To run this code, please upload it to Google Colab.
Also, make sure you download the 100-dimensional GloVe embeddings trained on 6B words from https://nlp.stanford.edu/projects/glove/

The SWIFT review datasets can be retrieved from Howard, B.E., Phillips, J., Miller, K. et al. SWIFT-Review: a text-mining workbench for systematic review. Syst Rev 5, 87 (2016). https://doi.org/10.1186/s13643-016-0263-z
The drug review datasets can be retrieved from Cohen AM, Hersh WR, Peterson K, Yen PY. Reducing Workload in Systematic Review Preparation Using Automated Citation Classification. JAMIA 2006: https://dmice.ohsu.edu/cohenaa/systematic-drug-class-review-data.html 

Please download the datasets and develop your own script using Entrez (https://biopython.org/docs/1.75/api/Bio.Entrez.html) to obtain title and abstracts. Some articles do not contain an abstract, as they are interviews or book chapters.

## Citing this code
For citing this code, please refer to `van Dinter, R., Catal, C., & Tekinerdogan, B. (2021). A Multi-Channel Convolutional Neural Network approach to automate the citation screening process. Applied Soft Computing, 112, 107765.`

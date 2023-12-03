# Towards a Corpus (and Language)-Independent Screening of Parkinson’s Disease from Voice and Speech through Domain Adaptation.
By Ibarra, E.J.; Arias-Londoño, J.D.; Zañartu, M.; Godino-Llorente, J.I. 
Bioengineering 2023, 10, 1316. https://doi.org/10.3390/bioengineering10111316

## Abstract:  

End-to-end deep learning models have shown promising results for the automatic screening of Parkinson’s disease by voice and speech. However, these models often suffer degradation in their performance when applied to scenarios involving multiple corpora. In addition, they also show corpus-dependent clusterings. These facts indicate a lack of generalisation or the presence of certain shortcuts in the decision, and also suggest the need for developing new corpus-independent models. In this respect, this work explores the use of domain adversarial training as a viable strategy to develop models that retain their discriminative capacity to detect Parkinson’s disease across diverse datasets. The paper presents three deep learning architectures and their domain adversarial counterparts. The models were evaluated with sustained vowels and diadochokinetic recordings extracted from four corpora with different demographics, dialects or languages, and recording conditions. The results showed that the space distribution of the embedding features extracted by the domain adversarial networks exhibits a higher intra-class cohesion. This behaviour is supported by a decrease in the variability and inter-domain divergence computed within each class. The findings suggest that domain adversarial networks are able to learn the common characteristics present in Parkinsonian voice and speech, which are supposed to be corpus, and consequently, language independent. Overall, this effort provides evidence that domain adaptation techniques refine the existing end-to-end deep learning approaches for Parkinson’s disease detection from voice and speech, achieving more generalizable models.

## Software Implementation
All source code used to generate the results and figures in the paper are in the repository.
The data used in this study is provided under request to the owners of the databases.

## Getting the code

You can download a copy of all the files in this repository by cloning the repository:

    git clone https://github.com/orgs/BYO-UPM/repositories.git

or [download a zip archive]([https://github.com/orgs/BYO-UPM/repositories/archive/master.zip).

A copy of the repository is also archived at 'DOI'

## Dependecies

You'll need a working Phyton environment to run the code. 

## License

All source code is made available under a 'MIT' license. You can freely
use and modify the code, without warranty, so long as you provide attribution
to the authors.

Ibarra, E.J.; Arias-Londoño, J.D.; Zañartu, M.; Godino-Llorente, J.I. Towards a Corpus (and Language)-Independent Screening of Parkinson’s Disease from Voice and Speech through Domain Adaptation. Bioengineering 2023, 10, 1316. https://doi.org/10.3390/bioengineering10111316

If you find our work useful, can cite our paper using:

```
@article{Ibarra2023TowardsAC,
  title={Towards a Corpus (and Language)-Independent Screening of Parkinson’s Disease from Voice and Speech through Domain Adaptation},
  author={Emiro J. Ibarra and Juli{\'a}n D. Arias-Londo{\~n}o and Mat{\'i}as Za{\~n}artu and Juan Ignacio Godino-Llorente},
  journal={Bioengineering},
  year={2023},
  volume={10},
  url={https://api.semanticscholar.org/CorpusID:265224807}
}
```

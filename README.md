# ALEXSIS
ALEXSIS:  A Dataset for Benchmarking Lexical Simplification for Spanish

## Description

The ALEXSIS Spanish Dataset for Lexical Simplification contains 381 instances. Each instance is composed by a sentence, a target complex word, and 25 candidate substitutions. The dataset format is similar to that of LexMturk (Horn et al., 2014) but in ALEXSIS the sentences are not tokenized. 
A total of 380 instances of the 381 have only 1 appearance of the complex word in the sentence.
There is only one instance with two appearances of the complex word in the sentence. This is the case of the instance in line 263.
The sentence is: "Limita al norte con el paraje Árbol Solo, al sur con el paraje San Vicente, al este con la localidad de San Andrés y al oeste con el Canal San Martín." The complex is "paraje". The first appearance of the complex word paraje was the one marked in bold for the annotators.

The instances have the following format in UTF8:

<SENTENCE><TAB><COMPLEX_WORD_IN_SENTENCE><TAB><SUBSTITUTION1><TAB>...<TAB><SUBSTITUTION25>

See below an instance of the dataset.

________________________________  SAMPLE INSTANCE __________________________
Sufrió una importante reducción en su capacidad para poder acogerse a las normas de la FIFA para los estadios de fútbol. acogerse adaptarse sumarse incorporarse obedecer apegarse adaptarse adaptarse ampararse ampararse adaptarse apegarse aceptar asimilarse adaptarse aplicarse aceptarse incorporarse refugiarse amparar recurrir aceptar refugiarse cumplir con adaptarse admitirse
____________________________________________________________________________

The ALEXSIS Spanish Dataset for Lexical Simplification can also be found at github:  [https://github.com/LaSTUS-TALN-UPF/ALEXSIS](https://github.com/LaSTUS-TALN-UPF/ALEXSIS)

##Citation

If you make use of the ALEXSIS dataset for Spanish, please cite the following paper:

Daniel Ferrés and Horacio Saggion.
ALEXSIS: A Dataset for Lexical Simplification in Spanish.[PDF](www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.383.pdf)
Proceedings of the Language Resources and Evaluation Conference (LREC) 2022.

link to the bibtex format file [.bib]


@inproceedings{ferres-saggion@LREC2022,
    title = "ALEXSIS: A Dataset for Lexical Simplification in Spanish.",
    author = "Ferrés, Daniel  and Saggion, Horacio",
    booktitle      = {Proceedings of the Language Resources and Evaluation Conference},
    month          = {June},
    year           = {2022},
    address        = {Marseille, France},
    publisher      = {European Language Resources Association},
    pages     = {3582--3594},
    url       = {https://aclanthology.org/2022.lrec-1.383}
}

##Contact

LaSTUS lab@TALN@UPF

Daniel Ferrés - daniel.ferres[at]upf.edu

Horacio Saggion - horacio.saggion[at]upf.edu   (corresponding author)

ConMuTeS project Link: https://www.upf.edu/web/conmutes

##Acknowledgements

ConMuTeS project: Context-aware Multilingual Text Simplification (ConMuTeS) PID2019-109066GB-I00/AEI/10.13039/501100011033
Ministerio de Ciencia, Innovación y Universidades (MCIU) of Spain
Agencia Estatal de Investigación (AEI) of Spain

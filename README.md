# MirasIrony : A Persian Text Corpus of ironic and non-ironic tweets.
This repository contains MirasIrony corpus and description along side with what it has been used for and what it can be used for. The dataset is provided in Irony_Dataset/MirasIrony.xlsx which contains 2942 data samples. In order to use the dataset you need to submit a request to preni@miras-tech.com and we will provide you with the password needed to access the MirasIrony.xlsx .

## MirasIrony Description
MirasText is the result of manually annotated Persian tweets as ironic or non-ironic.
The definition of irony that was used during the annotation process is *"The use of words that are the opposite of what you mean, as a way of being funny.”* and *”A situation in which something whichwas intended to have a particular result has the opposite or a very different result"*. In Persian it has been translated as sarcasm, satire, mockery and ridicule.
 
The following table demonstrates the statistics of the corpus:

|       Total number of samples      |   2941   |
|:--------------------------:|:-------------:|
|     Number of ironic samples    | 1278 |
|   Number of non-ironic samples   |     1663     |
|      Average number of tokens per tweet      |      32.25     |
| Maximum number of tokens per tweet |      50    |

## Dataset Description
The dataset is provided in Irony_Dataset/MirasIrony.xlsx. Each line contains a tweet and it's coressponding label. Label 1 is for ironic and 0 for non-ironic.

## Cite
Please cite the following paper in your publication if you are using MirasIrony in your research:
```bibtex
@InProceedings{SABETI18.385,
  author = {Behnam Sabeti ,Hossein Abedi Firouzjaee ,Ali Janalizadeh Choobbasti ,Seyed hani elamahdi Mortazavi Najafabadi and Amir Vaheb},
  title = {MirasText: An Automatically Generated Text Corpus for Persian},
  booktitle = {Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018)},
  year = {2018},
  month = {may},
  date = {7-12},
  location = {Miyazaki, Japan},
  editor = {Nicoletta Calzolari (Conference chair) and Khalid Choukri and Christopher Cieri and Thierry Declerck and Sara Goggi and Koiti Hasida and Hitoshi Isahara and Bente Maegaard and Joseph Mariani and H�l�ne Mazo and Asuncion Moreno and Jan Odijk and Stelios Piperidis and Takenobu Tokunaga},
  publisher = {European Language Resources Association (ELRA)},
  address = {Paris, France},
  isbn = {979-10-95546-00-9},
  language = {english}
  }
  ```

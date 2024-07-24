## Data Preparation

The data, in *.fasta format, are downloaded from UniProt's UniRef database using **UniRef-download.sh**, specifying species with TaxID.

The data are shuffled and split into three datasets: training/finetuning, evaluation, and inference/testing, using **train-eval-test-datasets.ipynb**.

The data's statistic (frequencies of amino acid(s)) is computed in **Data-exploration.ipynb**.
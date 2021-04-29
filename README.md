# Triplet_repeats



## Download the directory:

```
git clone git@github.com:AWGL/triplet_repeat_automation.git

```


## Create and activate the conda environment

```
conda env create -f triplet_repeat_automation.yml

conda activate triplet_repeat_automation

```



## Create the executable:


The executable file must be created on a windows platform


```
pyinstaller triplet_repeat_automation.py

```


## Requirements:


The folder with the executable file must also contain:

* A text file outputted from genemapper in asuragen format, with name in the format "worksheetid_gene.txt"
* Two excel files "Triplet_controls.xlsx" and "Triplet_controls_FRAX.xlsx"




## Run the executable:


* Click on the executable 
* Input the gene name and worksheet number into the console







## Run the tests:

```

python -m unittest test_triplets_repeats.py

```


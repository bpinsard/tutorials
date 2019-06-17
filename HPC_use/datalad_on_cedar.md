#Install

You can create a virtualenv to install datalad.

```
module load git-annex/6.20180807
pip install datalad
```

# usage example

## Install a dataset

```
module load git-annex/6.20180807
datalad install https://github.com/OpenNeuroDatasets/ds001761.git
git annex enableremote s3-PUBLIC
```

## Get the files you need

```
datalad  get sub-*/ses-*/anat/*_T1w.nii.gz
```

# PANDAS IN 30 DAYS

Update: 23 May 2024

https://courses.dataschool.io/view/courses/pandas-in-30-days

## Versions of packages

Conda environment: pandas30
Python 3.12.3
pandas 2.2.2

### Install main packages

See @downloaded-from-udemy\@downloaded-lesson_264-requirements-file\bot_req.txt

```
$ . a
$ conda install ipykernel
$ python -m ipykernel install --user --name pandas30
```

### List kernels

$ jupyter kernelspec list

---

Update: 19 June 2024

https://docs.conda.io/projects/conda/en/4.6.0/commands/list.html

List all packages in the current environment:

```
conda list
```

List all packages installed into the environment ‘myenv’:

```
conda list -n pandas30
```

Save packages for future use:

```
conda list –-export > package-list.txt
```

Reinstall packages from an export file:

```
$ conda config --append channels conda-forge
$ conda create --name pandas30 --file package-list.txt
```

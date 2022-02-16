# Machine Learning Courses Repositories

**Clone submodules**
```zsh
git clone --recurse-submodules https://gitlab.com/durandv-learn/ml-courses.git
```

**Environments**

* Conda
```bash
conda create -p ./env python=3.8 numpy pandas matplotlib jupyter scikit-learn seaborn
```

* Pyenv + Poetry
```bash
poetry init --name ml-courses --python=3.9.9
poetry add pandas numpy matplotlib scikit-learn seaborn
```

## ML Classic

### Machine learning in python with scikit-learn
* scikit-learn-mooc (https://github.com/INRIA/scikit-learn-mooc/)

```bash
git submodule add -f git@github.com:INRIA/scikit-learn-mooc.git scikit-learn-mooc
```


### COMS W4995 Applied Machine Learning Spring 2020
* Course: https://www.cs.columbia.edu/~amueller/comsw4995s20/schedule/
* Folder: aml_amueller_2020

### Zero to Mastery Machine Learning Course (zero-to-mastery-ml)
git submodule add https://github.com/mrdbourke/zero-to-mastery-ml.git zero-to-mastery-ml
git submodule update --remote --init zero-to-mastery-ml

### deeplearning.ai - Natural Language Processing with Classification and Vector Spaces
* Course: https://www.coursera.org/learn/classification-vector-spaces-in-nlp
* Folder: deeplearning_ai_nlp_2020

mkdir deeplearning_ai_nlp_spec_2020
cd deeplearning_ai_nlp_spec_2020
git submodule add https://github.com/ijelliti/Deeplearning.ai-Natural-Language-Processing-Specialization.git repo_1
git submodule update --remote --init repo_1
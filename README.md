# Detecting-Far-Right-Talking-Points


## Description of the Project

This repository includes code for the final project for [Le Wagon's Data Science Bootcamp](https://www.lewagon.com/data-science-course?utm_term=le%20wagon%20courses&utm_campaign=WW+%7C+Brand+%7C+EN+%7C+S&utm_source=adwords&utm_medium=ppc&hsa_acc=9887519486&hsa_cam=17795863130&hsa_grp=138703896883&hsa_ad=634543295246&hsa_src=g&hsa_tgt=kwd-811252777396&hsa_kw=le%20wagon%20courses&hsa_mt=b&hsa_net=adwords&hsa_ver=3&gclid=Cj0KCQiAveebBhD_ARIsAFaAvrHtFXBTG6fge-2tThnAgAJx13gnibCR00eBIoS6UaoLbzPT3ZjTtFQaAogiEALw_wcB) (Batch 1014) in Berlin. Using over 144,000 speeches given in the European Parliament between 1996 and 2011, we attempt to understand when politicians from liberal, conservative, environmentalist and leftist parties evoke far-right talking points. To achieve this, we trained a deep learning classifier to predict if a given speech was given by a far-right politician or not. We then performed topic modeling on the subset of speeches our model falsely classified as far-right, i.e. our model detected far-right rhetoric, but the speech itself was not given by a far-right Member of the European Parliament (MEP). We presented the our findings at Le Wagon's Demo Day 2022, feel free to watch our presentation using [this link](https://drive.google.com/file/d/1NcrEVAfzOHh2Q9QShYnqyt-CDaIdGCqu/view?usp=sharing).


## Description of the Repository

This repository contains two main subdirectories, `data_cleaning` and `deep_learning`. The [`data_cleaning`](data_cleaning) subdirectory contains several notebooks that load, clean, preprocess and balance the datasets we use for our analysis. In the [`deep_learning`](deep_learning) subdirectory, you will find notebooks pertaining to the training of our deep learning model and the unsupervised learning model we use to perform topic modeling on relevant subsets of the data. We recommend running the notebooks in the `deep_learning` folder remotely using [Google Colab](https://colab.research.google.com/), as they are computationally intensive. If you have trouble running any of the files in this repository, or if you have any questions about this project, please feel free to contact me at [kpekkip@uchicago.edu](mailto:kpekkip@uchicago.edu).


## Data

The data for our project stems from the [European Parliament Proceedings Parallel Corpus (1996-2011)](https://www.statmt.org/europarl/) and can be downloaded using [this link](https://www.statmt.org/europarl/#:~:text=Download-,source%20release,-(text%20files)%2C%201.5). The dataset consists of roughly 10,000 `.txt` files that do not follow a set structure. It is crucial that you run the cleaning and preprocessing steps laid out in [data_cleaning_preprocessing.ipynb](data_cleaning/data_cleaning_preprocessing.ipynb) in order to reproduce our work. Again, should you have any questions about the data or the steps we took to clean or preprocess it, feel free to reach out to me at [kpekkip@uchicago.edu](mailto:kpekkip@uchicago.edu).



Whereismytransport assessment
==============================

The objective of this repository is to highlight my technical abilities for Whereismytransport based on the providing hiring exercise.
I have selected the first exercise, user segment creation, because of the following reasons:
-	Most work a data scientist does is data cleaning, which includes customer segmentation. Because of that I thought it would be most useful to demonstrate my skills in this area;
-	Creating user segments is useful for any company and always adds value. Better understanding a client base allows for better user targeting and product improvement. On top of that, depending on the use case, segments can be stored in a feature storage to use for future product features and data analytics exercises;
-	I have worked on quite some message effectiveness/improvement campaigns and found that AB testing is the most reliable method to do this because it eliminates external influences (eg phone user broke, technical issues. Within the tech space Whereismytransport is in, it should be fairly easy to implement and manage this;
-	I would assume that geographical entities are already available for Whereismytransport, so creating a tool which extracts these wouldn't directly be of use.

The project contains the following notebooks:
- 1 – **Data download**. After forking the Github repository, run this code to download the data from source;
- 2 – **Exploratory analysis**. Use this to gain an understanding on the available data
- 3 – **Segmentation**. Worked-out segmentation exercise.



Full description of the exercise and source data: https://drive.google.com/drive/folders/1akT7jbXYy2-zLHEtnK3q6vqcQ-JdRO9H

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │  
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment
    │
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

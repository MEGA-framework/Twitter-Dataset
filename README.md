# Twitter Dataset of COVID-19 Pandemic

We provide the tweet IDs of the posts on Twitter related to the COVID-19 pandemic.

In particular, tweets posted between 1 January and 31 May 2021 and containing keywords: "COVID19", "COVID", "Coronavirus", "Vaccine" and "Mask" (string matching is case-insensitive) are considered, for a total of 986,446 (some of the tweets had been deleted).

## Format

The format of the csv file is:
<ul>
  <li>Tweet ID</li>
  <li>Date</li>
</ul>
in comma-separated columns. <br /> <br />

Due to privacy concerns, we can only provide the tweet IDs and the dates. To obtain the raw data of each tweet, tools such as <a href="https://github.com/DocNow/hydrator">Hydrator</a> can be used to rehydrate the dataset.

## Citing
If you use the provided Twitter Dataset of the COVID-19 Pandemic for research that results in a publication, please cite our [paper](https://ieeexplore.ieee.org/abstract/document/10251942):
```
@article{hang2023mega,
  title={{MEGA}: Machine learning-enhanced graph analytics for infodemic risk management},
  author={Hang, Ching Nam and Yu, Pei-Duo and Chen, Siya and Tan, Chee Wei and Chen, Guanrong},
  journal={IEEE Journal of Biomedical and Health Informatics},
  volume={27},
  number={12},
  pages={6100--6111},
  year={2023},
  publisher={IEEE}
}
```

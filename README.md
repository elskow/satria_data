# **Optical Character Recognition on Plate Number**
## **Introduction**
This project made for [Satria Data 2023](https://satriadata.kemdikbud.go.id/) elimination round. The goal is to make a program that can recognize plate number from an image. 

This project reformatted using [Black](https://pypi.org/project/black/). The project was trained using [Kaggle](https://www.kaggle.com/)'s with T4 x2 GPU. We wouldn't recommend to run this project on your local machine because it will take a lot of time and resources.

We got **97.33** score accuracy on leaderboard and finished on 33rd place.

## **Project Structure**
```bash
.
├── data
│   ├── test_data
│   │   ├── *.png
│   │   └── DataTest.csv
│   └── train_data
│       ├── *.png
│       └── DataTrain.csv
├── Resources
│   └── Juknis Satria Data 2023.pdf
├── src
│   ├── playground
│   │   └── *.ipynb
│   ├── csvpreprocess.ipynb
│   ├── prediction.ipynb
│   └── preprocess.ipynb
├── .gitignore
├── LICENSE
└── README.md
```
- `data` folder contains the dataset for training and testing.
- `Resources` folder contains the rules for this project.
- `src` folder contains the source code for this project.
- `src/playground` folder contains the source code for testing the model.
- `src/csvpreprocess.ipynb` is the source code for preprocessing the dataset.
- `src/prediction.ipynb` is the source code for predicting the dataset.
- `src/preprocess.ipynb` is the source code for preprocessing the image.


## **Contributors**
- [Helmy LuqmanulHakim](https://github.com/elskow)
- [Naufal Farras Pratama](https://github.com/NaufalF121)
- [Rizal Hidayatulloh](https://pddikti.kemdikbud.go.id/data_mahasiswa/QkVDN0UxQzgtMjIyRS00Qzc1LUEzRjEtMEQ1QzNEOEI1Mjk5)

## **License**
[MIT](https://choosealicense.com/licenses/mit/)
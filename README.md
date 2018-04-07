## Paper

Karduni, A., Wesslen, R., Santhanam, S., Cho, I., Shaikh, S., and Dou W. (2018). Can You Verifi This? Studying Uncertainty and Decision-Making about  Misinformation in Visual Analytics. ICWSM 2018.


## Instructions to run

The code is written in R 3.4.3 or higher. Highly recommend using RStudio 1.1.383 or higher.

Open the file verifi-icwsm-2018.Rproj.

This repo contains 3 codes:
1) R-stream-code: Twitter Streaming API Code to pull the original data ([Rmd](./02-linguistic-features.Rmd) / [HTML](https://htmlpreview.github.io/?https://github.com/wesslen/verifi-icwsm-2018/blob/master/02-linguistic-features.html))
2) Random Forest Model on Language Feature Selection ([Rmd](./02-linguistic-features.Rmd) / [HTML](https://htmlpreview.github.io/?https://github.com/wesslen/verifi-icwsm-2018/blob/master/02-linguistic-features.html))
3) Logistic Regression: Accuracy and Fake Decisions ([Rmd](./03-logistic-regression.Rmd) / [HTML](https://htmlpreview.github.io/?https://github.com/wesslen/verifi-icwsm-2018/blob/master/03-logistic-regression.html))

## Data

| format | Description            |
| ------ | ---------------------- |
| csv    | [User Interaction Logs](./data/userLogs.csv) |
| csv    | [User Responses (Decisions)](./data/userForms.csv) |
| csv    | [Pre-questionnaire](./data/pretest.csv) |

All user-level data are anonymized. Use user-id for matching.

## Figures

### Verifi

![Verifi Interface](./img/VerifiInterfaceWithLabel.png)

### Language Features

![Interface Language Features](./img/language-features.png)

### User Study

#### Study Demographics

![Study Demographics](./img/demographics.jpg)

#### Study Decision Accounts Truth Table

![Decision Accounts Truth Table](./img/truthTable2.pdf)

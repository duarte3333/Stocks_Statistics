
# Stocks Statistics

This program, through an Excel with three columns: date of purchase of the share, price of purchase of the share and name of the share, allows you to retrieve numerous statistics about the shares placed in this Excel
## Installation

Run these commands to install the used libraries

```bash
  pip install pandas
  pip install matplotlib
  pip install numpy
  pip install prettytable
```
Then, go to yahoo finance website to see the acronym of all stock's.

![Imagem3](https://user-images.githubusercontent.com/76222459/147173819-303046c5-bbd6-4650-b3e2-f6e6aaac2751.png)


For example Tesla's acronym is TSLA, the picture above shows where to look for the acronym.

After that, fill in the excel with the informations as shown in the figure below.

![excel](https://user-images.githubusercontent.com/76222459/147171430-10a04b5b-2526-4e7b-b8a7-a26eee23e189.png)

Make sure excel is in the same folder as the python script

In this sheet the last stock is in cell 8, so put this number in the number_acoes() function in the code

![f1](https://user-images.githubusercontent.com/76222459/147171735-ac548e4a-8cf4-4cf9-9048-49f767134636.png)

The program can take around 30 to 40s to run because needs to see several stock values in real time.
For that reason, check if you have good internet connection!
## Results

The program returns several important results for investment analysis.

![results](https://user-images.githubusercontent.com/76222459/147172049-0efe8a6c-db81-4612-89cc-a70c241c86d1.png)

In addition, it provides graphics that allow you to carefully view statistical details.

![g10](https://user-images.githubusercontent.com/76222459/147173310-52c09efa-33d0-40e1-8332-e41bac38ce16.png)

![g6](https://user-images.githubusercontent.com/76222459/147173381-1431dd7a-34b5-41ec-b998-5c4ce56e56a5.png)

![g7](https://user-images.githubusercontent.com/76222459/147173403-05716b50-a59f-4cd8-8f75-98b8d1daf6b2.png)

Thanks to matplotlib it is possible to make all of these graphics. I hope that you enjoy this work!

## Authors

- [@duarte3333](https://www.github.com/duarte3333)

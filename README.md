
# Stocks statistics in real time

This program, through an Excel with four columns: date of purchase of the share, price of purchase of the share, name of the share and the value of the participation that was acquired allows you to retrieve numerous statistics in real time about the shares placed in this Excel
## Installation

Run these commands to install the used libraries

```bash
  pip install pandas
  pip install matplotlib
  pip install numpy
  pip install prettytable
```
Then, go to yahoo finance website to see the acronym of all stock's.

![Imagem32](https://user-images.githubusercontent.com/76222459/147173926-9b45fac1-ae0d-46df-bd91-6b8a8c4436c7.png)


For example Tesla's acronym is TSLA, the picture above shows where to look for the acronym.

After that, fill in the excel with the informations as shown in the figure below.

![excel](https://user-images.githubusercontent.com/76222459/147183300-6698952a-3cc3-40f6-a4f4-c73951e8519e.png)

Make sure excel is in the same folder as the python script

In this sheet the last stock is in cell 8, so put this number in the number_acoes() function in the code

![f1](https://user-images.githubusercontent.com/76222459/147171735-ac548e4a-8cf4-4cf9-9048-49f767134636.png)

The program can take around 30 to 40s to run because needs to see several stock values in real time.
For that reason, check if you have good internet connection!
## Results

The program returns several important results for investment analysis in real time. The table shows the top five stocks with the most profit in real time.

![results](https://user-images.githubusercontent.com/76222459/147172049-0efe8a6c-db81-4612-89cc-a70c241c86d1.png)

In addition, it provides graphics that allow you to carefully view statistical details.

![g10](https://user-images.githubusercontent.com/76222459/147173310-52c09efa-33d0-40e1-8332-e41bac38ce16.png)

![g6](https://user-images.githubusercontent.com/76222459/147173381-1431dd7a-34b5-41ec-b998-5c4ce56e56a5.png)

![g7](https://user-images.githubusercontent.com/76222459/147173403-05716b50-a59f-4cd8-8f75-98b8d1daf6b2.png)

Thanks to matplotlib it is possible to make all of these graphics. I hope that you enjoy this work!
## ???? About Me
I'm a mechanical engineering student and I really enjoy programming...

## Authors

- [@duarte3333](https://www.github.com/duarte3333)

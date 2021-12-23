
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

![tesla](https://user-images.githubusercontent.com/76222459/147171111-5d151803-15a3-4aef-9e1e-38329a61dfa1.png)

For example Tesla's acronym is TSLA, the picture above shows where to look for the acronym.

After that, fill in the excel with the informations as shown in the figure below.

![excel](https://user-images.githubusercontent.com/76222459/147171430-10a04b5b-2526-4e7b-b8a7-a26eee23e189.png)

Make sure excel is in the same folder as the python script

In this sheet the last action is in cell 8, so put this number in the number_acoes() function in the code

![f1](https://user-images.githubusercontent.com/76222459/147171735-ac548e4a-8cf4-4cf9-9048-49f767134636.png)

The program can take around 30 to 40s to run because needs to see several stock values in real time.
For that reason, check if you have good internet connection!
## Results

The program returns several important results for investment analysis.

![results](https://user-images.githubusercontent.com/76222459/147172049-0efe8a6c-db81-4612-89cc-a70c241c86d1.png)

The program returns several important results for investment analysis.

In addition, it provides graphics that allow you to carefully view statistical details.

![g1](https://user-images.githubusercontent.com/76222459/147172548-76f29c15-6233-4161-bf77-abe686ad46a9.png)

Thanks to matplotlib it is possible to make all of these graphics

![g2](https://user-images.githubusercontent.com/76222459/147172570-e366373b-6297-47a7-a58c-256f2cb5c7d5.png)

![g3](https://user-images.githubusercontent.com/76222459/147172589-eef826a8-1d54-450e-8384-4baa78e03efd.png)


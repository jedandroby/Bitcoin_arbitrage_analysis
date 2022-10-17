# Bitcoin Arbitrage Analysis
Challenge 3 for fintech bootcamp with UC Berkeley, arbitrage analysis with pandas on bitcoin prices across 2 exchanges.

This Python notebook `crypto_arbitrage.ipynb` was created in Jupyter labs and analyzes the Bitcoin price from January 2018 to April 2018 across bitstamp and coinbase. The CSV files are located in the Resources folder. The notebook is ready to run analysis on 3 days with a 4th day at the end. It would be easy to follow along and run analysis on other days using the same logic. 

The results from this analysis show that the arbitrage opportunites in this dataset were limited to early periods, namely late January. With little to no profitable trades in the Febraury and March months. However those opporunities in late January showed some strong profits when trading with 1BTC trades.

For example, one of the days analyzed was January 28th, 2018. 
<p><img src=./Resources/Images/BTC_jan_28.png width="500" height="400"/></p>


Clear opportunity for some trades to be made, and after doing all the math and code, this was the cumulative profits for a day of trades. 
<p><img src=./Resources/Images/btc_profits_jan28.png width="500" height="400"/></p>

This was by the far the most successful day and if you want to learn more or follow along keep scrolling down for a more detailed analysis of what you'll need. 

First make sure you have cloned the repo to have the files needed.

---

## Technologies

<p><img src=./Resources/Images/versions.png width="500" height="200"/></p>

The above screenshot shows the python version needed `python 3.7` and the only package you will need installed which is `pandas`. If you have set up a dev environment with anaconda or something similar you will be fine. If not keep scrolling and I will help explain. 
If you need the dev environment setup and dont know what [Anaconda]( https://docs.anaconda.com/anaconda/install/) is then click on [Anaconda]( https://docs.anaconda.com/anaconda/install/) and follow after you get that setup!

---

## Installation Guide

To get your dev environment setup, and get jupyter labs running follow along:

- Creating a dev environment for python 3.7 called 'dev' - if you do not already have an environment setup 
    - Get setup in your preferred CLI (Gitbash, terminal, etc)
    - `conda create -n dev python=3.7 anaconda`
    - Once you have created the environment type the following to activate and deactivate.
<p><img src=./Resources/Images/anaconda_dev_env.png width="300" height="150"/></p>
- Once your `dev` env is setup go ahead and navigate to the same directory as the newly cloned repo and type `juypter lab` in your console.
<p><img src=./Resources/Images/jupyterlab.png width="400" height="75"/></p>
- Thats it! Then your in, you should see the same as the screenshot below.
<p><img src=./Resources/Images/crypto_arbitrage.png width="700" height="300"/></p>

- If you get an import error for pandas just make sure you have pandas installed in your dev environment with a quick `pip install pandas` command and try again.

---
## Usage

Once you are in jupyter labs open the `crypto_arbitrage.ipynb` notebook, make sure to run all the lines so you import the packages and create all the dataframes needed to run the analysis. After that feel free to create more cells at the bottom and perform your own analysis on different dates or under different conditions!

You will find two more dates that I analyzed, these each failed to produce any trades that were more profitable than 1% so I did not complete the analysis on these dates. Instead at the bottom I did the same steps for January 29th and produced some very nice profits for that day as well. Its interesting to notice on the 29th that after 12:00 the profits went away and the price difference must have shrunk between the two exchanges. There could be more dates in January that could still provide some opportunities for arbitrage and would be fun to explore. 

---

## Contributors

[Robin Thorsen](https://www.linkedin.com/in/robin-thorsen-079819120/) was the main developer working on this project. Alot of code was provided by UC Berkeley for this challenge. 

Best reached via email - robinbthorsen@gmail.com

---

## License

Apache 2.0 public License applied, feel free to clone and fork and use and reach out if you have questions. 

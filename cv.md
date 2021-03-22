<style>
    form{
        float:left;
        display: inline-block;
    }
</style>

<form action="https://sickotra.github.io/">
    <input type="submit" style = "
  border: ridge #4780D5; /* Blue */
  color: black;
  background-color: #FFD700; /* Yellow */                                
  padding: 10px 15px;                               
  text-align: center;
  text-decoration: none;
  display: inline;
  font-size: 16px;
  margin: 4px 2px;
  width: 100px;
  cursor: pointer;" value="Home" />
</form>

<form action="https://sickotra.github.io/Projects/projects">
    <input type="submit" style = "
  border: ridge #4780D5; /* Blue */
  color: black;
  background-color: #FFD700; /* Yellow */                                
  padding: 10px 15px;                               
  text-align: center;
  text-decoration: none;
  display: inline;
  font-size: 16px;
  margin: 4px 2px;
  width: 100px;
  cursor: pointer;" value="Python" />
</form>

<form action="https://sickotra.github.io/cv">
    <input type="submit" style = "
  border: ridge #4780D5; /* Blue */
  color: black;
  background-color: #FFD700; /* Yellow */                                
  padding: 10px 15px;                               
  text-align: center;
  text-decoration: none;
  display: inline;
  font-size: 16px;
  margin: 4px 2px;
  width: 100px;
  cursor: pointer;" value="Diamonds" />
</form>

<form action="https://sickotra.github.io/maths">
    <input type="submit" style = "
  border: ridge #4780D5; /* Blue */
  color: black;
  background-color: #FFD700; /* Yellow */                                
  padding: 10px 15px;                               
  text-align: center;
  text-decoration: none;
  display: inline;
  font-size: 16px;
  margin: 4px 2px;
  width: 100px;
  cursor: pointer;" value="Blog" />
</form>




<br>

<br>
   
--------------------------------------------------------
## Diamonds Data Analysis

The dataset selected for analysis was the 'Diamonds' dataset found on Kaggle (2017) consisting of 53,940 round cut diamond observations. This dataset was thought to be particularly rich for performing data analysis and machine learning due to the complexity of the variables in relation to the diamond price (GIA, 2021).

After cleaning the data, the final dataset consisted of 53,772 observations with 10 features: 
* `carat` (0.2 - 5.01 ct.)
* `cut` (Fair, Good, Very Good, Premium, Ideal)
* `colour` (J-D)
* `clarity` (I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF)
* `price` ($326 - $18,823 USD)
* Length `x` (3.73 - 10.74mm)
* Width `y` (3.68 - 10.54mm)
* Depth `z` (1.07 - 6.98mm)
* `table` (table width/y, 43 - 79%)
* `depth`( 2(z/x+y), 50.8 - 79.0%)

----------------------------------------
Exploatory data analysis revealed patterns and trends in the dataset.

(add images)

Figure 3 can assist in deciding the characteristics of a ‘perfect’ diamond. To choose a diamond to optimise beauty, it should be between 1 – 2ct. Diamonds outside of this range may be too small or large that either cut, clarity or colour are poor. Therefore, for the ‘perfect’ diamond, the cut type should ‘Ideal’-‘Very Good’, the diamond colour can be compromised down to grade G and the clarity compromised down to ‘VS2’. In this dataset there are 4438 diamonds that meet these criteria. The diamond with `ID 10006` achieves these conditions with 1.01 carat, ‘Premium’ cut, colour ‘E’ and clarity ‘VS2’ for the lowest price of $4706. This should be the diamond a buyer should consider purchasing since it encapsulates all desired characteristics to optimise beauty for the cheapest price.

Unsupervised and Supervised Machine Learning techniques were also applied to the dataset to predict the prices of diamonds.

<br> <i> See the [Diamonds Analysis Github Repository](https://github.com/sickotra/Diamonds_Analysis.git) for the full Jupyter Notebook report including the code used. </i>


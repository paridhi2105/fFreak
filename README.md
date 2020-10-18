# fFreak_recommender_system

recommender.py contains the code for recommending foods based on BMI value of user. User BMI is calculated from his/her weight and height data, and calorie requirement corresponding to the BMI is estimated.
The estimated calorie count is then compared with the calories present in different food items from the Food.csv dataset. The closest matched items are added in a list and showcased at the end.

Instructions for implementation :-
Run the recommender.py file.
Copy the URL that shows up(http://127.0.0.1:5000/) and paste it in the browser.
Concatenate /recommendation/height=<h>/weight=<w> to the URL.
(For example, the URL for height=1 and weight=21 is http://127.0.0.1:5000/recommendation/height=1/weight=21)
Hit enter and the page will display the BMI and recommended food list in json format.
Stop the script after returning to the python console.

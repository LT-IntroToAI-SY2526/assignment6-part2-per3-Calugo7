# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Square footage
2. Age
3. Bedrooms
4. Bathrooms

**Explanation:**
1. Bedrooms have the most impact because adding one bedroom to a house has more impact than adding 100 square feet or another feature. Cost 6130.59 to add a bedroom.
2. Bathrooms have the second most impact because of the same reason as the bedrooms but overall, bedrooms are valued more than bathrooms. Cost 6044.99 to add a bathroom.
3. Age has the third most impact because it adds or subtracts 901.61 to the cost of the house by adding a year.
4. Square footage has the least impact because adding a few hundred square feet in comparison to adding an entire bedroom or bathroom is valued less. It costs 120.09 to add a around 100 square feet.
---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"
Coefficients:
  SquareFeet: 120.09
  Bedrooms: 6130.59
  Bathrooms: 6044.99
  Age: -901.61
**Feature 1:**
Square Footage
The coeficient for Square footage increases the price by $120.09 for each increase in square footage.
**Feature 2:**
Age
The coeficient for Age decreases the price by $901.61 because it makes the house older which would decrease the price.
---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
R² Score: 0.9989
  → Model explains 99.89% of price variation
This tells me that the model was very accurate in calculating price for the house.


---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Floor materials

**Why it would help:**
Depending on what the floor is made from, the house can differ in price because of its quality.

**Feature 2:**
Basement

**Why it would help:**
This would be the same as bedrooms and bathrooms but more impactful because there would only be one basement.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I would not trust the model because there is not enough data given that reaches this amount for each feature.


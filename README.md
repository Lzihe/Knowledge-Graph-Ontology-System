# Pizza Shop Ontology Development
## Project Overview
This project involves the development of an ontology to enhance the customer experience in a pizza shop. The ontology covers various menu items such as pizza ingredients, dietary preferences, beverages, and desserts. The goal is to provide personalized recommendations and dietary alerts for customers, improving their dining experience.
## Key Features
1) 23 Classes: The ontology defines classes such as Pizza, PizzaTopping, Beverage, IceCream, etc.
2) 12 Object Properties: Includes properties such as hasSpiciness, pairsWith, and complements to model relationships between food items.
3) 10 Data Properties: These provide information on attributes such as allergen info, caloric content, spiciness levels (using the Scoville scale), and beverage volume.
4) Property Restrictions: The ontology defines restrictions like VegetarianPizza, which only allows cheese and vegetable toppings, and InterestingPizza, which has at least 3 toppings.
5) SPARQL Queries: The implementation includes SPARQL queries to retrieve relevant information from the ontology, such as pizzas with specific allergens, calorie values, or pizza topping combinations.
## Practical Applications
Personalized pizza recommendations based on customer dietary preferences.
Dynamic menu displays and ingredient tracking systems.
Insights into customer preferences for improved decision-making.
## Files Included
Ontology Graph: Contains the detailed structure of the ontology, class hierarchies, object and data properties.
OWL file: Contains the detailed structure of the ontology, class hierarchies, object and data properties, and data instance.
## How to Run
Load the ontology into a semantic reasoner or an ontology editor.
Customize the ontology for other food-related businesses or extend it to include more categories, such as supply chain data.

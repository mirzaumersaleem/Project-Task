# Recipe Builder

Create a drink recipe builder that allows the user to create drink recipes and view drink recipes.

Here are some abilities the interface you build should have:
- Create a new drink recipe from scratch
- Pick from a list of Actions and Supplies to create a new recipe
- Name and save that recipe (no need to save to server, just keep a local reference)
- View a list of all the recipes you have created
- Expand / click into any recipe to see its steps

A drink recipe combines a set of actions with a set of ingredients in a linear order.
An example recipes:

Pumpkin Spice Latte
1. Steam
2. Low-fat Milk
3. Add
4. Espresso Shot
5. Pumpkin Syrup
6. Sugar
7. Stir
8. Pour Into Cup

Don't worry about actually saving the recipes with a database or local storage. That's not necessary. We just want the front end and basic functionality here.

Feel free to use the following arrays in your code:

```
const ACTIONS = ['Add', 'Stir', 'Shake', 'Steam', 'Blend', 'Pour Into Cup'];

const SUPPLIES = [
  'Espresso Shot',
  'Decaf Espresso Shot',
  'Drip Coffee',
  'Cream',
  'Low-fat Milk',
  'Soy Milk',
  'Almond Milk',
  'Sugar',
  'Splenda',
  'Honey',
  'Caramel',
  'Whipped Cream',
  'Vanilla Syrup',
  'Caramel Syrup',
  'Pumpkin Syrup',
  'Chocolate Syrup',
  'Ice',
  'Water',
  'Sparkling Water'
  ];
```

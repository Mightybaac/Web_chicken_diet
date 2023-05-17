# Web_chicken_diet

# Chicken Diet Generator

This repository contains a Chicken Diet Generator application that generates a random diet plan for chickens based on their nutritional requirements.

## JavaScript Code

The JavaScript code (`chicken-diet-generator.js`) is responsible for generating a random chicken diet based on predefined food options and nutritional requirements. It uses the `Food` class to represent food items and their nutritional values. The `generateChickenDiet` function randomly selects foods and adjusts their weights to meet the protein, carbohydrate, fat, and vitamin requirements. The generated diet is returned as an object containing the weight of each food category. The `generateDiet` function is triggered by a button click in the HTML file and displays the daily diet on the web page.

## HTML File

The HTML file (`index.html`) provides the user interface for the Chicken Diet Generator. It includes a button that triggers the `generateDiet` function when clicked. The generated diet is displayed as a list of food groups and their weights. The HTML file also includes a script tag that embeds the JavaScript code.

## Usage

1. Clone the repository or download the JavaScript code (`chicken-diet-generator.js`) and the HTML file (`index.html`).
2. Open the `index.html` file in a web browser.
3. Click the "Generate Diet" button to generate a random chicken diet.
4. The generated diet will be displayed as a list of food groups and their weights.

Feel free to modify the food options, nutritional requirements, or other aspects of the code to suit your needs.

Enjoy creating random chicken diets with the Chicken Diet Generator!





## Customization

You can customize the food options and nutritional requirements by modifying the `foods` array and the variables in the `generateChickenDiet` function in the `chicken-diet-generator.js` file.

```javascript
// Modify the food options
const foods = [
  new Food("Corn", "Grains", { protein: 8, carbohydrates: 80, fats: 4, vitamins: 8 }),
  // Add or remove food options here
];

// Modify the nutritional requirements
const protein_requirement = 18;
const carbohydrate_requirement = 60;
const fat_requirement = 5;
const vitamin_requirement = 17;
```

## License

This project is licensed under the [MIT License](LICENSE).

---

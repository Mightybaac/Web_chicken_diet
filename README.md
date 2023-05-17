# Web_chicken_diet

---

This project is a chicken diet generator that generates a random chicken diet based on nutritional requirements and food options. The generator is implemented using HTML and JavaScript.

## Features

- Generate a random chicken diet based on nutritional requirements and available food options.
- Display the generated diet on the web page.

## Getting Started

To get started with the chicken diet generator, follow these steps:

1. Clone the repository or download the source code.
2. Open the `chicken_diet.html` file in a web browser.
3. Click the "Generate Diet" button to generate a random chicken diet.
4. The generated diet will be displayed below the button.

## Code Structure

- `chicken_diet.html`: The HTML file containing the web page structure and UI elements.
- `script.js`: The JavaScript file containing the logic for generating the chicken diet and updating the web page.

## Customization

You can customize the food options and nutritional requirements by modifying the `foods` array and the variables in the `generateChickenDiet` function in the `script.js` file.

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

# 40-40-20 Meal Plans

A phone-friendly meal plan app: 2,100 calories a day at 40% protein, 40% carbs and 20% fat, with a grocery list for every meal.

## What's inside

- **6 meal plans:** Crockpot, Road, No-Cook Power Bowls, Quick and Easy Recipes, Burritos, and Fish Crockpot Meals
- **A grocery list for every meal,** with checkboxes that remember what you've bought on each device
- **Search** across every recipe, food and nutrient
- **Your Fiber Takeaway** reference guide
- **Works offline** after the first visit, and can be added to a phone's home screen
- **Download:** the full collection as a Word file in `downloads/`

## Files

| File | What it does |
| --- | --- |
| `index.html` | The app (all content is inside this file) |
| `manifest.webmanifest` | App name, colors and icon for "Add to Home Screen" |
| `sw.js` | Lets the app open without a connection after the first visit |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Home screen icons (cartoon plate of food) |
| `icon.svg` | The icon artwork, in case you want to edit it |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |
| `downloads/40-40-20-Complete-Meal-Plan-Collection.docx` | The full collection as a Word file |

## Updating the app

Upload a new `index.html` over the old one. To make phones pick up the change right away, also change `meal-plans-v2` in `sw.js` to the next number (for example `meal-plans-v3`).

Talk with your doctor before adding supplements.

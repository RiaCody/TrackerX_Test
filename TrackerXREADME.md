# TrackerX

A personal tracker for fasting, daily check-ins, calories, water and weight. The daily clock uses your device’s local time. The eating window runs from 9 am to 3 pm and the fasting window runs from 3 pm to 9 am.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The complete app, including styles, JavaScript and 4,835 searchable Australian food entries. |
| `README.md` | Setup, data transfer and food data credits. |

## Move your logs

Records are stored in the browser for the address you use. To move existing records, open the old tracker, go to **My plan and data → Export backup**, then open the new GitHub Pages address and select **Import backup**. Import replaces records in the destination browser. Keep the JSON backup in your personal files, since it contains your logs.

## Run or edit locally

Open `index.html` in a browser. The file contains the app’s HTML, CSS, and JavaScript, and requires no build step or server code. Photo scanning downloads Tesseract.js at runtime and reads the photo in the browser. You can also paste text from iPhone Live Text or enter the label values manually.

## Food data credits

© Food Standards Australia New Zealand. Food names and energy values were extracted and combined from the [Australian Food Composition Database, Release 3](https://www.foodstandards.gov.au/science-data/food-nutrient-databases/afcd/data-files) and [AUSNUT 2023](https://www.foodstandards.gov.au/science-data/food-nutrient-databases/ausnut/data-files). The app converts kilojoules to calories for display.

The adapted AFCD data is distributed under the [FSANZ Data User Licence Agreement](https://www.foodstandards.gov.au/science-data/monitoringnutrients/afcd/datauserlicenceagreement). See also the [FSANZ copyright notice](https://www.foodstandards.gov.au/legal-policies/copyright).

Food composition figures can reflect averages from specific samples and collection periods. Nutrient levels vary between brands and batches due to season, sourcing, preparation, processing and calculation methods. This dataset is based on Australian foods and may be unsuitable for use in other countries. For a specific packaged product, use its nutrition label.

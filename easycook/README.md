# EasyCook

**EasyCook** is a web-based tool designed to assist individuals with ADHD in managing cooking recipes efficiently. By breaking down recipes into manageable steps, EasyCook helps users stay organized, track their progress, and estimate the time required for each task. The tool supports multiple languages and offers a clean, user-friendly interface to enhance productivity and minimize distractions.

Use the following GPT to create the receipes: [easycookgpt]https://chatgpt.com/g/g-677a345d2b588191b054dee975393ba2-easycookgpt
## Features

- **Step-by-Step Recipe Management:** Follow recipes one step at a time to avoid feeling overwhelmed.
- **JSON Import:** Easily import your own recipes using JSON files for personalized use.
- **Progress Tracking:** Visual indicators and time estimations help you stay on track.
- **Internationalization:** Supports multiple languages (French, English, German, Spanish) with easy switching via intuitive language selectors.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Sidebar for Ingredients and Utensils:** Organized view of all required ingredients and utensils.
- **Progress Modal:** View all steps and overall progress in a modal popup.
- **Local Storage:** Saves your language preference and recipe progress for a seamless experience across sessions.

## Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Safari, Edge).
- GitHub Pages enabled for hosting (optional but recommended for online access).

### Using EasyCook

1. **Open EasyCook:**
   - Navigate to the `easycook` folder in the repository.
   - Open `easycook.html` in your web browser.

2. **Import a Recipe:**
   - Click on the **"Choose File"** button to select your JSON file containing the recipe.
   - Click on **"Recharger la Recette"** (**"Reload Recipe"**) to load the imported recipe.

3. **Follow the Steps:**
   - Only one step is displayed at a time to help you focus.
   - Click **"Étape Terminée"** (**"Step Completed"**) or press the **Enter** key to mark a step as completed.
   - Double-click or double-tap anywhere on the screen to mark the next step as completed.

4. **Track Progress:**
   - View the total and remaining estimated time for your recipe.
   - Open the **Progression** (**"Progress"**) modal by clicking the **≡** button at the bottom-right corner to see all steps and your overall progress.

5. **Switch Languages:**
   - Click on the flag icons in the top-left corner to switch between supported languages (French, English, German, Spanish).

## Formatting Your Recipe JSON

Ensure your JSON file follows this structure to be compatible with EasyCook:

```json
{
  "name": "Lait d’Avoine Barista Enrichi – 5 Litres",
  "ingredients": [
    {
      "ingredient": "Flocons d'avoine fins",
      "quantity": "250g"
    },
    {
      "ingredient": "Flocons de soja",
      "quantity": "200g"
    },
    {
      "ingredient": "Lécithine de tournesol",
      "quantity": "5g"
    },
    {
      "ingredient": "Gomme xanthane",
      "quantity": "2,5g"
    },
    {
      "ingredient": "Pilule de Vitamine B12",
      "quantity": "1"
    },
    {
      "ingredient": "Sel",
      "quantity": "5 pincées"
    },
    {
      "ingredient": "Sirop d’érable (optionnel)",
      "quantity": "5 cuillères à soupe"
    },
    {
      "ingredient": "Eau froide",
      "quantity": "3,75 L"
    },
    {
      "ingredient": "Huile neutre",
      "quantity": "25 ml"
    },
    {
      "ingredient": "Lécithine de tournesol",
      "quantity": "1,25 g"
    },
    {
      "ingredient": "Gomme xanthane",
      "quantity": "0,625 g"
    },
    {
      "ingredient": "Huile neutre",
      "quantity": "75 ml"
    },
    {
      "ingredient": "Lécithine de tournesol",
      "quantity": "5 g"
    },
    {
      "ingredient": "Gomme xanthane",
      "quantity": "2,5 g"
    },
    {
      "ingredient": "Vitamine B12",
      "quantity": "31,25 µg"
    }
  ],
  "utensils": [
    {
      "utensil": "Grand saladier"
    },
    {
      "utensil": "Blender"
    },
    {
      "utensil": "Sac à lait végétal ou étamine"
    },
    {
      "utensil": "Récipients propres pour filtrer"
    },
    {
      "utensil": "Bouteilles ou bocaux hermétiques"
    },
    {
      "utensil": "Balance de cuisine"
    },
    {
      "utensil": "Cuillères à mesurer"
    },
    {
      "utensil": "Spatule ou fouet"
    },
    {
      "utensil": "Tasses ou verres pour les mesures"
    },
    {
      "utensil": "Planche à découper et râpe (si nécessaire)"
    },
    {
      "utensil": "Torchon propre"
    },
    {
      "utensil": "Pilon ou broyeur"
    }
  ],
  "steps": [
    {
      "step": "Prendre un grand saladier",
      "time": 5
    },
    {
      "step": "Prendre le blender",
      "time": 5
    },
    {
      "step": "Prendre un sac à lait végétal ou une étamine",
      "time": 5
    },
    {
      "step": "Prendre des récipients propres pour filtrer",
      "time": 5
    },
    {
      "step": "Prendre des bouteilles ou bocaux hermétiques",
      "time": 5
    },
    {
      "step": "Prendre une balance de cuisine",
      "time": 5
    },
    {
      "step": "Prendre des cuillères à mesurer",
      "time": 5
    },
    {
      "step": "Prendre une spatule ou un fouet",
      "time": 5
    },
    {
      "step": "Prendre des tasses ou verres pour les mesures",
      "time": 5
    },
    {
      "step": "Prendre une planche à découper et une râpe (si nécessaire)",
      "time": 10
    },
    {
      "step": "Prendre un torchon propre",
      "time": 5
    },
    {
      "step": "Nettoyer le grand saladier",
      "time": 10
    },
    {
      "step": "Nettoyer le blender",
      "time": 10
    },
    {
      "step": "Nettoyer le sac à lait végétal ou l'étamine",
      "time": 10
    },
    {
      "step": "Nettoyer les récipients de filtrage",
      "time": 10
    },
    {
      "step": "Nettoyer les bouteilles ou bocaux hermétiques",
      "time": 10
    },
    {
      "step": "Nettoyer la balance de cuisine",
      "time": 5
    },
    {
      "step": "Nettoyer les cuillères à mesurer",
      "time": 5
    },
    {
      "step": "Nettoyer la spatule ou le fouet",
      "time": 5
    },
    {
      "step": "Nettoyer les tasses ou verres de mesure",
      "time": 5
    },
    {
      "step": "Nettoyer la planche à découper et la râpe",
      "time": 10
    },
    {
      "step": "Essuyer le torchon propre",
      "time": 5
    },
    {
      "step": "Mesurer 250g de flocons d'avoine fins",
      "time": 10
    },
    {
      "step": "Mesurer 200g de flocons de soja",
      "time": 10
    },
    {
      "step": "Mesurer 5g de lécithine de tournesol",
      "time": 10
    },
    {
      "step": "Mesurer 2,5g de gomme xanthane",
      "time": 10
    },
    {
      "step": "Mesurer et broyer la pilule de Vitamine B12",
      "time": 15
    },
    {
      "step": "Mesurer 5 pincées de sel",
      "time": 5
    },
    {
      "step": "Mesurer 5 cuillères à soupe de sirop d’érable (optionnel)",
      "time": 10
    },
    {
      "step": "Nettoyer la surface de travail",
      "time": 5
    },
    {
      "step": "Prendre la pilule de vitamine B12",
      "time": 10
    },
    {
      "step": "Placer la pilule sur une surface propre",
      "time": 5
    },
    {
      "step": "Utiliser un pilon ou un broyeur pour broyer la pilule en poudre fine",
      "time": 20
    },
    {
      "step": "Transférer la poudre de vitamine B12 dans un petit récipient",
      "time": 5
    },
    {
      "step": "Placer les flocons d’avoine et de soja dans le grand saladier",
      "time": 5
    },
    {
      "step": "Ajouter 3,75 L d’eau froide dans le saladier",
      "time": 5
    },
    {
      "step": "Mélanger légèrement pour répartir les ingrédients",
      "time": 5
    },
    {
      "step": "Laisser tremper pendant 15 minutes",
      "time": 900
    },
    {
      "step": "Rincer abondamment les flocons sous l’eau froide",
      "time": 10
    },
    {
      "step": "Nettoyer le saladier après le trempage",
      "time": 10
    },
    {
      "step": "Diviser les flocons rincés en 2 ou 3 lots pour le mixage",
      "time": 5
    },
    {
      "step": "Placer le premier lot de flocons dans le blender",
      "time": 5
    },
    {
      "step": "Ajouter une portion d’eau froide dans le blender",
      "time": 5
    },
    {
      "step": "Ajouter 25 ml d’huile neutre",
      "time": 5
    },
    {
      "step": "Ajouter 1,25 g de lécithine de tournesol",
      "time": 5
    },
    {
      "step": "Ajouter 0,625 g de gomme xanthane",
      "time": 5
    },
    {
      "step": "Ajouter la poudre de Vitamine B12 broyée",
      "time": 15
    },
    {
      "step": "Mixer pendant 30 à 45 secondes",
      "time": 30
    },
    {
      "step": "Répéter le mixage pour chaque lot",
      "time": 5
    },
    {
      "step": "Placer un sac à lait végétal ou une étamine sur un grand récipient",
      "time": 5
    },
    {
      "step": "Verser le mélange mixé dans le sac à lait végétal pour filtrer",
      "time": 10
    },
    {
      "step": "Presser bien pour extraire tout le liquide",
      "time": 15
    },
    {
      "step": "Répéter le filtrage pour chaque lot",
      "time": 5
    },
    {
      "step": "Combiner tous les liquides filtrés dans un grand récipient",
      "time": 5
    },
    {
      "step": "Ajouter 75 ml d’huile neutre",
      "time": 5
    },
    {
      "step": "Ajouter 5 g de lécithine de tournesol",
      "time": 5
    },
    {
      "step": "Ajouter 2,5 g de gomme xanthane",
      "time": 5
    },
    {
      "step": "Ajouter 31,25 µg de vitamine B12",
      "time": 5
    },
    {
      "step": "Mélanger énergiquement pour homogénéiser",
      "time": 15
    },
    {
      "step": "Goûter et ajuster le sel et l’édulcorant si nécessaire",
      "time": 15
    },
    {
      "step": "Verser le lait d’avoine dans des bouteilles ou bocaux hermétiques",
      "time": 10
    },
    {
      "step": "Étiqueter les bouteilles avec la date de préparation",
      "time": 5
    },
    {
      "step": "Réfrigérer immédiatement",
      "time": 10
    },
    {
      "step": "Nettoyer et ranger le blender",
      "time": 10
    },
    {
      "step": "Nettoyer et ranger le sac à lait végétal ou l'étamine",
      "time": 10
    },
    {
      "step": "Nettoyer et ranger les récipients de filtrage",
      "time": 10
    },
    {
      "step": "Nettoyer et ranger les bouteilles ou bocaux hermétiques",
      "time": 10
    },
    {
      "step": "Nettoyer et ranger la balance de cuisine",
      "time": 5
    },
    {
      "step": "Nettoyer et ranger les cuillères à mesurer",
      "time": 5
    },
    {
      "step": "Nettoyer et ranger la spatule ou le fouet",
      "time": 5
    },
    {
      "step": "Nettoyer et ranger les tasses ou verres de mesure",
      "time": 5
    },
    {
      "step": "Nettoyer et ranger la planche à découper et la râpe",
      "time": 10
    },
    {
      "step": "Placer le torchon propre à sa place",
      "time": 5
    },
    {
      "step": "Essuyer la surface de travail après la préparation",
      "time": 5
    }
  ]
}

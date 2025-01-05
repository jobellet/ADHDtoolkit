### 3.2 `easycook/README.md`

This README provides specific information about the **EasyCook** tool, including its purpose, features, usage instructions, and any other relevant details.

#### **Content for `easycook/README.md`:**

```markdown
# EasyCook

**EasyCook** is a web-based tool designed to help individuals with ADHD manage cooking recipes efficiently. It breaks down recipes into manageable steps, allowing users to track their progress and estimate time effectively.

## Features

- **Step-by-Step Recipe Management:** Follow recipes one step at a time to avoid feeling overwhelmed.
- **CSV/TSV Import:** Import your own recipes or task lists in CSV/TSV format for personalized use.
- **Progress Tracking:** Visual indicators and time estimations help you stay on track.
- **Internationalization:** Supports multiple languages for broader accessibility.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Getting Started

### Using EasyCook

1. **Open EasyCook:**
   - Navigate to the `easycook` folder in the repository.
   - Open `easycook.html` in your web browser.

2. **Import a Recipe:**
   - Click on the **"Choose File"** button to select your CSV/TSV file containing the recipe steps.
   - Click on **"Reload Recipe"** to load the imported recipe.

3. **Follow the Steps:**
   - Only one step is displayed at a time to help you focus.
   - Click **"Étape Terminée"** or press the **Enter** key to mark a step as completed.
   - Double-click or double-tap anywhere on the screen to mark the next step as completed.

4. **Track Progress:**
   - View the total and remaining estimated time for your recipe.
   - Open the **Progression** modal by clicking the **≡** button at the bottom-right corner to see all steps and your overall progress.

## Formatting Your Recipe CSV/TSV

Ensure your CSV/TSV file follows this structure:

```csv
Recette,EasyCook – Example Recipe
Chop vegetables,300
Heat oil in pan,60
Add vegetables,120
Stir-fry until tender,180
Serve hot,30

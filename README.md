# Recipe Book

**Project: Recipe Book**

*Description*: Create a recipe book application where users can add, edit, and delete recipes.

**Step-by-Step Instructions**:
1. Set up a React app.
2. Create a component called "RecipeBook."
3. Maintain an array of recipes in the component's state.
4. Display a list of recipes.
5. Implement a form to add new recipes.
6. Add buttons for editing and deleting recipes.
7. Create event handlers for these actions.
8. Make sure you style your App

**CSS code**

```
/* RecipeBook.css */
.recipe-book {
  max-width: 800px;
  margin: 0 auto;
}

.recipe {
  border: 1px solid #ccc;
  padding: 1rem;
  margin: 1rem 0;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.edit-button, .delete-button {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 0.3rem 0.5rem;
  margin-right: 0.5rem;
  cursor: pointer;
}

.edit-button:hover, .delete-button:hover {
  background-color: #0056b3;
}
```

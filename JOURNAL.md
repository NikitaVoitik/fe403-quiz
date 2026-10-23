# Journal

A running record for the whole course. Add new entries at the bottom.

---

## Module 1 · Interfaces

### Discovery

Problem: https://cjb-labs.github.io/knowledge-base/hsfe403/module1/interfaces/discovery/reference/

Here is a recipe program. When you run it, it crashes partway through.

```js
const recipes = [
  { name: "Pancakes", ingredients: ["flour", "milk"] },
  { name: "Soup", ingridients: ["carrot", "stock"] },
  { name: 7, ingredients: ["water", "salt"] },
]

for (const recipe of recipes) {
  console.log(recipe.name)
  console.log(recipe.ingredients.join(", "))
}
```

**1. Why does it crash? Is anything else wrong with this data that the program doesn't tell you about? How would you fix it?**



**2. Now suppose this list grows to 5,000 recipes written by ten different people. You can't read them all. How would you make sure every recipe is shaped correctly before the program runs?**



### After class

**Sticking points (resolved?):**

**How I feel about today's content (Solid / Shaky / Lost):**

**What earlier content did it lean on? Did those connections hold up?**

### After homework

**Did I resolve yesterday's struggles?**


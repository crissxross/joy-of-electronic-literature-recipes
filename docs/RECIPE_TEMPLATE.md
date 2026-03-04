---
title: Your Recipe Title Here
chef: Your Name (or Names)
abstract: One clear sentence summarizing what this recipe does and teaches (max 25 words).
description: >
  A 250-word summary that explains what the recipe is, what it teaches,
  the context and background, and how the approach works. This will appear
  in the published book, so make it informative but concise.

  You can write multiple paragraphs by leaving blank lines between them.
  Focus on: (1) what your recipe is, (2) what it teaches, (3) why it matters
  (artistic/literary context), and (4) how it works (brief overview).

  Keep this section to approximately 250 words. The full background and
  details go in the Body sections below the YAML.
genres:
  - Genre Name
  - Another Genre
custom_genres:
  - Custom Genre (optional)
difficulty_pans: 2
yields: >
  A brief description (max 50 words) of what the reader will experience
  or create when they follow this recipe.
github_link: https://your-project-url.com
---

# **[Recipe Title] - a recipe**

**[Your Name]** [role/title if desired]

**Class of E-lit:** [genre/category]

**Dish:** [metaphorical description of the outcome]

**Required ingredients:** [List tools, software, materials needed]

**Preparation and cooking time:** [estimated time]

**Number of servings:** [how often this can be practiced, or audience size]

**Rating: 🍳 [Easy/Medium/Hard with 1-4 pan emojis]**

## **From the Chef**

[A personal note from you about why you created this recipe, what inspired it,
your relationship to the work, or what you hope readers will gain. This is your
voice speaking directly to the reader about the recipe's origins and significance.]

## **Background**

[Provide context for your recipe. This might include:
- The artistic, literary, or technical tradition it comes from
- Problems or questions it addresses
- Historical or contemporary context
- Theoretical frameworks that inform it
- Why this approach or technique matters
- How it fits into electronic literature practices]

## **Samples before you cook**

[Provide links to examples of works created with this recipe, or demonstrations
of the technique in action. Include:
- Links to finished works
- Demo projects
- Video demonstrations
- Screenshots or images
- Interactive examples readers can try]

Example:
- [Project Name](https://example.com) - Brief description
- [Another Example](https://example.com) - Brief description

## **Additional reading**

[Scholarly articles, tutorials, documentation, or other resources that provide
deeper context or instruction. Format as a bibliography:]

Author Name. "Article or Book Title." *Publication*, Year. [URL](https://example.com)

Author Name. *Book Title*. Publisher, Year.

## **Recipe**

[If you didn't include "From the Chef" at the top, you can place it here as
a subsection under Recipe]

### **Ingredients**

[List all required materials, tools, software, accounts, or prerequisites:]

- **Software/Platform:** [name and version if relevant]
- **Programming language:** [if applicable]
- **Libraries/frameworks:** [specific versions if important]
- **Hardware:** [computer specs, devices, sensors, etc.]
- **Accounts:** [any services that require signup]
- **Data/files:** [any datasets, images, text files needed]
- **Skills:** [prerequisite knowledge helpful to have]

### **Directions**

[Step-by-step instructions for following your recipe. Number or bullet the steps.
Be specific and clear. Include:]

1. **[Step name/phase]:** Description of what to do
2. **[Next step]:** More details
3. **[Continue...]:** Keep going

[You can break this into subsections if your recipe has distinct phases:]

#### Phase 1: [Setup/Preparation]
1. First step
2. Second step

#### Phase 2: [Main Cooking]
1. Next phase steps
2. Continue

#### Phase 3: [Finishing/Presentation]
1. Final steps
2. How to complete

### **Starter Code** *(if applicable)*

[If your recipe involves programming or markup, include starter code that readers
can build from. Use proper code blocks with language specification:]

```python
# Example Python code
def starter_function():
    """This is a starting point for your recipe."""
    print("Hello, electronic literature!")
```

```html
<!-- Example HTML structure -->
<!DOCTYPE html>
<html>
<head>
    <title>Recipe Title</title>
</head>
<body>
    <h1>Your work starts here</h1>
</body>
</html>
```

```javascript
// Example JavaScript
function createWork() {
    // Your code here
}
```

[Include comments explaining what the code does and where readers should customize it]

### **Variations**

[Describe alternative approaches, extensions, or modifications of the basic recipe.
This might include:]

**Variation 1: [Name]**

[Description of how to modify the recipe for different effects or purposes]

**Variation 2: [Name]**

[Another variation]

**Extensions:**

[Ideas for taking the recipe further, adding complexity, or combining with other techniques]

**Simplifications:**

[Ways to make the recipe easier for beginners or when time/resources are limited]

## **Related Recipes**

[Link to other recipes in this cookbook or elsewhere that connect to yours:]

- **[Recipe Name]** - [How it relates to yours]
- **[Another Recipe]** - [Connection or contrast]

[If referencing recipes in this cookbook, use relative links:]
- See [Recipe Title](recipe-slug.md) for [related technique]

## **Notes**

[Any additional notes, caveats, troubleshooting tips, or acknowledgments.
This might include:]

- Known issues or limitations
- Tips for success
- Common mistakes to avoid
- Acknowledgments of collaborators or inspirations
- Credits for tools or techniques
- Future directions or open questions

## **Works Cited**

[Full bibliography in a consistent citation format. Include all sources referenced
in the recipe, including those already listed in "Additional reading":]

Author, Name. "Title of Article." *Journal/Publication Name*, vol. X, no. Y, Year, pp. XX-XX. DOI or URL.

Author, Name. *Title of Book*. Publisher, Year.

Author, Name. *Title of Website or Project*. Year. URL. Accessed Date.

---

## **Template Usage Notes** *(Remove this section when writing your recipe)*

### **Section Guidelines:**

- **Required sections:** YAML frontmatter, Recipe (with Ingredients and Directions)
- **Recommended sections:** Background, Samples before you cook, From the Chef
- **Optional sections:** Starter Code, Variations, Related Recipes, Notes, Works Cited, Additional reading

### **Section Order:**

The order above follows common cookbook conventions, but you can adjust if it serves your recipe better. The key is clarity and consistency.

### **YAML Field Constraints:**

- `title`: Max 10 words
- `chef`: Max 5 words (names only, no titles)
- `abstract`: Max 25 words (one sentence)
- `description`: Max 250 words (this appears in the book)
- `yields`: Max 50 words
- `difficulty_pans`: Integer 1-4 (matches number of 🍳 emojis)
- `genres`: Use official genre list
- `github_link`: Valid URL (project, demo, or GitHub repository)

### **Writing Tips:**

1. **Be specific:** Instead of "add text," say "add a paragraph of at least 50 words"
2. **Test your recipe:** Have someone else try following it
3. **Use examples:** Show, don't just tell
4. **Explain why:** Not just what to do, but why it matters
5. **Consider your audience:** Balance accessibility with depth

### **Code Formatting:**

Always specify the language for syntax highlighting:
- \`\`\`python for Python
- \`\`\`javascript for JavaScript
- \`\`\`html for HTML
- \`\`\`css for CSS
- \`\`\`inform7 for Inform 7
- \`\`\`bash for shell commands

### **Images:**

If you include images, reference them like:
```markdown
![Alt text description](path/to/image.png)
```

Or if using external links:
```markdown
![Alt text](https://example.com/image.png)
```

### **Internal Links:**

Reference other recipes in this cookbook using relative paths:
```markdown
See [Recipe Title](recipe-filename.md) for more details.
```

### **External Links:**

Use descriptive link text:
```markdown
[Project Website](https://example.com)
```

Not:
```markdown
Click [here](https://example.com)
```

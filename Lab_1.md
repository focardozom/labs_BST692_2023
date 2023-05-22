##  Labs BST692: TITANIC dataset

### Lab1

**Objective:**

Build a shiny::UI (User Interface). 

---

**Step 1**

Clone this GitHub repository:

https://github.com/focardozom/labs_BST692_2023

**Step 2**

Create a `.md` file (go to File > New File > Markdown File).  
**Note that it is a Markdown file, not an Rmarkdown file.**

**Step 3**

Save the `.md` file. (Name it 'page1')

**Step 4**

Open this link [webpage](https://rpubs.com/focardozom2/titatinc_bst692). 

**Step 5**

Your task is to reproduce the webpage in your markdown file (page1.md). 

For example:

This code: `# Titanic: Tragedy in the Atlantic` 

Produces this output:

# Titanic: Tragedy in the Atlantic

And this code: `* Titanic: Tragedy in the Atlantic` 

Produces this output:

* Titanic: Tragedy in the Atlantic

You can use the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/) and [RMarkdown Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) to see style options.

The image is located in your PoistCloud ('titanic.png')

Save the `.md` file.

**Step 6**

In your project, create a new R script file (go to File > New File > R Script).

Type the following snippet `shinyap` in the new file (Remember to press the tab key before you finish typing to call the snippet). 

**Step 7**

Select everything and run your code. You can use `Command + a`, then `Command + Return` to execute it like a pro.

**Step 8**

**Congratulations**, you have created a Shiny app. 

Save your file and name it `app`. 

**Step 9**

In your `.app`, include the `.md` file in the UI object (everything inside the `fluidPage()` will be part of your user interface). The `includeMarkdown()` function will read your `.md` and deploy it. For example, use `includeMarkdown("???")`.

**Step 10** 

Click the `Run app` button to see the magic unfold.




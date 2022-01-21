## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/cshankle/AdvancedDataScience/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cshankle/AdvancedDataScience/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
# Sort and Custom Sort - Caleb Shankle
## What Is Sorting?
Sort is a tool that allows the user to rearrange their data in excel. The user can choose how they want to arrange their data, whether it is alphabetically and numerically or by using their own categories. Common examples of categories include the days of the week, or by which color the cell is highlighted as. The user is also able to decide which column the data is sorted by. When setting the parameters, the user also chooses which column to sort by. The data in the column is used to decide where in the sheet all of the data goes, so even if a cell would be first if sorted by its column, it might be last if the column that is being used in the sort would be last.
## Why Should We Sort?
  Having the sort tool makes life a lot easier for the person who needs to use spreadsheet. There are always going to be different ways to arrange data and depending on the context, you might need to look at the data arranged differently multiple times on one sheet. For example, we use spreadsheets to keep track of who gets packages and what day they arrive at the Package Center. When we had paper copies of the manifest, it was helpful to sort by alphabetical order, since we had to manually find each person's name. Now that the manifest is digital it is more useful to sort by date, since all of the packages are on one spreadsheet. By sorting by date, we know which packages got here most recently and we don't have to waste time. Another instance where the sort tool is useful is in big data projects such as the highschool counselor project that the Office of Admission is doing. We wanted to sort all of the high schools in Maryland by which county they are in. This is pretty easy, we can just use the sort tool on the county column. However, this project took a **very** long time, so it would be more useful to sort by counties that we are more likely to have students coming from. In this case Montgomery county and Howard County are both counties where we pull a lot of students from. By making a custom sort that prioritizes those two counties, we could focus on urgent counties first. Remembering the time we spent in 201 working on sorting algorithms shows why it is so helpful to have a tool to do the sorting rather than coding it ourselves. Because we have the sort tool, we are able to turn a process that involves a lot of code into a few clicks of a button. 
## How to Sort:
1. Add Your Data.
  -In this case, we will look at a small dataset of what different countries call shaved ice.
  ![alt text](Step 1.png)
2. Click Sort.
  - Sort is found in the data tool bar.
3. Choose whether your data has headers.
  - This option will be found in the top right corner of the window.
  - This is important for if your columns are titled. By clicking this check box, you won't include the top two cells in the dataset.
4. Choose which column to sort by.
  - This will be found in the leftmost dropdown menu.
5. Choose how you want to sort.
  - You can choose A-Z, Z-A, or Custom List
6. Once you choose how to sort, hit ok and the data will sort!

### How to make a custom list
1. click the custom list option from the order menu. 
2. This will open a new window where you can make a list to sort on
3. In the right box (titled List Entries), you can enter the items that the list should be sorted by. <br>
  a. To do this, you enter one term then press enter to enter the next term.


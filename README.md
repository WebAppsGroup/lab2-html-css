<div align="center">
<img height=150px src="https://poloinnovazioneict.org/wp-content/uploads/2020/02/politecnico_blu.png" />
</div>

# Web Applications I 2020/21 - LAB #2

<p align="center">
 <img alt="HTML" src="https://img.shields.io/badge/languages-HTML,CSS-orange"/>
 <img alt="Framework" src="https://img.shields.io/badge/Bootstrap-v4.6-blue"/>
</p>

This is the transcription of the [original pdf text](https://github.com/polito-WA1-AW1-2021/course-materials/blob/main/labs/L02-getting-started-html-css.pdf) of the second laboratory of the course of Web Applications I at Politecnico di Torino. 

## A GUI for the TODO manager

Realize a “static” webpage (using Bootstrap, see the “hints” below) that can serve as the user interface for managing a list of tasks (i.e., a “task manager”). A task is represented by the same information as in the previous lab (description, important, private, deadline). Since we are not using any database in this lab, (statically) populate the webpage with a few dummy tasks (4-5). A possible result is shown at the end of the document.

The webpage starts with a navigation bar, which includes a) a logo for the todo manager, b) a search box, and c) an icon representing the logged-in user.

The rest of the webpage is split in two columns: a left sidebar (around 1/3 of the page width) and the main content.

The left sidebar contains some filters: “All”, “Important”, “Today”, “Next 7 Days”, “Private”. In the image, the “All” filter is the currently active one. Each filter conceptually refers to one of the task properties. For instance, the “Important” filter will show all the “important” tasks, while the “Today” filter will list all the tasks whose deadline is today (at any hour). You are not requested to implement those functions in this lab, the webpage should show the name of the filters, only.

The main content shows the title of the filter (“All” in our case), the relevant inserted tasks, and an element to create a new task.

In particular, each task shows the following information, in order and horizontally:

* an element to show whether the task is completed or not; this element should be clickable to complete/uncomplete a task
* the description of the task; if the task is important, the description should be red
* an icon if the task is accessible to other users (i.e., not private)
* the deadline, in textual form (e.g., “today at 2:00 PM”), if any.

The element for creating a new task should be represented by the “+” symbol and be positioned in the right bottom corner of the page. Finally, the lab should consist of a single HTML page and one (or more) CSS files.

**Optional:** if the webpage is displayed on a smartphone, the left sidebar should collapse (disappear), and all the other information should be re-organized to fit the screen width (e.g., as in the second screenshot below).

**Hints**

```
1. Use Bootstrap 4.6 and its components to create the webpage: https://getbootstrap.com
2. If you need to personalize the style of your page, you may create a separate CSS file.
```












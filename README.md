# Overview

* **Task: **You will be working with your group. You will be using what you have learned about FlexBox and Grid to create a responsive webpage.
* **Purpose: **To give you experience in using Flexbox and Grid techniques.
* **Instructor: **Will be available to help occasionally in this forum and will be assessing your posts.

## Instructions

1. The file group_week06.html has already been created for you and contains 4 <section> elements. You will write CSS in a file called group_week06.css to make each of the four sections responsive using FlexBox and/or Grid. In the context of the assignment, responsive means the sections will have a certain appearance at three screen sizes:
   * Small: less than 600px wide.
   * Medium: 600px or greater wide.
   * Large: 1200px or greater wide.
2. Download the [group_week06.zip](https://byui.instructure.com/courses/127272/files/49546180/download?wrap=1 "group_week06.zip").
3. The file group_week06.html is the webpage. You must not alter the contents of this file.
4. The file group_week06.css is where all of your work for this assignment must go.
5. The download zip file contains three .png files: small_500px.png, medium_1000px.png, and large_1300px.png. These three screenshots show what the assignment might look like if your browser window is 500, 1000, or 1300 pixels wide. Due to the responsive nature of FlexBox and CSS Grid the web page will look different as things grow and shrink at other pixel sizes. Depending on what browser you are using, it might look a bit different that the screenshots even at 500, 1000, or 1300 pixels wide. Nevertheless this will give you an idea of what the finished assignment should look like.
6. Section 1 has the id **flex_first**. You must only use FlexBox for this section.
   1. Center the section horizontally on the page and move the section 1rem down from the top of the page.
   2. Center the <ul> with the class **center_list** both horizontally and vertically within the section.
   3. Both the section and the <ul> must remain centered at all screen sizes.
7. Section 2 has the id **flex_second**. You must only use FlexBox for this section.
   1. Place the form labels and input elements in a single column with the form labels and input elements stacked on top of each other.
   2. The individual radio buttons and checkboxes must be stacked on top of each other.
8. Section 3 has the id **grid_first**. You must only use CSS Grid for this section. At all sizes, the articles must have a 1rem gap between each other.
   1. Small size: Place the articles in a single column.
   2. Medium size: Place the articles in two columns of equal widths.
   3. Large size: Place the articles in four columns of equal widths.
9. Section 4 has the id **grid_second**. You must only use CSS Grid for the main layout, but you must only use FlexBox for laying out the contents of box9. At all sizes, the divs must have a 1rem gap between each other. At all sizes the divs must be a minimum of 100px tall.
   1. Small size:
      1. Place the divs in a single column.
      2. The contents of box9 must be placed in a column so that the items are spaced evenly and stretched to fit box9.
   2. Medium size:
      1. Place the divs in 2 columns of equal widths.
      2. Box1 must span 2 columns and take up 2 rows.
      3. The contents of box9 must be placed in a row, centered within box9, and allowed to wrap.
   3. Large size:
      1. Place the divs in 3 columns of equal widths.
      2. Box1 must span 3 columns and take up 2 rows.
      3. The contents of box9 must still be placed in a row and centered within box9, but cannot wrap.
10. Upload group_week06.html and group_week06.css to the public_html directory of one of the group members. Please be certain they are named correctly and the permissions are set to 755.
11. Using Canvas Inbox, send your instructor a message with:
    1. The group’s number (e.g., Group 3).
    2. The group member’s Linux Lab account where the files are located (e.g., The files are in the public_html directory of Lucy Pevensie).
    3. The Group Member Participation Scores. (If a student did not participate, they receive a score of 0. The scores of the rest of the group members should add up to 100.)

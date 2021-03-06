# 432 Class 05: 2018-01-30

### Key Materials

[The slides](https://github.com/THOMASELOVE/432-2018/tree/master/slides/class05), and the [audio files](https://github.com/THOMASELOVE/432-2018/tree/master/slides/class05) will be posted above when they become available.

In today's class, we'll focus on model selection and validation.

## Announcements Before Class 05

1. R Studio version 1.1.419 is now [available for download](https://www.rstudio.com/products/rstudio/download/#download). You probably want to do so.

2. Homework 1 and Grading, in general. 
    - The [Homework 1 Answer Sketch](https://github.com/THOMASELOVE/432-2018/blob/master/assignments/hw1/README.md) is now available in R Markdown, HTML and PDF.
    - The [Grading Rubric](https://github.com/THOMASELOVE/432-2018/blob/master/assignments/hw1/README.md) is also available.
    - Once Homework 1 has been graded, we'll post grades and a few TA comments, in a list, with students identified by HW ID number.
        + By the time Class 5 begins, you should have received an email from Professor Love with your HW ID number.
    - Should you have questions about the Homework's concepts or other **non-grading** issues, please contact us at 431-help or in office hours.
        + The TAs are available to help you understand an appropriate way to tackle each problem, and also to help you understand potential concerns related to your answer.
    - But if you have questions about **grading**, you'll submit those to Dr. Love for all homework assignments, in a batch.
        + Dr. Love takes care of regrading requests in a batch at the end of the term. Fill out [this Google Form](https://goo.gl/forms/aQNPnlAWGIn72a7h1) before noon on Wednesday 2018-05-09 to request a regrade of any homework assignment.
        + If you've already got an A in the course without any additional credit on homework assignments, then Dr. Love won't bother to review your regrading requests in May, but if you don't have an A yet, he will do so very carefully after noon on 2018-05-09.
        + Please **don't** expect the TAs to address grading issues: Dr. Love will do that, at the end of the semester.

3. Here's a little progress report on course materials.
    1. We've corrected typos in Chapters 3, 4, 6 and 7 of the [Course Notes](https://thomaselove.github.io/432-notes/), all found by students. Thanks!
    2. There were some minor additions (hints, really) to [Homework 2](https://github.com/THOMASELOVE/432-2018/blob/master/assignments/hw2/README.md) this weekend.
    3. [Homework 3](https://github.com/THOMASELOVE/432-2018/blob/master/assignments/hw3/README.md) and [Homework 4](https://github.com/THOMASELOVE/432-2018/blob/master/assignments/hw4/README.md) and [Homework 5](https://github.com/THOMASELOVE/432-2018/blob/master/assignments/hw5/README.md) are now available, too. So you're set for HW through February.

4. Deadline Questions? Check the [SCHEDULE](https://github.com/THOMASELOVE/432-2018/blob/master/SCHEDULE.md), please. 

5. Here's a hint for question 3 in [Homework 2](https://github.com/THOMASELOVE/432-2018/tree/master/assignments/hw2), which I've added [to the assignment](https://github.com/THOMASELOVE/432-2018/tree/master/assignments/hw2) as well. 
    - R may well warn you about something like "singularities" in your output, but we'd like a clearer answer than that from you. 
    - To obtain it, look at the output, and then look at your data. 
    - Looking at the output is easy-ish. To look at the data, consider specifically the value of counting things. 
    - In particular, ask yourself questions like "How many people fall into the levels of the product term I've created?" or "What if I build a table, say with race in the rows and insurance in the columns - how many people fall into each cell of that table?" as a way to figure out what the real problem is in terms more understandable than R's warning message.



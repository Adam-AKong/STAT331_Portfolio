---
editor_options: 
  markdown: 
    wrap: 72
---

For the revisions included in your Portfolio, to help me understand the
nature of your revisions, please denote somehow the feedback I provided
you (e.g., boldface, italics, colored text) before your revisions.

{r wd-5-right} \# Week 4: Lab 4 Q 5

NOTE: I would use a semi_join here after the resubmissions. But because
I did not use a resubmissions for a correct solution for this learning
target I can't use a right_join I have in the corrected challenge 4. I
could just revere the order of the combined_data set to be the right
join instead by flipping cali_avocados and HPI_index.

*Q5 - G*

*You need to find the top 5 METRO AREAS (not regions) and their names in
step 1. Then you can use these names (stored in a dataframe) to filter
the regions rather than typing out the names a second time.*

*Q5 - G*

*A right_join() assumes you want to keep the observations in the
topFiveRegions dataframe. Do you want to keep these means for your
plot?*

*Q5 - G*

*A right join is not what you want here!*

{r wd-4-factor} {r wd-7-long} \# Week 4: Lab 4 Q 7 (Revised)

*Q7 - G*

*You need to find the mean sales for each city, type, and size
**before** plotting!*

*Q7 - S*

*Yes! Great job! Do you need to arrange() the means before you plot?*

{r dvs-2-cat} {r dvs-2-2} \# Week 5: Lab 5 Part 2 Q 3 (Revised)

*Q3 - S*

*This is a great place for `fct_reorder2()`!*

{r dvs-5-2} {r dvs-6-1} \# Week 9: Lab 9 Q 1 (Revised)

*Q1- G*

*I don't see a table...*

*Nice work using the built-in argument to pivot_wider() to fill the NA
values with 0s!*

Note: Just had to call function to read the table. Revised the rest of
Lab 9.

{r wd-5-left}
# Week 4: Challenge 4 (Revised)

If you specify that year should be used to join the datasets together, you won't end up with year.x and year.y !

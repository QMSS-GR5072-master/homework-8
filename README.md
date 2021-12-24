# homework 8 - build a REST API

## Instructions

1. Your final document should be an `.md` file (GitHub-flavored markdown) knitted from an R Markdown file. Create a folder called `/homework` where you will add the `.md` file, and a folder called `/src` where you will  place the `.Rmd` file and any other scripts you used to create the reports.

  In answering each of the questions for the assignment please include
  - the question as a header in your R Markdown report,
  - the raw code that you used to generate any tables, and
  - the top ten rows of the resulting `tibble`. (Do not include more than ten rows for any table in your report).

2. when you are done with your final `push` to this repo, submit the link to this repo on Canvas. (Make sure to `commit` your progress throughout the day, and `push` your progress at the end of each day.)


### Assignment items `[100 pts]`

Using data from the NYCHealth Github [repo](https://github.com/nychealth/coronavirus-data/tree/master/trends), build a REST API that accepts query parameters that can return meaningful data. [We returned the covid positivity weekly rate by zipcode in our class tutorial. Add or change the returned data and successfully deploy your REST API.]

1. [`30 pts`] Describe how to use your API to a potential end user.

2. [`30 pts`] Describe why your API might be useful if you were to share it with the world.

3. [`40 pts`] Discuss how you might improve your API if you had more time.

Be sure to use R code to make a GET request to your API to demonstrate to use that it actually works! (Consult the [`httr`](https://cran.r-project.org/web/packages/httr/vignettes/quickstart.html) package for a reminder on how to do it.)

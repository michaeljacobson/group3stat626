Just a quick README to get everyone started. Github is simply a development
platform for Git which is a 'revision control system it is aimed at speed,
data integrity, and support for distributed, non-linear workflows.' It's a
space where we can collaborate on this project. Especially with R code, etc,
we can standardize our work for sharing and code review.

# Getting Started with Git and RStudio

Here is a quick (and to the point) guide to Git: http://rogerdudler.github.io/git-guide/.
We could spend days or weeks talking about the finer points of Git and GitHub, but
that is the general idea.

RStudio integrates with Git repos very well. RStudio will track all of your changes
in the *Git* tab. From there you can Commit and Push changes to the remote repository
in GitHub. If you don't already have RStudio, you can get the most recent release here:
https://www.rstudio.com/products/RStudio/#Desktop.

In a perfect world, we would all create our own working branches from the Master branch 
(keeping them updated regularly), and then create pull requests where we can
code review and collaborate. From there you can *merge* changes to the master. Regardless,
Git / GitHub allows for good versioning and change tracking even if we only work in the Master branch.

# Loading Project & Data

Start by creating a "New Project" in RStudio. (File > New Project). Select "Version
Control", then "Git", and then copy/paste the GitHub URL. You will need a GitHub
username and password, and that's good to have even after this cource is complete.

Once you create the project, load the Rproject by double clicking on *group3stat626.Rproj*.

Nina's complete dataset is already saved within the project. All columns are
formatted to the correct data types. You can load the data simply by executing 
the following line in R:

```
data(dta)
```

From there you can create new R functions (saving them in the R directory), or
creating new pipelines or markdown documents that we'll eventually integrate into
reports and / or presentations.




  
  

# Repository Guidelines

**PLEASE READ BEFORE CREATING NEW REPOS**

This file documents current guidelines for naming new repositories. Following these guidelines will help keep things organized.

Beyond having a consistent set of conventions for organizing repositories, there may not be a specific reason for a given guideline. If for whatever reason you'd like to discuss making a change to these guidelines, please open an issue within this repository.

If you have any other questions, please contact Steve <smatsumoto@olin.edu>.

## Course Repositories

If creating a repository for a course, we recommend that you create a "development version" of your course repository that you use to track changes to the course materials, etc. over time, as well as a "semester version" of the repository that contains files that you distribute to students during a given semester.

The development version of your course repository should simply be titled with the name of the course. Titles should be in all lowercase, with words separated by hyphens. It does not matter whether you use the long form of the course title (e.g., `software-design`) or the short form (e.g., `softdes`) as long as you are consistent.

Examples of acceptable course repository titles:

* `softdes`
* `isim`
* `teaching-and-learning`
* `qea-1a`

Examples of non-ideal course repository titles:

* `SoftSys` (mixes uppercase and lowercase letters)
* `mspw` (unclear what the acronym stands for, even if the course name abbreviates to the title)
* `mechanicalprototyping` (uses full course title without hyphens to separate words)

For semester repositories, you should use the same title as you would for the development version of the course repository, but add the four-digit year and a two-digit semester code to the end of the course title. The current semester codes are as follows:

* `01`: Spring
* `02`: Summer
* `03`: Fall
* `04`: Winter (likely will be rarely used)

Any other two-digit code can be used for whatever you wish, but try to be consistent.

As an example, the semester repository title of SoftDes Fall 2020 would be `softdes-2020-03` and QEA 1b Spring 2021 would be `qea-1b-2021-01`.

For some courses, you may want to have a separate repository for grading. In this case, your grading repository should be the title of the semester repository, with `-grading` appended. Thus the grading repository for SoftDes Fall 2020 would be `softdes-2020-03-grading`.
